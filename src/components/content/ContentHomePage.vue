<template>
  <div class="content">
    <section class="section content_section">
      <h2 class="content_title">{{ title }}</h2>
      <p class="content_text">
        Физиотерапия – прекрасное дополнение, а в некоторых случаях основной
        метод лечения различных заболеваний. Физиотерапевтические воздействия
        безболезненны, имеют минимум побочных эффектов и незначительное число
        противопоказаний, совместимы с лекарственной терапией, незаменимы в
        период восстановления после болезни, для профилактики обострений
        заболеваний, для укрепления организма. Массаж в свою очередь является
        превосходным средством для профилактики многих проблем, их лечения в
        комплексе с другими назначениями. Данная процедура имеет много
        разновидностей, но, если говорить о физиотерапевтическом воздействии на
        тело – в основном используется классический метод. Он заключается в том,
        что специалист сначала мягкими движениями рук разминает ткани тела
        пациента, затем более серьезными усилиями проводит саму процедуру, и
        снова повторяет мягкую разминку. Кабинет физиотерапии оснащен
        современной физиотерапевтической аппаратурой последнего поколения,
        позволяющей применять следующие методы лечения:
      </p>
      <div class="content_list_block">
        <ul class="content_list">
          <li class="content_list_item">
            Гальванизация и лекарственный электрофорез
          </li>
          <li class="content_list_item">Электростимуляция</li>
          <li class="content_list_item">
            Транскраниальная электроанальгезия (аналог электросна)
          </li>
          <li class="content_list_item">Магнитотерапия</li>
          <li class="content_list_item">
            Лечение лазером при заболеваниях лор – органов
          </li>
          <li class="content_list_item">УВЧ терапия</li>
          <li class="content_list_item">Амплипульстерапия, амплипульсфорез</li>
          <li class="content_list_item">Диадинамотерапия</li>
          <li class="content_list_item">Магнитолазерная терапия</li>
          <li class="content_list_item">Ингаляционная терапия</li>
        </ul>
      </div>
    </section>
  </div>
</template>
<script>
export default {
  name: 'ContentHomePage',
  props: {},
  data() {
    return {
      title: 'Кабинет физиотерапии ',
      text: 'Массаж в свою ',
    };
  },
};
</script>
<style>
.content_list_block {
  width: 1300px;
  margin-left: auto;
  margin-right: auto;
}
.content_text {
  max-width: 1300px;
  margin-left: auto;
  margin-right: auto;
  font-size: 18px;
  line-height: 1.6;
  word-wrap: break-word;
}
.content_list {
  display: grid;
  grid-template-columns: 1fr 1fr;
  justify-content: start;
  padding-left: 0;
}
.content_list_item {
  margin-right: auto;
  font-size: 18px;
  font-weight: bold;
  line-height: 1.6;
}
.content_section {
  box-shadow: inset 0 -3em 3em rgba(0, 0, 0, 0.1), 0 0 0 2px rgb(255, 255, 255),
    0.3em 0.3em 1em rgba(0, 0, 0, 0.3);
  border-radius: 7px;
}
</style>
