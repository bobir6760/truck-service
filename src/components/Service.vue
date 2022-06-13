<template>
  <div class="service">
    <div class="container">
      <div class="service-wrapper">
        <div class="service-item">
          <div class="service-wrapper__title">Affordable truck service</div>
          <div class="service-wrapper__subtitle">
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc odio
              in et, lectus sit lorem id integer.
            </p>
          </div>
          <div class="service-item__btn">
            <button class="service-btn">Чета сделать</button>
          </div>
        </div>
        <div class="service-image">
          <img src="@/assets/img/FURA.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Service",
};
</script>

<style scoped lang="scss">
.service {
  padding: 50px 0px;
}
.service-wrapper {
  display: flex;
  align-items: center;
}
.service-wrapper__title {
  text-align: start;
  font-size: 60px;
  font-weight: bold;
  cursor: pointer;
}
.service-image img {
  width: 100%;
  cursor: pointer;
}
.service-item {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.service-btn {
  background: #4762ff;
  border-radius: 15px;
  padding: 15px;
  border: none;
  color: white;
  font-size: 20px;
  cursor: pointer;
}
.service-btn:hover {
  transition: 0.5s;
  background: black;
  border-radius: 5px;
}
@media screen and (max-width: 1200px) {
}
@media screen and (max-width: 992px) {
  .service-image img {
    object-fit: contain;
    cursor: pointer;
  }
  .service-wrapper__title {
    font-size: 40px;
  }
  .service-wrapper {
    display: flex;
    gap: 30px;
  }
}
@media screen and (max-width: 768px) {
  .service-btn {
    padding: 12px;
    font-size: 15px;
  }
  .service-wrapper__title {
    font-size: 30px;
  }
  .service-wrapper__subtitle {
    font-size: 12px;
  }
}
@media screen and (max-width: 576px) {
  .service-wrapper {
    flex-direction: column;
  }
}
</style>
