<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS</title>
</head>
<script>
    function bam(){
        document.getElementById("click").style.display = "none";
        document.getElementById("love").style.display = "block";
    }
</script>
<style>
    .love{
        color: purple;
        display: none;
        font-size: 50px;
        margin-top: 50px;
        margin-left: 15%;
    }
    
    .body{
        margin: auto;
        margin-top: 200px;
         width: 600px;
         height: 300px;
        box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 10px;
        /* background-image: url(https://scontent.fvca1-3.fna.fbcdn.net/v/t39.30808-6/p843x403/273584213_4592038424386947_6541855128446097781_n.jpg?_nc_cat=1&ccb=1-5&_nc_sid=730e14&_nc_ohc=GA0SaWg0DrIAX_z7Tc7&_nc_ht=scontent.fvca1-3.fna&oh=00_AT9SzAS6XGHoSx9iE4Ju6U9AgAq_6-CIf7DQmxCGve2sVA&oe=6207C4CE);      background-size: cover; */
    }
    .click{
        width: 100px;
        box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 10px;
        margin-top: 50px;
        margin-left: 35%;
    }
    button:hover{
        color: black;
        background-color: red;
    }
</style>
<body >
    <div class="body">
        <marquee width="100%" behavior="alternate" bgcolor="pink" style="font-size: 50px;">  
            πHello bae!!π
        </marquee>
        <div id="click" class="click"><button onclick="bam()" style="font-size: 30px;width: 200px;">Click me!</button></div>
        <div id="love" class="love">I Love You!πβ€β€π€£</div>
    </div>
</body>
</html>
