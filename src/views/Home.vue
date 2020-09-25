<template>
  <div class="ba-about-us">
    <div class="ba-container">
      <div class="ba-about-us__wrapper">
        <h1 class="ba-about-us__title">Про нас</h1>
        <p class="ba-about-us__explanation">Дорогі друзі!</p>
        <p class="ba-about-us__explanation">
          В цей дуже непростий час ми хочемо представити Вам платформу
          «РазомUA», яка створена для підтримки наших медиків в боротьбі з
          COVID-19!
        </p>
        <p class="ba-about-us__explanation">
          Завдяки цьому проекту ми хочемо досягнути справедливості! Кожна
          лікарня має бути забезпечена та почута!
        </p>
        <p class="ba-about-us__explanation">
          Ви зможете напряму допомагати обраній Вами лікарні, ми за прозорість і
          чесність! Неважливо, чи Ви хочете купити одну маску, чи дорогий апарат
          – Ви можете врятувати життя!
        </p>
        <p class="ba-about-us__explanation">
          Лише разом ми подолаємо будь-які кризи та віруси!
        </p>
        <p class="ba-about-us__explanation">
          Платформа організована спільно з Радою Волонтерів Міністерства Оборони
          України, волонтерами з усіх регіонів України за підтримки Офісу
          Президента України та Міністерства Охорони Здоров’я України.
        </p>
        <p class="ba-about-us__explanation">
          Ми зібрали інформацію з офіційних джерел, громадських та волонтерських
          організацій, щоб виявити реальну ситуацію на місцях. Головні задачі
          громадської платформи разом – привернути увагу до поточної ситуації в
          лікарнях та спрямувати зусилля волонтерів та донорів туди, де зараз
          найбільше потрібна допомога.
        </p>
        <p class="ba-about-us__explanation">
          Саме відкритість та прозорість допоможуть разом зробити більше і
          краще!
        </p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: "Home",
};
</script>
<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Fira+Sans:wght@300;400;500;600;700&family=Montserrat:wght@300;400;500;600;700&display=swap");
.ba-about-us {
  &__wrapper {
    max-width: 816px;
    padding-bottom: 161px;
  }
  &__title {
    font-family: Montserrat;
    font-weight: 800;
    font-size: 48px;
    line-height: 64px;
    color: #29b8ff;
    margin: 0;
    padding-top: 64px;
    padding-bottom: 16px;
  }
  &__explanation {
    font-family: "Fira Sans";
    font-weight: 400;
    font-size: 22px;
    line-height: 28px;
    color: #32323e;
    margin: 0;
    padding-bottom: 10px;
  }
}
</style>