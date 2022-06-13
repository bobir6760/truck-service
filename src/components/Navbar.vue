<template>
  <div class="navbar">
    <div class="container">
      <div class="navbar-wrapper">
        <div class="navbar-body__wrapper">
          <div class="navbar-wrapper__address">
            <div class="navbar-address">
              <div class="navbar-wrapper__icon">
                <img src="@/assets/img/Vector.svg" alt="" />
              </div>
              <div class="navbar-title">
                <h5>Наш адрес:</h5>
                <h5>г.Бишкек,ул.Ляляля 69</h5>
              </div>
            </div>
            <div class="navbar-wrapper__work">
              <div class="navbar-wrapper__icon">
                <img src="@/assets/img/clock.svg" alt="" />
              </div>
              <div class="navbar-work__title">
                <h5>График работы:</h5>
                <h5>с 8:00 до 22:00 без выходных</h5>
              </div>
            </div>
          </div>

          <div class="navbar-wrapper__number">
            <div class="navbar__icon">
              <img src="@/assets/img/call.svg" alt="" />
            </div>
            <div class="navbar-number__title">
              <div class="number__title">+7(708)51 51 518</div>
              <div class="number__title">+7(700)51 51 518</div>
            </div>
          </div>
        </div>
        <div class="navbar-card__wrapper">
          <div class="navbar-item__image">
            <img src="@/assets/img/EURO.png" alt="" />
          </div>
          <div class="navbar-body">
            <div class="navbar-item__title">Ето мы</div>
            <div class="navbar-item__title">Почему мы</div>
            <div class="navbar-item__title">А вот поетому</div>
            <div class="navbar-item__title">Контакты</div>
          </div>
          <button class="navbar-btn">Заказать звонок</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style lang="scss" scoped>
.navbar {
  padding: 50px 0px;
}
.navbar-wrapper {
  display: flex;
  flex-direction: column;
}
.navbar-body__wrapper {
  display: flex;
  justify-content: space-between;
}
.navbar-wrapper__address {
  display: flex;
  gap: 40px;
  cursor: pointer;
}
.navbar-card__wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.navbar-wrapper__work {
  display: flex;
  gap: 10px;
  align-items: center;
  cursor: pointer;
}
.navbar-wrapper__number {
  display: flex;
  gap: 10px;
  align-items: center;
  cursor: pointer;
}
.navbar-address {
  display: flex;
  gap: 10px;
  align-items: center;
}

.navbar-header {
  display: flex;
  justify-content: flex-start;
  gap: 10px;
}
.navbar-number {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}
.navbar-item__image {
  img {
    width: 100%;
    height: 100%;
    object-fit: contain;
    cursor: pointer;
  }
}
.navbar-body {
  display: flex;
  font-weight: bold;
  gap: 30px;
  cursor: pointer;
}
.navbar-btn {
  background: #4762ff;
  border-radius: 15px;
  padding: 15px;
  border: none;
  color: white;
  font-size: 20px;
  cursor: pointer;
}
.navbar-btn:hover {
  transition: 0.5s;
  background: black;
  border-radius: 5px;
}
@media screen and (max-width: 1200px) {
  .navbar-body {
    gap: 30px;
  }
}
.navbar-item {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
  padding-top: 00px;
}
.navbar-wrapper {
  display: flex;
  justify-content: center;
  gap: 30px;
}
@media screen and (max-width: 992px) {
  .navbar-body {
    gap: 20px;
  }
  .navbar-item__title {
    font-size: 12px;
  }
  .navbar-btn {
    padding: 12px;
    font-size: 12px;
  }
  .navbar-item__image {
    img {
      width: 70%;
      height: 70%;
    }
  }
  .navbar-number__title {
    font-size: 15px;
  }
}
@media screen and (max-width: 768px) {
  .navbar-number__title {
    font-size: 12px;
  }
  .navbar-btn {
    padding: 7px 10px;
    font-size: 12px;
  }
  .navbar-item__title {
    font-size: 10px;
  }
  .navbar-body {
    gap: 10px;
  }
  .navbar-item__image {
    img {
      width: 60%;
      height: 60%;
    }
  }
}
@media screen and (max-width: 576px) {
  .navbar-body__wrapper {
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  .navbar-wrapper__address {
    flex-direction: column;
    gap: 20px;
    align-items: center;
  }
  .navbar-card__wrapper {
    flex-direction: column;
    gap: 20px;
    align-items: center;
  }
  .navbar-item__image {
    text-align: center;
  }
  .navbar-item__title {
    font-size: 12px;
  }
  .navbar-wrapper__number {
    display: flex;
    justify-content: center;
    font-weight: bold;
  }
}
</style>
