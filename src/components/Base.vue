<template>
  <div class="base">
    <div class="container">
      <div class="base-wrapper">
        <div class="base-wrapper__title">Фоточки</div>
        <div class="base-image">
          <img src="@/assets/img/baza.png" alt="" />
        </div>
        <div class="base-item__image">
          <img src="@/assets/img/knopka.svg" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Base",
};
</script>

<style scopes lang="scss">
.base {
  padding: 50px 0px;
}
.base-wrapper {
  padding: 50px 0px;
  text-align: center;
}
.base-wrapper__title {
  font-size: 50px;
  font-weight: 900;
  text-align: center;
  cursor: pointer;
}
.base-wrapper__title:hover {
  text-decoration: underline crimson;
}
.base-image img {
  object-fit: contain;
  cursor: pointer;
}
.base-item__image img {
  cursor: pointer;
  object-fit: contain;
}
@media screen and (max-width: 1200px) {
}
@media screen and (max-width: 992px) {
}
@media screen and (max-width: 768px) {
}
@media screen and (max-width: 576px) {
}
</style>
