<template>
  <div class="mann">
    <div class="container">
      <div class="mann-wrapper">
        <div class="mann-item__wrapper">
          <div class="mann-wrapper__title">Любые услуги за ваши денишки</div>
          <div class="mann-wrapper__subtitle">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc odio
            in et, lectus sit lorem id integer.
          </div>
        </div>

        <div class="mann-wrapper__block">
          <div class="mann-item">
            <div class="mann-block__item">
              <div class="mann-item__title">
                Б/у запчасти для грузовых авто из Европы
              </div>
              <div class="mann-item__subtitle">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc
                odio in et, lectus sit lorem id intege
              </div>
            </div>
            <div class="mann-item__image">
              <img src="@/assets/img/moyka.svg" alt="" />
            </div>
          </div>

          <div class="mann-item">
            <div class="mann-block__item">
              <div class="mann-item__title">
                Автомойка грузовых и легковых авто
              </div>
              <div class="mann-item__subtitle">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc
                odio in et, lectus sit lorem id intege
              </div>
            </div>
            <div class="mann-item__image">
              <img src="@/assets/img/moyka.svg" alt="" />
            </div>
          </div>

          <div class="mann-item">
            <div class="mann-block__item">
              <div class="mann-item__title">Магазин аксессуаров</div>
              <div class="mann-item__subtitle">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc
                odio in et, lectus sit lorem id intege
              </div>
            </div>
            <div class="mann-item__image">
              <img src="@/assets/img/zapchast.svg" alt="" />
            </div>
          </div>

          <div class="mann-item">
            <div class="mann-block__item">
              <div class="mann-item__title">
                Пункт замены масла легковых авто
              </div>
              <div class="mann-item__subtitle">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc
                odio in et, lectus sit lorem id intege
              </div>
            </div>
            <div class="mann-item__image">
              <img src="@/assets/img/zapchast.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Mann",
};
</script>

<style lang="scss" scoped>
.mann {
  padding: 50px 0px;
}
.mann-wrapper {
  display: flex;
  flex-direction: column;
}
.mann-wrapper__title {
  font-size: 40px;
  font-weight: 900;
  text-align: center;
  padding-bottom: 20px;
}
.mann-item__wrapper {
  padding-bottom: 40px;
  cursor: pointer;
}
.mann-wrapper__block {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 25px;
}
.mann-item {
  display: flex;
  background: #f4f6fa;
  border-radius: 10px;
  padding: 30px 0px 30px 30px;
}
.mann-block__item {
  flex: 1;
}
.mann-item__title {
  font-size: 25px;
  font-weight: 900;
  cursor: pointer;
}
.mann-item__subtitle {
  font-size: 15px;
}
.mann-wrapper__subtitle {
  text-align: center;
}
.mann-item__image {
  width: 50%;
  cursor: pointer;
  img {
    width: 100%;
    height: 100%;
    object-fit: contain;
  }
}
@media screen and (max-width: 1200px) {
}
@media screen and (max-width: 992px) {
  .mann-wrapper__title {
    font-size: 30px;
  }
  .mann-wrapper__subtitle {
    font-size: 15px;
  }
  .mann-item__image {
    width: 60%;
    cursor: pointer;
    img {
      width: 100%;
      height: 100%;
      object-fit: contain;
    }
  }
  .mann-item__title {
    font-size: 18px;
  }
  .mann-item__subtitle {
    font-size: 10px;
  }
  .mann-item {
    padding: 20px 0px 20px 20px;
  }
}
@media screen and (max-width: 768px) {
  .mann-wrapper__title {
    font-size: 25px;
  }
  .mann-wrapper__subtitle {
    font-size: 12px;
  }
  .mann-item__image {
    width: 60%;
    cursor: pointer;
    img {
      width: 100%;
      height: 100%;
      object-fit: contain;
    }
  }
  .mann-item__title {
    font-size: 15px;
  }
  .mann-item__subtitle {
    font-size: 8px;
  }
  .mann-item {
    padding: 15px 0px 15px 15px;
  }
}
@media screen and (max-width: 576px) {
  .mann-wrapper__title {
    font-size: 22px;
  }
  .mann-wrapper__subtitle {
    font-size: 12px;
  }
  .mann-item__image {
    width: 60%;
    cursor: pointer;
    img {
      width: 100%;
      height: 100%;
      object-fit: contain;
    }
  }
  .mann-item__title {
    font-size: 15px;
  }
  .mann-item__subtitle {
    font-size: 12px;
  }
  .mann-item {
    padding: 15px 0px 15px 15px;
  }
  .mann-wrapper__block {
    display: flex;
    flex-direction: column;
  }
}
</style>
