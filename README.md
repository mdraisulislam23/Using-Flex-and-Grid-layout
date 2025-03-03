<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="style.css" rel="stylesheet">
    <style>
      body{
    border-radius: 10px;
    border-color:10px solid darkorange;
    background-color:whitesmoke;
    ;
}

.flexdiv1{
    display: flex;
    padding: 0px;
    margin: 0px;
    background-color: aqua;
}
 .f{
   width: 20%;
   padding-top: 20px;
   padding-bottom: 20px;
   border-color: 10px solid black;
   background-color:#0f1111;
   border-collapse: collapse;
   text-align: center;
   color: white;
   
 }

.fd{ 
    color: white;
    width: 40%;
    padding-top: 20px;
    padding-bottom: 20px;
    border-color: 2px solid black;
    background-color:#0f1111;
    text-align: center;
}
.flexdiv2{
    display: flex;
    padding: 0px;
    margin: 0px;
    background-color:whitesmoke;
}
.S{
    width: 20%;
    padding-top: 10px;
    padding-bottom: 10px;
    border-color: 2px solid black;
    background-color: #4b5c5c;
    color:white;
    text-align: center;
    margin-bottom: 10px;
}

 .grid{
    color: white;
    border: 1px solid red;
    background-color: #4d4e4e;
    text-align: center;
 }
 .grid-container{

    display: grid;
    border: 1px solid red;
    grid-template-columns: repeat(auto-fit,minmax(300px,1fr));
    justify-content: center;
    gap: 10px;
 }
 .End{
    text-align: center;
    
 }



    </style>
</head>
<body>
    <div class="flexdiv1 ">
        <div class="f">FDA</div>
        <div class="fd"> <strong>Feeling of Different Age</strong></div>
        <div class="f">Mother</div>
        <div class="f">Father</div>
    </div>
    <div class="flexdiv2 ">
        <div class="S">Story</div>
        <div class="S">Video</div>
        <div class="S">Communication</div>
        <div class="S"><button>search</button></div>
        <div class="S">Help</div>
    </div>


    



    <div class="grid-container">
        <div class="grid">
            <h2>First Drid</h2>
            <p>Lorem ipsum odor amet, consectetuer adipiscing elit.
              Ridiculus sit nisl laoreet facilisis aliquet.
              Potenti dignissim litora eget montes rhoncus 
              sapien neque urna.
            </p>
        </div>
        <div class="grid">
            <h2>First Drid</h2>
            <p>Lorem ipsum odor amet, consectetuer adipiscing elit.
              Ridiculus sit nisl laoreet facilisis aliquet.
              Potenti dignissim litora eget montes rhoncus 
              sapien neque urna.
            </p>
        </div>
        <div class="grid">
            <h2>First Drid</h2>
            <p>Lorem ipsum odor amet, consectetuer adipiscing elit.
              Ridiculus sit nisl laoreet facilisis aliquet.
              Potenti dignissim litora eget montes rhoncus 
              sapien neque urna.
            </p>
        </div>
        <div class="grid">
            <h2>First Drid</h2>
            <p>Lorem ipsum odor amet, consectetuer adipiscing elit.
              Ridiculus sit nisl laoreet facilisis aliquet.
              Potenti dignissim litora eget montes rhoncus 
              sapien neque urna.
            </p>
        </div>
        <div class="grid">
            <h2>First Drid</h2>
            <p>Lorem ipsum odor amet, consectetuer adipiscing elit.
              Ridiculus sit nisl laoreet facilisis aliquet.
              Potenti dignissim litora eget montes rhoncus 
              sapien neque urna.
            </p>
        </div>
        <div class="grid">
            <h2>First Drid</h2>
            <p>Lorem ipsum odor amet, consectetuer adipiscing elit.
              Ridiculus sit nisl laoreet facilisis aliquet.
              Potenti dignissim litora eget montes rhoncus 
              sapien neque urna.
            </p>
        </div>
    </div>

    <div class="End">
        <h1>End Now</h1>
    </div>
</body>
</html>
