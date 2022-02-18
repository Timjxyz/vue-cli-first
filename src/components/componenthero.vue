<template>
   <!-- Inizio sezione jumbotron -->
    <section id="jumbotron">

        <div class="container">
            <!-- Titolo della pagina e paragrafo -->
            <h1 id="title-text">Il tuo posto per parlare</h1>
            <p id="p-title">Che tu faccia parte di un club scolastico,gruppo di gamer,comunità artistica mondiale o semplicemente di un piccolo gruppo di amici che vuole passare il tempo assieme,Discord rende più facile chiacchierare ogni giorno e ritrovarsi più spesso.</p>

            <!-- Btn per scaricare discord per mac o per aprire la pagina sul browser -->
            <a class="btn big btn-mac" href="#"><i class="fas fa-long-arrow-alt-down"></i>Scarica per Mac</a>
            <a class="btn big btn-browser" href="#">Apri Discord nel tuo browser</a>
        </div>

    </section>
</template>

<script>
export default {
  name: 'componenthero'
}
</script>

<style scoped>
.btn{
    display: inline-block;
    text-decoration: none;
    background-color: white;
    color: black;
    padding: 7px 16px;


}

.btn.big{
    display: inline-block;
    text-decoration: none;
    background-color: white;
    color: black;
    border-radius: 28px;
    padding: 16px 32px;
    font-size: 20px;
    font-weight: 600;
    
}
#jumbotron{
    background-image: url("../assets/jumbo.png");
    min-height: 420px;
    background-size: cover;
    background-position: center;
      
}

#jumbotron .container{
    width: 60%;
    max-width: 780px;
    margin: auto;
    text-align: center;
    color: white;  
}

#title-text{
    font-size: 56px;
}

#p-title{
    font-size: 20px;
    margin-top: 40px;
}

#jumbotron .btn-mac{
    margin-top: 24px;
    margin-right: 24px;

}

#jumbotron .btn-browser{
    margin-top: 24px;
    background-color: #23272a;
    color: white;
    

}
</style>