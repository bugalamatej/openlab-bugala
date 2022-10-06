<template>
  <div class="container">
    <div class="main-text">
      <div class="d-flex justify-content-center row">
        <div class="d-flex justify-content-center">
          <h2 class="mr-1 preco fsh">Prečo</h2>
          <h2 class="openlab ml-1 fw fsh">OpenLab?</h2>
        </div>
        <p class="text-center text mb-5">
          V OpenLabe študentov učíme najnovšie technológie. Zároveň im dávame
          veľkú slobodu, pričom ich vedieme k zodpovednosti a samostatnosti,
          učíme ich princípy partnerského prístupu, pracovať v tíme, trénujeme
          ich schopnosti sebareflexie a podnecujeme ich kreativitu. Takto
          študentov pripravujeme osobnostne aj tech zručnosťami na veľké veci,
          ktoré môžu v budúcnosti tvoriť.
        </p>
      </div>
      <div class="container d-flex justify-content-center">
        <div class="cards row">
          <div class="col">
            <img
              src="https://openlab.sk/wp-content/themes/wp-bootstrap-starter/assets/images/select.svg"
              alt=""
              class="card-img d-flex"
            />
            <h5 class="rozvoj fw mt-3 mb-3">Celospoločenský rozvoj</h5>
            <p class="osnovy">
              Osnovy aj učebné materiály pre všetky tech oblasti sú open source.
            </p>
          </div>
          <div class="col">
            <img
              src="https://openlab.sk/wp-content/themes/wp-bootstrap-starter/assets/images/support.svg"
              alt=""
              class="card-img d-flex"
            />
            <h5 class="rozvoj fw mt-3 mb-3">Učenie praxou</h5>
            <p class="osnovy">
              Študentov vedieme k tímovému riešeniu problémov.
            </p>
          </div>
          <div class="col">
            <img
              src="https://openlab.sk/wp-content/themes/wp-bootstrap-starter/assets/images/intership.svg"
              alt=""
              class="card-img d-flex"
            />
            <h5 class="rozvoj fw mt-3 mb-3">Rozvoj talentu</h5>
            <p class="osnovy">
              Vytvárame šikovné tímy schopné riešiť veľké problémy.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "why",
};
</script>

<style scoped>
.card-img {
  max-height: 12%;
  display: flex !important;
  justify-content: flex-start !important;
}

.cards {
  max-width: 70%;
}

.fw {
  font-weight: 700;
}

.openlab {
  margin-left: 1%;
}

.fsh {
  font-size: 200%;
}

.preco {
  font-weight: 300 !important;
}

.text {
  color: #566b8d;
  font-weight: 500 !important;
}

.rozvoj {
  font-size: 20px;
}

.osnovy {
  font-size: 14px;
  color: #566b8d;
}
</style>
