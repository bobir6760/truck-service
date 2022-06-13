<template>
  <div class="location">
    <div class="container">
      <div class="location-wrapper">
        <div class="location-wrapper__item">
          <div class="location-title">Где мы?</div>
          <div class="location-wrapper__subtitle">
            <div class="location-subtitle">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc odio
              in et, lectus sit lorem id integer.
            </div>

            <div class="location-subtitle">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc odio
              in et, lectus sit lorem id integer.
            </div>

            <div class="location-subtitle">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc odio
              in et, lectus sit lorem id integer.
            </div>
          </div>
        </div>

        <div class="location-image">
          <img src="@/assets/img/Maps.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Location",
};
</script>

<style lang="scss" scoped>
.location {
  padding: 50px 0px;
}
.location-wrapper {
  padding: 10px;
  display: flex;
  justify-content: space-between;
  background-color: #f4f4f4;
  align-items: center;
  gap: 40px;
}
.location-title {
  font-weight: bold;
  font-size: 40px;
  cursor: pointer;
}
.location-subtitle {
  font-size: 20px;
  cursor: pointer;
}
.location-image img {
  width: 100%;
  cursor: pointer;
}
@media screen and (max-width: 1200px) {
}
@media screen and (max-width: 992px) {
  .location-title {
    font-size: 30px;
  }
  .location-subtitle {
    font-size: 15px;
  }
}
@media screen and (max-width: 768px) {
  .location-title {
    font-size: 25px;
  }
  .location-subtitle {
    font-size: 12px;
  }
}
@media screen and (max-width: 576px) {
  .location-title {
    font-size: 25px;
  }
  .location-subtitle {
    font-size: 12px;
  }
  .location-wrapper {
    display: flex;
    align-items: center;
    gap: 30px;
    flex-direction: column;
  }
}
</style>
