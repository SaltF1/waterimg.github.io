@@ -0,0 +1,58 @@
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Lists</title>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
 <script src="https://atuin.ru/demo/ripples/jquery.ripples-min.js"></script>
</head>
<style type="text/css">
	body{
		background-image: url('https://ak7.picdn.net/shutterstock/videos/4297247/thumb/1.jpg')center;
		background-color: #1A162A;
		margin: 0px;
		padding: 0px;
	}
	.full-landing-image{
		width: 100%;
		height: 90vh;
		background: url('https://pbs.twimg.com/media/D-U2xmnX4AEf0Wj?format=jpg&name=medium')no-repeat center;
		background-size: cover;
	}
.Txt {
    font-size: 79px;
    font-weight: bold;
    line-height: 0;
    position: middle;
    display: inline-block;
    margin: .25px;
    padding: .5px .75px;
    text-align: center;
    /* Color fallback */
    color: #fff;
    -webkit-background-clip: text;

    -webkit-text-fill-color: transparent;
}
.Txt{
    background-image: url('https://i.gifer.com/WXdf.gif');
}

</style>
<body>
	<div class="Txt">
	<h1>Night~</h1>
    </div>
	<div class="full-landing-image">
		
	</div>
<script type="text/javascript">
	$('.full-landing-image').ripples({
    resolution: 256,
    dropRadius: 18,
    perturbance: 0.04
});
 
</script>
</body>
</html>
