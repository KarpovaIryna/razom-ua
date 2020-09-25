<template>
  <header class="ba-header">
    <div class="ba-container">
      <div class="ba-header__wrapper">
        <a href="#" class="ba-logo"
          ><img src="../img/Full.svg" alt="++Razom" />
          За підтримки Фонду Соціальної Справедливості
        </a>
        <nav class="ba-header__nav">
          <router-link to="/vikonano" class="ba-header__done">
            <img src="../img/done.svg" alt="done" />
            Виконано
          </router-link>
          <router-link to="/" class="ba-header__about-us">
            <img src="../img/about-us.svg" alt="about-us" />
           Про нас
          </router-link>
        </nav>
        <a href="#" class="ba-header__marathon">Марафон “Ти не один”</a>
      </div>
    </div>
    <!-- /.ba-container -->
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Fira+Sans:wght@300;400;500;600;700&family=Montserrat:wght@300;400;500;600;700&display=swap");
.ba-header {
  &__wrapper {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    @media screen and (min-width: 640px) {
      flex-direction: row;
    }
  }
  &__nav {
    display: flex;
    width: 35%;
    flex-direction: column;
    @media screen and (min-width: 640px) {
      flex-direction: row;
    }
  }
  &__done {
    font-family: "Fira Sans";
    font-weight: 400;
    font-size: 18px;
    line-height: 32px;
    color: #32323e;
    text-decoration: none;
    margin: auto;
    &:hover,
    &:active {
      text-decoration: underline;
    }
  }
  &__about-us {
    font-family: "Fira Sans";
    font-weight: 400;
    font-size: 18px;
    line-height: 32px;
    color: #32323e;
    text-decoration: none;
    margin: auto;
    &:hover,
    &:active {
      text-decoration: underline;
    }
  }
  &__marathon {
    font-family: Montserrat;
    font-weight: 600;
    font-size: 18px;
    line-height: 16px;
    color: #ffffff;
    align-self: center;
    background: #e44185;
    border: 1px solid #e44185;
    border-radius: 4px;
    padding: 16px;
    text-decoration: none;
    &:hover,
    &:active {
      background: transparent;
      color: #e44185;
      translate: 0.3s;
    }
  }
}
.ba-logo {
  font-family: "Fira Sans";
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 16px;
  color: #32323e;
  text-decoration: none;
  display: flex;
  flex-direction: column;
}
</style>