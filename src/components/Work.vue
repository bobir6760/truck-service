<template>
  <div class="work">
    <div class="container">
      <div class="work-wrapper">
        <div class="work-item__image">
          <img src="@/assets/img/rabota.png" alt="" />
        </div>
        <!-- <div class="form">
          <div class="work-title">
            Остались <br />
            вопросы?
          </div>
          <div class="work-subtitle">
            Lorem ipsum dolor sit amet, consectetur adipiscing <br />
            Nunc odio in et, lectus sit lorem id integer.
          </div>
          <div class="work-item">
            <div>
              <input placeholder="имя" type="text" name="" value="" />
            </div>
            <div>
              <input
                placeholder="номер телефона"
                type="text"
                name=""
                value=""
              />
            </div>
          </div>
          <button class="btn-work">Отправить</button>
        </div> -->
        <div class="work-body">
          <div class="work-wrapper__image">
            <img src="@/assets/img/logotip.png" alt="" />
          </div>
          <div class="work-wrapper__item">
            <div class="work-wrapper__title">Главная</div>
            <div class="work-wrapper__subtitle">Ето мы</div>
            <div class="work-wrapper__subtitle">Кто мы</div>
            <div class="work-wrapper__subtitle">Почему мы</div>
            <div class="work-wrapper__subtitle">Остались вопросы</div>
            <div class="work-wrapper__subtitle">Контакты</div>
          </div>
          <div class="work-wrapper__item">
            <div class="work-wrapper__title">Контакты</div>
            <div class="work-wrapper__subtitle">+7 (708) 802 88 88</div>
            <div class="work-wrapper__subtitle">+7 (708) 803 88 88</div>
            <div class="work-wrapper__subtitle">+7 (708) 51 51 518</div>
            <div class="work-wrapper__subtitle">+7 (700) 51 51 518</div>
            <div class="work-truck">
              <div class="work-truck__set">
                <div class="work-truck__icon">
                  <img src="@/assets/img/whatsapp.svg" alt="" />
                </div>
                <div class="work-truck__number">+7 (708) 802 88 88</div>
              </div>
              <div class="work-truck__set">
                <div class="work-truck__icon">
                  <img src="@/assets/img/drop.svg" alt="" />
                </div>
                <div class="work-truck__title">г. Бишкек, ул. Ляляля 69</div>
              </div>
            </div>
          </div>
          <div class="work-wrapper__item">
            <div class="work-wrapper__title">Следите за нами</div>
            <div class="work-image">
              <div class="work-icon">
                <img src="@/assets/img/Facebook.svg" alt="" />
              </div>
              <div class="finish-subtitle">truck_service_ofFicIaL</div>
            </div>
            <div class="work-image">
              <img src="@/assets/img/Instagram.svg" alt="" />
              <div class="finish-subtitle">truck_service_ofFicIaL</div>
            </div>
          </div>
        </div>
        <div class="work-item__title">
          <p>Copyright © Truck Services 2022. All rights reserved.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Work",
};
</script>

<style lang="scss" scoped>
.work {
  padding: 50px 0px;
}
.work-wrapper {
  position: relative;
  background-color: black;
}
.work-item__image img {
  width: 100%;
  cursor: pointer;
}
.work-title {
  font-size: 50px;
  font-weight: bold;
  width: 80%;
  cursor: pointer;
}
.work-subtitle {
  width: 100%;
  font-size: 20px;
  cursor: pointer;
}
// .form {
//   display: flex;
//   flex-direction: column;
//   justify-content: space-around;
//   position: absolute;
//   top: 15%;
//   right: 10%;
//   width: 40%;
//   height: 450px;
//   background-color: white;
//   border-radius: 20px;
//   padding: 40px;
// }
.btn-work {
  width: 100%;
  background: #4762ff;
  border-radius: 10px;
  padding: 16px 21px;
  border: none;
  color: white;
  font-size: 16px;
  margin-top: 30px;
}
.work-item input {
  background: white;
  font-size: 16px;
  background: rgba(71, 98, 255, 0.08);
  border-radius: 10px;
  padding: 16px 20px 16px 21px;
  border: none;
  margin-top: 20px;
  width: 100%;
}
.work-body {
  display: flex;
  justify-content: space-around;
  color: white;
  padding: 20px;
  cursor: pointer;
}
.work-image {
  display: flex;
  gap: 10px;
  padding: 10px;
  cursor: pointer;
}
.work-wrapper__title {
  font-size: 20px;
  padding-bottom: 10px;
  cursor: pointer;
}
.work-wrapper__subtitle {
  padding-bottom: 5px;
  cursor: pointer;
}
.work-truck__set {
  display: flex;
  padding-top: 10px;
}
.work-truck__icon {
  padding-right: 5px;
  cursor: pointer;
}
.work-item__title {
  color: white;
  display: flex;
  padding: 0px 0px 20px 90px;
  cursor: pointer;
}
@media screen and (max-width: 1200px) {
  .work-title {
    font-size: 50px;
    font-weight: bold;
    width: 80%;
    cursor: pointer;
  }
}
@media screen and (max-width: 992px) {
}
@media screen and (max-width: 768px) {
}
@media screen and (max-width: 576px) {
}
</style>
