# Buzzer-Bell-widget

Widget for webpage 

Need to include in website heder  the following scripts
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>	
<link rel="stylesheet" type="text/css" href="css/style.css" >
<script type='text/javascript' src='js/jQuery.tubeplayer.js'></script>		
<script type='text/javascript' src='js/buzzerwidghet.js'></script>

Necessary for connection and comunication with Amazon Webservices they also include in heder website

<script src="js/hmacsha1.js"></script>
<script src="js/awssigner.js"></script>
<script src="js/scratchpad.js"></script>

To crate a widget in website, place this
<script>
CreateWidget("videoId", widget_size, 'UserName');
</script>

When you create  widget  to be create
Input parametars are:

o videoId
o widget size
  o 1  for video and widget  size 430x300
  o 2  for video and widget  size 320x190
  o 3  for video and widget  size 240x110
oUser name

