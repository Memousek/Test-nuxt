<template>
  <div class="content__section">
    <main>
      <h1>Hellou Word</h1>
      <span>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate eos
        est quo maiores dicta itaque reiciendis placeat facilis, deserunt odit
        in, consequatur earum dolorem delectus dolorum quae blanditiis
        repellendus deleniti?
      </span>
    </main>

    <footer class="footer__section">
      <div class="footer__wrapper">
        <div class="footer__copy">
          <span>&copy; 2021 Všechna práva jsou vyhrazena</span>
          <a href="#">Něcí jméno třeba</a>
        </div>
        <div class="footer__author">
          Web je od <a href="https://memousek.eu">Vojtíška</a>
        </div>
      </div>
    </footer>
  </div>
</template>


<style scoped>
h1 {
  text-align: center;
}
.footer__section {
  position: fixed;
  bottom: 0;
  width: 100%;
  padding: 10px 50px;
  max-width: 500px;
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
  border-top: 1px solid black;
}

.footer__wrapper {
  display: flex;
  justify-content: space-between;
}
</style>