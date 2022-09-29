
<template>
	 /* eslint-disable */
	<div>

  
	</div>
	
   
   </template>
	
	<script>
	export default {
	  name: 'HeaderStandard',
	  
	}
	</script>
	
	/* eslint-disable */
	<style scoped lang="scss">
		 /* eslint-disable */
	   @import "../../assets/sass/variable.scss";
	   @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@300;400;500;700&family=Pacifico&display=swap');
	   
	   .container_my{
		background-image: url('../../assets/img/jumbotron-deliveboo-wide.jpg');
		background-position: center;
		background-repeat: no-repeat;
		background-size: cover;
	   
	   }
.header_top_my{
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding-top:20px ;
		padding-left:40px ;
		padding-right:40px ;
		background-color: white;
		
}
	  .interface_my{
		display: flex;
		align-items: center;
		.login_my{
		  margin-right: 20px;
		  color: $secondarycolor;
		}
		.registration_my{
		  color: $maincolor;
		}
	  }
	  .logo_my{
		color: $maincolor;
		font-family: 'Pacifico', cursive;
		font-size: 20px;
	  }
	  
	</style>