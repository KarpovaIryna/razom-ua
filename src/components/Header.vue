<template>
  <header class="ba-header">
    <div class="ba-container">
      <div class="ba-header__wrapper">
        <a href="#" class="ba-logo"
          ><img src="../img/Full.svg" alt="++Razom" />
          За підтримки Фонду Соціальної Справедливості
        </a>
        <nav class="ba-nav">
          <ul class="ba-nav__list">
            <li class="ba-nav__item">
              <router-link to="/vikonano" class="ba-nav__done">
                <img src="../img/done.svg" alt="done" />
                Виконано
              </router-link>
            </li>
            <li class="ba-nav__item">
              <router-link to="/" class="ba-nav__about-us">
                <img src="../img/about-us.svg" alt="about-us" />
                Про нас
              </router-link>
            </li>
          </ul>
          <a href="https://razomukraine.com/donate/" class="ba-nav__help"
            >Допомогти</a
          >
        </nav>
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
    width: fit-content;
   //  @media screen and (min-width: 640px) {
   //    font-size: 12px;
   //    line-height: 16px;
   //  }
  }
}
.ba-nav {
  display: flex;
  width: 100%;
  align-items: center;
  justify-content: space-between;
  padding-top: 25px;
  @media screen and (min-width: 640px) {
    flex-direction: row;
    width: 50%;
    padding-top: 0;
  }
  @media screen and (min-width: 1024px) {
    flex-direction: row;
    width: 65%;
  }
  &__list {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    @media screen and (min-width: 1024px) {
      flex-direction: row;
    }
  }
  &__item{
padding-bottom: 15px;
margin: auto 0;
&:last-child{
	padding-bottom: 0;
}
	@media screen and (min-width: 1024px) {
		padding-right: 40px;
		padding-bottom: 0;
    &:last-child{
	padding-right: 0;
}
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
  &__help {
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

</style>