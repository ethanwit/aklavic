-----------------------------
Replace your html code:
--------------------------
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Website</title>
    <link href="style.css" rel="stylesheet">
  </head>
  <body>
<div id="content">
<div id="toptxt">
Fred's fanclub, Only fans and memers allowed! Affiliated with thememers.com.
</div>
dina is hot
</div>
<div id="vid">
    <iframe class="embed-responsive-item"id="ytplayer" type="text/html" width= 100%; height=100%; src="https://www.youtube.com/embed/cVm1AK-l3Zg?&autoplay=1&loop=1&rel=0&showinfo=0&color=white&iv_load_policy=3&playlist=cVm1AK-l3Zg"
      frameborder="0" allowfullscreen></iframe>
</div>
 
  </body>
</html>
--------------------------------------
Css:
Make css file with name "style.css" and put it in the same folder as index.html
---------------------------------------
 
#content{
width: 80%;
margin-left: 10%;  
   
}
#toptxt{
    width: 100%;
  border: solid red 2px;  
  text-align: center;
   
}
#vid{
    position: absolute;
    margin-left: 10%;
z-index: -10;
height: 100%;
width: 80%;    
   
   
}
