<template>
<div class="service">
      <div class="container">
        <div class="service-wrapper">
          <div class="service-container">
            <div class="service-big__title">Affordable truck service</div>
            <div class="home__title">
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc
                odio in et, lectus sit lorem id integer.
              </p>
            </div>
            <button class="service-btn">Чета сделать</button>
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
name:"Service"
}
</script>

<style scoped lang="scss">
.service {
  padding: 50px 0px;
}
.service-wrapper {
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 95%;
}
.service-container {
  padding: 30px;
  margin-left: 70px;
}
.service-big__title {
  text-align: start;
  font-size: 60px;
  font-weight: bold;
  padding: 50px 0px 20px;
  cursor: pointer;
}
.service-image {
  display: flex;
  justify-content: center;
  width: 100%;
  height: 500px;
  cursor: pointer;
}
.service-btn {
  background: #4762ff;
  border-radius: 15px;
  padding: 15px 60px 15px 50px;
  border: none;
  margin-top: auto;
  color: white;
  font-size: 20px;
  margin-top: 30px;
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
}
@media screen and (max-width: 768px) {
}
@media screen and (max-width: 576px) {
}
</style>