<template>
<div class="blu d-flex justify-content-center">
  <div class=" position-relative mb-4 mb-md-5">
    <div class="row d-flex justify-content-center">
        <div class="col justify-content-center">
            <h1>Inštitút stredoškolského odborného vzdelávania
                zameraný na IT & AI
            </h1>
            <p>Realizujeme odborné vzdelávanie zamerané na IT pre štátne školy ako nový štandard formálneho vzdelávania</p>
        </div>



        <div class="col d-flex justify-content-center position">
            <img src="https://openlab.sk/wp-content/themes/wp-bootstrap-starter/assets/images/main-home.png" 
                 alt=""
                 class="glasnak"
                 >
        </div>
    </div>
  </div>
</div>
</template>

<script>


export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Text',
}
</script>

<style scoped>
    .blu{
        background-color: red !important;
        height: 100%;
        align-self: baseline;
    }

    .glasnak{
    position: absolute;
    left: 70%;
    bottom: 0;
    height: auto !important;
    width: auto !important;
    max-width: 50%;
    max-height: 95%;
    width: 20rem !important;
    z-index: 99;
        
    }
</style>

///toto musim prerobit :)