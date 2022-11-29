<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="/all/mis.css">
</head>
<body>
    <div class="app">
        <h1>Can we hang out ? ♥ " </h1>
        <img style="margin:20px;" src="https://cdn.fbsbx.com/v/t59.2708-21/279068458_530394025371896_3068074944005340854_n.gif?_nc_cat=104&ccb=1-7&_nc_sid=041f46&_nc_eui2=AeHwQiTCDS75OalDeIJwyy5dJ3CoCikPL6gncKgKKQ8vqLx5R01anPkHTtFSnIpUJ2ultjXLnDK6DnmmrTZ0k0RO&_nc_ohc=ppwgb5X7XG4AX-1LKrk&_nc_ht=cdn.fbsbx.com&oh=03_AdT2exj554Zlj2fMkapn3q6ygY5iVj-slMmMi2LdEXruzw&oe=637D62D8" alt="fiso">
        <div class="buttonGroupe">
            <button class="button--yes" onclick="saba()">Yes</button>
            <button class="button--no">No</button>
        </div>
        
    </div>
    <script src="/all/a.js"></script>
</body>
</html>





html{background-color:rgb(202, 197, 119)}

h1{ color: red;
font-size: 50px;
display: block;
position: absolute;}


.app{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
}

.buttonGroupe{margin-top: 150px;}

button{
    position: absolute;
    display: flex;
    cursor: pointer;
    margin: 0 10px;
    padding: 10px 30px;
    background-color: rgb(108, 197, 163);
    border: none;
}
.button--no{
    right: 50%;



const b = document.querySelector('button.button--no')
b.addEventListener("mouseover", mouseHover)

function mouseHover(){
    const i=Math.floor(Math.random()*500)+1;
    const j=Math.floor(Math.random()*500)+1;
  
    b.style.left=i+"px"
    b.style.top=j+"px"
}

function saba(){
    alert("Yey THANK U  SEE U on MONDAY>< ")
}

