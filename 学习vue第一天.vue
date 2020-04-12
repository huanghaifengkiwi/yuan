<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
	    <script src="vue.js" type="text/javascript" charset="utf-8"></script>
		<!-- <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script> -->
	</head>
	<body>
		<div id="app">
          {{message}}  {{NAME}}  {{AGE}}
		</div>
		<script type="text/javascript">
			var app=new Vue({   /* VUE对象里包含element和data数据，el对应着div标签的id，data对应着message数据，初始化一个数据值为HELLO VUES*/
				el:'#app',
				data:{
					message:'HELLO VUE!',
					NAME:'Dm',
					AGE:'SAD'
				}
				
			});
		</script>
	</body>
</html>