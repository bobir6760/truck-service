<template>
  <div class="volvo">
    <div class="container">
      <div class="volvo-wrapper">
        <div class="volvo-wrapper__block">
          <div class="volvo-title">
            У вас вопрос кто мы <br />
            а кто мы блин
          </div>
          <div class="volvo-wrapper__subtitle">
            <div class="volvo-subtitle">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc
              odio<br />
              in et, lectus sit lorem id integer.
            </div>
            <div class="volvo-subtitle">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc
              odio<br />
              in et, lectus sit lorem id integer.
            </div>
            <div class="volvo-subtitle">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc
              odio<br />
              in et, lectus sit lorem id integer.
            </div>
          </div>
        </div>

        <div class="volvo-wrapper-items">
          <div class="volvo__item">
            <img src="@/assets/img/SCANIA.jpg" alt="" />
          </div>
          <div class="volvo__item">
            <img src="@/assets/img/VOLVO.jpg" alt="" />
          </div>
          <div class="volvo__item odd">
            <img src="@/assets/img/MAN.jpg" alt="" />
          </div>
          <div class="volvo__item">
            <img src="@/assets/img/DAF.jpg" alt="" />
          </div>
          <div class="volvo__item">
            <img src="@/assets/img/RENAULT.jpg" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Volvo",
};
</script>

<style scoped lang="scss">
.volvo {
  padding: 50px 0px;
}
.volvo-wrapper {
  display: flex;
}
.volvo-wrapper__block {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.volvo-title {
  font-size: 50px;
  font-weight: bold;
  text-align: center;
}

.volvo-wrapper-items {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 15px;
  width: 50%;
}

.volvo__item {
  display: flex;
  justify-content: center;
  align-items: center;

  &.odd {
    grid-column: span 2;
  }

  img {
    width: 100px;
    height: 100px;
    object-fit: contain;
  }
}

.volvo-wrapper__subtitle {
  text-align: center;
}
.volvo-subtitle {
  font-size: 20px;
}
@media screen and (max-width: 1200px) {
}
@media screen and (max-width: 992px) {
  .volvo-title {
    font-size: 35px;
  }
  .volvo-subtitle {
    font-size: 16px;
  }
}
@media screen and (max-width: 768px) {
  .volvo-title {
    font-size: 30px;
  }
  .volvo-subtitle {
    font-size: 12px;
  }
}
@media screen and (max-width: 576px) {
  .volvo-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
  }
  .volvo-wrapper__block {
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  .volvo-wrapper-items {
    width: 100%;
  }
}
</style>
