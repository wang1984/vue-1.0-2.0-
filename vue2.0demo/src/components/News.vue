<template>
   <div class="mynews">
   	<h3>我是新闻</h3>
   	 <ul>
   	 	<li v-for="(val,index) in news">
   	 		{{val}}
   	 	</li>
   	 </ul>
   </div>
</template>
<script>
	 export default{
	 	name : 'news',
	 	data(){
	 		return{
	 			news:['111','222','333']
	 		}
	 	}
	 }

</script>

<style scoped>
	 li{
		list-style: none;
		line-height: 30px;
		font-size: 20px;
		color: #f60
	}
	div{
		border: 1px solid #000;
	}
</style>