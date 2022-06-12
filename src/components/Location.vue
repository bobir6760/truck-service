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
  padding: 20px;
  display: flex;
  justify-content: space-between;
  background-color: #f4f4f4;
  align-items: center;
  gap: 50px;
}
.location-title {
  font-weight: bold;
  font-size: 50px;
  cursor: pointer;
}
.location-subtitle {
  font-size: 25px;
  cursor: pointer;
}
.location-image img {
  width: 100%;
  cursor: pointer;
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
