<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <div class="d-flex mb-5">
          <h5 class="vizia">Naša vízia</h5>
          <h5 class="openlabe">v Openlabe</h5>
        </div>

        <p class="content">
          Veríme, že otvorený prístup a kvalitné vzdelanie sú základom úspechu
          jednotlivca ako aj prosperujúcej spoločnosti.
        </p>
        <p class="content">
          Uvedomujeme si, že ak chceme niečo zmeniť, musíme ísť príkladom. Našim
          cieľom je rozšíriť princípy OpenLab-u na všetkých úrovniach škôl a
          nastaviť svetový štandard vzdelávania v školstve v technológiách.
        </p>
      </div>

      <div class="col">
        <div class="container">
          <div class="row">
            <div class="bcard m-2 col">
              <p class="bnumber d-flex justify-content-end">11</p>
              <p class="binfo d-flex justify-content-end">tried</p>
            </div>
            <div class="gcard m-2 col">
              <p class="gnumber d-flex justify-content-end">11</p>
              <p class="ginfo d-flex justify-content-end">tried</p>
            </div>
          </div>
          <div class="row">
            <div class="ycard m-2 col">
              <p class="ynumber d-flex justify-content-end">11</p>
              <p class="yinfo d-flex justify-content-end">tried</p>
            </div>
            <div class="rcard m-2 col">
              <p class="rnumber d-flex justify-content-end">11</p>
              <p class="rinfo d-flex justify-content-end">tried</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "vizia",
};
</script>

<style scoped>
.vizia {
  margin-right: 5px;
  font-size: 35px;
  font-weight: 400;
}

.openlabe {
  font-size: 35px;
  font-weight: 700;
}

.content {
  color: #566b8d;
  font-size: 16px;
}

.bnumber {
  color: #5b94d7;
  font-size: 500%;
  margin-bottom: 0px;
  line-height: 1 !important;
  font-weight: 700 !important;
  margin-bottom: 0, 25rem;
}
.bcard {
  padding-top: 20px;
  background-color: rgba(221, 236, 251, 0.4);
}
.binfo {
  padding-right: 14px;
  font-size: 18px;
  font-weight: 700 !important;
  color: #5b94d7;
}

.gnumber {
  color: #5cc19a;
  font-size: 500%;
  margin-bottom: 0px;
  line-height: 1 !important;
  font-weight: 700 !important;
  margin-bottom: 0, 25rem;
}
.gcard {
  padding-top: 20px;
  background-color: rgba(156, 238, 204, 0.4);
}
.ginfo {
  padding-right: 14px;
  font-size: 18px;
  font-weight: 700 !important;
  color: #5cc19a;
}

.ynumber {
  color: #dbca68;
  font-size: 500%;
  margin-bottom: 0px;
  line-height: 1 !important;
  font-weight: 700 !important;
  margin-bottom: 0, 25rem;
}
.ycard {
  padding-top: 20px;
  background-color: rgba(238, 226, 156, 0.4);
}
.yinfo {
  padding-right: 14px;
  font-size: 18px;
  font-weight: 700 !important;
  color: #dbca68;
}

.rnumber {
  color: #b95e73;
  font-size: 500%;
  margin-bottom: 0px;
  line-height: 1 !important;
  font-weight: 700 !important;
  margin-bottom: 0, 25rem;
}
.rcard {
  padding-top: 20px;
  background-color: rgba(238, 156, 156, 0.4);
}
.rinfo {
  padding-right: 14px;
  font-size: 18px;
  font-weight: 700 !important;
  color: #b95e73;
}
</style>
