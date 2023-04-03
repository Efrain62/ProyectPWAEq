<script>
  import { Link } from "svelte-routing";
</script>
<center>
<h1>Tienda</h1>
<p>
  <small>
    <b>Tienda gestora de productos deportivos (PWA)</b>
  </small>

<p>Integrantes del equipo:</p>


<div class="bloque">
  
    <div class="resumen">
      <span class="opcion">191565</span>
      <span class="descripcion">Jorge Emilio Rodriguez Valdes</span>
    </div>
  

  
    <div class="resumen">
      <span class="opcion">191508</span>
      <span class="descripcion">
        Jorge Efrain Loera Rubalcava
      </span>
    </div>
  

  
    <div class="resumen">
      <span class="opcion">191542</span>
      <span class="descripcion">
        Juan Carlos Gonzalez Huerta
      </span>
    </div>
  

</div>
</center>

<style>
  h1,
  div,
  p {
    padding: 3px;
  }
  div {
    padding: 30px;
  }

  .bloque {
    display: flex;
    flex-direction: column;
  }
  .resumen {
    display: flex;
    flex-wrap: wrap;    
    padding: 5px;
    margin: 0 0 15px;
    border: 1px solid #000;
    border-radius: 4px;
    box-shadow: 0 0 3px rgba(0, 0, 0, 0.19);
    border: 1px solid #857C7A;
    border-radius: 4px;
  }

  .opcion {
    display: flex;   
    word-break: break-word;
    padding: 0 10px;
    font-size: 14px;
    font-weight: 700;
    text-shadow: 0 1px 0 rgba(0, 0, 0, 0.1);
    font-family: sans-serif;
    color: #3b4151;
    border-radius: 4px;
    background: #857C7A;
    min-width: 140px;
    padding: 10px;
  }

  .descripcion {
    font-size: 14px;
    flex: 1 1 auto;
    word-break: break-word;
    font-family: sans-serif;
    color: #3b4151;
    padding-top: 10px;
    padding-left: 10px;
  }
</style>
