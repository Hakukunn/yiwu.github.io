<!DOCTYPE html>
<html>
<head>
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	<meta name="viewport" content="initial-scale=1.0, user-scalable=no" />
	<style type="text/css">
	body, html,#allmap {width: 100%;height: 100%;overflow: hidden;margin:0;font-family:"微软雅黑";}
	</style>
	<script type="text/javascript" src="//api.map.baidu.com/api?v=2.0&ak=LXpXl6bnXk8EPypPqxwu1CL1s2j0jLU9"></script>
	<title>地图展示</title>
</head>
<body>
	<div id="allmap"></div>
	<p>义乌</p>
        <img src="https://image.baidu.com/search/detail?ct=503316480&z=0&ipn=d&word=%E4%B9%89%E4%B9%8C&step_word=&hs=0&pn=2&spn=0&di=7060663421280190465&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&istype=0&ie=utf-8&oe=utf-8&in=&cl=2&lm=-1&st=undefined&cs=3680648266%2C3548966307&os=3173605256%2C2595801153&simid=3680648266%2C3548966307&adpicid=0&lpn=0&ln=1824&fr=&fmq=1646915292796_R&fm=&ic=undefined&s=undefined&hd=undefined&latest=undefined&copyright=undefined&se=&sme=&tab=0&width=undefined&height=undefined&face=undefined&ist=&jit=&cg=&bdtype=0&oriquery=&objurl=https%3A%2F%2Fgimg2.baidu.com%2Fimage_search%2Fsrc%3Dhttp%3A%2F%2Fp8.itc.cn%2Fq_70%2Fimages01%2F20210531%2F13599242b1bd4da98ca42fe2b0ff3b9c.jpeg%26refer%3Dhttp%3A%2F%2Fp8.itc.cn%26app%3D2002%26size%3Df9999%2C10000%26q%3Da80%26n%3D0%26g%3D0n%26fmt%3Djpeg%3Fsec%3D1649507314%26t%3D1c4ce0e7b299d808ee4bd6879fcfb506&fromurl=ippr_z2C%24qAzdH3FAzdH3Fooo_z%26e3Bf5i7_z%26e3Bv54AzdH3FwAzdH3F9mlmmbd90_8d8aab0c9&gsm=3&rpstart=0&rpnum=0&islist=&querylist=&nojc=undefined&dyTabStr=MCwzLDEsMiw2LDUsNCw4LDcsOQ%3D%3D"/height="300"/>
	<a href="https://baike.baidu.com/item/%E4%B9%89%E4%B9%8C/214555?fr=aladdin">义乌介绍</a>
</body>
</html>
<script type="text/javascript">
	// 百度地图API功能
	var map = new BMap.Map("allmap");    // 创建Map实例
	map.centerAndZoom(new BMap.Point(120.076983,29.31241), 11);  // 初始化地图,设置中心点坐标和地图级别
	//添加地图类型控件
	map.addControl(new BMap.MapTypeControl({
		mapTypes:[
            BMAP_NORMAL_MAP,
            BMAP_HYBRID_MAP
        ]}));	  
	map.setCurrentCity("义乌");          // 设置地图显示的城市 此项是必须设置的
	map.enableScrollWheelZoom(true);     //开启鼠标滚轮缩放
</script>
