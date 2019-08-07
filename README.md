
<!DOCTYPE html>
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
<html>
<!DOCTYPE html> 
<html> 
<body> 

<button onclick="myFunction()" type="button">Add a new text track</button><br>
 
<video id="video1" width="320" height="176" controls="controls">
  <source src="mov_bbb.mp4" type="video/mp4">
  <source src="mov_bbb.ogg" type="video/ogg">
  Your browser does not support HTML5 video.
</video>

<script>
var vid = document.getElementById("video1");

function myFunction() { 
  var text1 = vid.addTextTrack("caption");
  text1.addCue(new TextTrackCue("Test text", 01.000, 04.000, "", "", "", true));
} 
</script> 

<p>Video courtesy of <a href="https://www.bigbuckbunny.org/" target="_blank">Big Buck Bunny</a>.</p>

</body> 
</html>

<body>

<h2>HTML Image</h2>
<img src="pic_trulli.jpg" alt="Trulli" width="500" height="333">

</body>
</html>




</body>
</html>
