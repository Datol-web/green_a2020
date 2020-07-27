<template>
<div class="landing">

    <div class="header">
      <div class="container">
        <div class="header-nav">

          <div class="container header-nav-container">
            <div class="header-nav__logo">
              <img src="~@/assets/img/ege-logo.png" alt="">
              <img src="~@/assets/img/2020-logo.png" alt="">
            </div>
            <div class="header-nav__social">
              <a href="#"><div class="header-nav__social-f"></div></a>
              <a href="#"><div class="header-nav__social-t"></div></a>
              <a href="#"><div class="header-nav__social-vk"></div></a>
            </div>
          </div>

        </div>

        <div class="header-barrels">
          <div class="title_eg">Всё</div>
          <img class="" src="~@/assets/img/earth-logo.png" alt="">
          <div class="title_eg">ЕГЭ</div>
        </div>

      </div>
    </div>

    <div class="container section1">

      <div class="section1-nav">
          <div class="container header-nav-container">
          <ul>
            <li onclick="animateScrollTo(document.querySelector('.section1'), {verticalOffset: -150,})">Что такое ЕГЭ</li>
            <li onclick="animateScrollTo(document.querySelector('.section2'), {verticalOffset: -150,})">Как запомнить материал</li>
            <li onclick="animateScrollTo(document.querySelector('.section3'), {verticalOffset: -150,})">Часто сдаваемые предметы</li>
            <li onclick="animateScrollTo(document.querySelector('.section4'), {verticalOffset: -150,})">Как проходит экзамен</li>
            <li onclick="animateScrollTo(document.querySelector('.section7'), {verticalOffset: -150,})">Где узнать результаты</li>
            <li onclick="animateScrollTo(document.querySelector('.section8'), {verticalOffset: -150,})">Пробные тесты</li>
          </ul>
        </div>
      </div>

      <div class="section-content">
        <div class="section-content-info">
          <h2 class="section-content__title-ege">Что такое «ЕГЭ»?</h2>
          <div class="section-content__text">
            Единый государственный экзамен (ЕГЭ) — это форма государственной итоговой аттестации по образовательным программам среднего общего образования (ГИА).
          </div>
          <div class="section-content__text-gray">
            При проведении ЕГЭ используются контрольные измерительные материалы (КИМ), представляющие собой комплексы заданий стандартизированной формы, а также специальные бланки для оформления ответов на задания. ЕГЭ проводится письменно на русском языке (за исключением ЕГЭ по иностранным языкам). Для проведения ЕГЭ на территории Российской Федерации и за ее пределами предусматривается единое расписание экзаменов.

          </div>
          <div class="section-content__text-gray">
            В России 3 июля стартовала сдача ЕГЭ, перенесённых из-за коронавируса. Единые госэкзамены 2020 года запомнятся бывшим одиннадцатиклассникам не только волнением, а ещё и сильной жарой и мерами профилактики COVID-19. В соцсетях молодые люди рассказывают, как справились с заданиями, описывают процедуры перед написанием, и, конечно же, шутят — а что ещё им остаётся делать, пока не пришли результаты.
          </div>
        </div>
        
        <img class="section-content__text-img" src="~@/assets/img/img-sec1.jpg" alt="">
        <div class="section-content-info">
          <div class="section-content__quote">
          
            Сайты для подготовки к сдаче экзаменов дистанционно, быстро стали востребованы по всему миру.
            В 2000-е годы такие сайты были бы одними из немногих, где была бы практически вся информация по любой из дисциплин.
             
            <span>Сергей Зарубин в <a href="#">интервью</a> для «Знания.ру»</span>
          </div>
        </div>


      </div>
    </div>


    <div class="container section2">

      <div class="section-content">

        <div class="section-content-info">
          <h2 class="section-content__title">Как быстро запомнить материал?</h2>
        </div>

        <img class="section-content__text-img" src="@/assets/img/img-sec2.jpg" alt="">

        <div class="section-content-info">
          <div class="section-content__text-gray">
          Есть ли метод, с помощью которого можно быстро запомнить материал?
          </div>
          <div class="section-content__text-gray">
          – Да, он называется «метод ключевых слов». Его суть заключается в том, что ключевое слово в тексте связывает хранящуюся в памяти информацию с сознанием и позволяет с легкостью ее воспроизвести в нужный момент. Так, для запоминания какой-либо фразы достаточно выделить одно-два главных слова и запомнить их, строя ассоциации с остальными словами. В дальнейшем стоит только вспомнить «ключевики», и фраза сразу вспомнится целиком.
          </div>
          <div class="section-content__text-gray">
            Этот метод можно применить при запоминании материала практически по любому предмету. Ученик должен прочитать текст, составить цепочку ключевых слов, следующих друг за другом и связанных между собой, а потом повторить несколько раз. Человеческий мозг запоминает ту информацию, которую постоянно использует, а также которая ему приятна и интересна – так что интересуйтесь предметом, стройте живые ассоциации!
          </div>
        </div>

      <img class="section-content__text-img" src="@/assets/img/img-sec3.jpg" alt="">

      <div class="section-content-info">
        <div class="section-content__quote">
         Эмоции и чувства – наши союзники, они помогают нам запомнить даже абстрактные цифры и формулы.

         <span>Школьный психолог о подготовке к ЕГЭ  для «Знания.ру»</span>
        </div>
      </div>

      </div>

    </div>

    <div class="container section3">
      <div class="section-content">
        <div class="section-content-info">
          <h2 class="section-content__title">Самые часто сдаваемые предметы в «России»</h2>
              <img class="section-content__text-img" src="@/assets/img/img-sec3_1.jpg" alt="">
          <div class="list-block">

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/1.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Обществознание — 315 000 человек.</div>
              </div>
              <div class="list-block__item-info__text">
                Средний балл по данному предмету составил 55.9.
               </div>
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/2.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Физика — 139 000 человек.</div>
              </div>
              <div class="list-block__item-info__text">
                Средний балл по данному предмету составил 54.4.
              </div>
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/3.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Биология — 124 000 человек.</div>
              </div>
              <div class="list-block__item-info__text">
               Средний балл по данному предмету составил 52.2.
              </div>
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/44.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">История — 103 000 человек.</div>
              </div>
              <div class="list-block__item-info__text">
                Средний балл по данному предмету составил 55.3.
              </div>
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/55.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Химия — 89 000 человек.</div>
              </div>
              <div class="list-block__item-info__text">
                Средний балл по данному предмету составил 56.7.
              </div>
            </div>

              <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/66.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Информатика — 75 000 человек.</div>
              </div>
              <div class="list-block__item-info__text">
                Средний балл по данному предмету составил 62.4.
              </div>
            </div>
            

          </div>

          <div class="section-content__text-gray">
          Давно прошли те времена, когда за экзамен получали отметки «отлично», «хорошо», «удовлетворительно». Уже более десяти лет единый государственный экзамен – обязательная форма тестирования выпускников, в которой не предполагается оценки по пятибалльной шкале.
          
          Теперь она складывается из подсчета баллов, сумма которых определяется заранее конкретизированными критериями. Кроме того, они пересчитываются во вторичной системе: максимум здесь составляет 100.

           Итог такого единого для каждого ученика теста зависит от качества знаний и общей подготовки, куда входят усидчивость, внимательность, умение сопоставлять факты и рассуждать о них системно, логическое мышление и т.п.
          </div>

        </div>
      </div>
    </div>

    <div class="container section4">

      <div class="section-content">

        <div class="section-content-info">
          <h2 class="section-content__title">Как проходит экзамен?</h2>
        </div>
        <img class="section-content__text-img" src="@/assets/img/img-sec4.jpg" alt="">

        <div class="section-content-info">
          <div class="list-block">

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/time.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Время</div>
              </div>
              <div class="list-block__item-info__text">
                Время начала ЕГЭ по всем учебным предметам 10.00 часов по местному времени.
                Допуск участников ЕГЭ в ППЭ осуществляется с 09.00 по местному времени.
              </div>
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/regulations.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Правила</div>
              </div>
              <div class="list-block__item-info__text">
                Участники ЕГЭ не должны опаздывать на экзамен, так как для таких участников экзамена продолжительность проведения экзамена не продлевается и общий инструктаж, в том числе по заполнению регистрационных полей бланков ЕГЭ, не проводится.
              </div>
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/documents.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Документы</div>
              </div>
              <div class="list-block__item-info__text">
                При входе в ППЭ участник ЕГЭ должен предъявить документ, удостоверяющий личность.
                В случае отсутствия по объективным причинам у обучающегося паспорта он допускается в ППЭ только после письменного подтверждения его личности сопровождающим от школы.
                В случае отсутствия паспорта у выпускника прошлых лет и других категорий участников ЕГЭ в ППЭ такие участники ЕГЭ не допускаются.
              </div>
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/accessories.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Принадлежности</div>
              </div>
              <div class="list-block__item-info__text">
               В ППЭ участник ЕГЭ берет с собой:<br>
               ручка; <br>
               паспорт; <br>
               лекарства и питание (при необходимости); <br>
               средства обучения и воспитания (по математике линейка; по физике – линейка и непрограммируемый калькулятор;<br>
               по химии – непрограммируемый калькулятор;<br> 
               по географии – линейка, транспортир, непрограммируемый калькулятор);<br> 
               участники ЕГЭ с ОВЗ, дети – инвалиды и инвалиды - специальные технические средства. 
              </div>
            </div>

          </div>

          <div class="section-content__notice">
            Далее проводится инструктаж по заполнению регистрационных бланков ЕГЭ, после чего участники приступают к выполнению заданий.
          </div>
        </div>

      </div>

    </div>

    <div class="container section7">

      <div class="section-content">

        <div class="section-content-info">
          <div class="section-content__title">Где узнать результаты?</div>
        </div>
        <div class="section-content__text-gray">
         В регионах участники ЕГЭ о своих результатах должны быть проинформированы не позднее 3 рабочих дней после объявления Рособрнадзором минимального количества баллов. На обработку результатов ЕГЭ по русскому языку и математике отводится 6 календарных дней после проведения испытания.<br>Результаты размещаются на <a href="http://check.ege.edu.ru/">официальном на сайте.</a>
         </div>
        <img class="section-content__text-img__game" src="@/assets/img/pass.jpg" alt="">
        <div class="section-content-info">
        Для того чтобы узнать результаты может потребоваться следующая информация:
          <div class="section-content__text-gray">
         
          </div>
      
          <div class="list-block">

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/1.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Код регистрации, полученный при регистрации на ЕГЭ (указан в пропуске на ЕГЭ);</div>
              </div>
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/2.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Фамилия Имя Отчество;</div>
              </div>              
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/3.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Серия и номер паспорта;</div>
              </div>          
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/44.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Номер другого документа, удостоверяющего личность, предъявленного при оформлении допуска к ЕГЭ;</div>
              </div>          
            </div>

            <div class="list-block__item">
              <div class="list-block__item-info">
                <img src="@/assets/img/55.png" alt="" class="wow animate__fadeInLeft" data-wow-duration="1s"  data-wow-offset="50" data-wow-iteration="1">
                <div class="list-block__item-info__title">Номер СНИЛС.</div>
              </div>          
            </div>
          </div>

        </div>

      </div>
      
    </div>

    <div class="container section8">

      <div class="section-content">
      <div class="section-content-info">
      <div class="section-content__title">Где пройти пробные тесты?</div>
      <div class="section-content__text-gray">
          Существует множество сайтов для подготовки к ЕГЭ, но мы рекомендуем следующий...
          </div>
          </div>

        <button class="section-content__btn"><a href= "http://os.fipi.ru/home/1" target="_blank"> «Перейти к пробному тестированию»</a></button>
      </div>
    </div>

    <div class="footer">
      <p class="footer-text">© 2020 Greenatom</p>
    </div>
  </div>
</template>

<script>

export default {
  watch: {
  },
  methods: {
  },
  create(){
    this.animateScrollTo();
  },
  mounted() {
  },
}
</script>


<style lang="scss" type="text/scss">

</style>

