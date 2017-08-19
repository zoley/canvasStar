# canvasStar

canvas七彩星背景特效



 * 2017-08-18
 * @var star_r:star半径系数，值越大，半径越大；
 * @var star_alpha:star透明度，值越大，越透明；建议取值在1-20之间，当star_alpha=20时，透明度在0.05-0.5之间；
 * @var initStarNum:初始化star个数； 
 * @var move_distance:位移距离，即star向上跑的距离，数值越大，相同时间内，速度越快。
 * @var dot_r:dot半径系数，值越大，半径越大；
 * @var dot_alpha:dot透明度；
 * @var dot_speed:dot运动速度；
 * @var dot_vanish:dot消失条件，透明度小于vanish时消失；
 * @var dot_mindis:dot最小距离；
 * @var dot_maxdis:dot最大距离；

用法：
<body>
	<canvas id="canvas"></canvas>
	<script src="js/canvasStar.js"></script>
	<script>
		new CanvasStar().init();
	</script>
</body>

