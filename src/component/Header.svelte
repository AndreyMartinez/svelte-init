<script>
 import { Button } from 'sveltestrap';
  const handleClick = () => alert('I warned you!');

</script>


<header class="header">
 <div class="item"></div>
 <div class="principal-item"></div>
 <div class="item buttom-content">
 <div>
 <Button class="button" color="dark" outline on:click={handleClick}>
  Iniciar sesión
</Button>
<Button class="button" color="dark" outline on:click={handleClick}>
  registrarse
</Button>
</div>
   </div>
</header>



<style>
	.header{
      border-bottom: 0.2px solid #00000096;
      position: fixed;
      top: 0;
  width: 100%;
    display: flex;
    height: 4em;
	}
	.item{
	   flex-grow: 1;
	}
   .buttom-content{
          display: flex;
    margin: 1% 5% 0.1% 0%;
    flex-direction: row-reverse;
   }
   .principal-item{
    flex-grow: 4;
   }
   .button{
      margin:1%
   }
</style>