<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=0, minimum-scale=1.0, maximum-scale=1.0">

<title>iScroll demo: horizontal scrolling</title>

<script type="text/javascript" src="https://raw.githack.com/windyisland/hyw/master/iscroll.js"></script>
<script type="text/javascript" src="https://raw.githack.com/windyisland/hyw/master/utils.js"></script>
<script type="text/javascript">
var myScroll;
function loaded () {
	myScroll = new IScroll('#wrapper', { scrollX: true, scrollY: false, mouseWheel: true });
}
document.addEventListener('touchmove', function (e) { e.preventDefault(); }, isPassive() ? {
	capture: false,
	passive: false
} : false);
</script>
<style type="text/css">

#wrapper {
	z-index: 1;
	top: 45px;
	bottom: 48px;
	left: 0;
	width: 100%;
	overflow: hidden;
}
#scroller ul {
	list-style: none;
	padding: 0;
	margin: 0;
	width: 100%;
	height: 100%;
	text-align: center;
}

#scroller li {
	display: block;
	float: left;
	width: 100px;
	height: 100%;
	border-right: 1px solid #ccc;
	background-color: #fafafa;
	font-size: 14px;
}

</style>
</head>
<body onload="loaded()">

<div id="wrapper">
	<div id="scroller">
		<ul>
			<li>Cell 1</li>
			<li>Cell 2</li>
			<li>Cell 3</li>
			<li>Cell 4</li>
			<li>Cell 5</li>
			<li>Cell 1</li>
			<li>Cell 2</li>
			<li>Cell 3</li>
			<li>Cell 4</li>
			<li>Cell 5</li>
			<li>Cell 1</li>
			<li>Cell 2</li>
			<li>Cell 3</li>
			<li>Cell 4</li>
			<li>Cell 5</li>
			<li>Cell 1</li>
			<li>Cell 2</li>
			<li>Cell 3</li>
			<li>Cell 4</li>
			<li>Cell 5</li>
			<li>Cell 1</li>
			<li>Cell 2</li>
			<li>Cell 3</li>
			<li>Cell 4</li>
			<li>Cell 5</li>
			<li>Cell 1</li>
			<li>Cell 2</li>
			<li>Cell 3</li>
			<li>Cell 4</li>
			<li>Cell 5</li>
		</ul>
	</div>
</div>
<h1>现代地图学作业</h1>>
<br>
<h2>这是山东省GDP分布图</h2>
<iframe src="https://api.mapbox.com/styles/v1/fengyu1995/cjb31h5pkpbnk2soctyezx36a.html?fresh=true&title=true&access_token=pk.eyJ1IjoiZmVuZ3l1MTk5NSIsImEiOiJjamIzMDNld2o3czkxMnFucWNjc2ozc2tjIn0.c829L8C-KkQVaeBBks6D_w#5.6/36.369/118.077" width="700px" height="500px" > </iframe><br>
<h2>这是山东省pm2.5分布图</h2>
<iframe src="https://api.mapbox.com/styles/v1/xieyunpeng/cjbkfej0p27mb2sl13g9ptu79.html?fresh=true&title=true&access_token=pk.eyJ1IjoieGlleXVucGVuZyIsImEiOiJjajFvbTRzNWowMTk5MzJwaTZwY3Vxd2x0In0.fFYplGoeSpjBlsqBi2iovA#6.4/36.833770/118.715140/0" width="700px" height="500px" > </iframe><br>
<h2>山东省降雨量分布图</h2>
<iframe src="https://api.mapbox.com/styles/v1/fengyu1995/cjbkpzmwp1erm2rpblfb7dgu1.html?fresh=true&title=true&access_token=pk.eyJ1IjoiZmVuZ3l1MTk5NSIsImEiOiJjamIzMDNld2o3czkxMnFucWNjc2ozc2tjIn0.c829L8C-KkQVaeBBks6D_w#5.9/36.380410/119.567368/0" width="700px" height="500px" > </iframe><br>


</body>

</html>

