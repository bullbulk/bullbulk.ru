<section class="education" id="education">
    <div class="container">
        <h2>Образование</h2>
        <ul class="education__items">
            <li>
                <div class="inner">
                    <div class="date">2015-2020</div>
                    <div>
                        МБОУ "Лицей" г. Нижневартовска с углубленным изучением математики и физики
                    </div>
                </div>
            </li>
            <li>
                <div class="inner">
                    <div class="date">2019-2021</div>
                    <div>
                        Очный курс Яндекс Лицей "Основы программирования на языке Python" и "Основы промышленного
                        программирования"
                    </div>
                    <b>
                        <a href="https://lms.yandex.ru/certificate/check/?certNumber=210236859&lastName=%D0%93%D1%80%D0%B5%D0%B1%D0%B5%D0%BD%D1%89%D0%B8%D0%BA%D0%BE%D0%B2">
                            Сертификат
                        </a>
                    </b>
                </div>
            </li>
            <li>
                <div class="inner">
                    <div class="date">2020-2024</div>
                    <div>
                        Нижневартовский социально-гуманитарный колледж, квалификация "Разработчик веб и мультимедийных
                        приложений"
                    </div>
                </div>
            </li>
            <li>
                <div class="inner">
                    <div class="date">2024-...</div>
                </div>
            </li>
        </ul>
    </div>
</section>


<style lang="scss">
  .education {
    padding: 7.5rem 10rem;
    min-height: 100vh;

    &__items {
      display: flex;
      flex-direction: column;
      gap: 2rem;
      border-left-width: 2px;
      border-left-style: solid;
      border-image: linear-gradient(to bottom, white 80%, rgba(0, 0, 0, 0) 100%) 1 100%;
      padding-bottom: 4rem;

      & li {
        position: relative;

        &:before {
          content: "";
          position: absolute;
          width: 2rem;
          top: 2rem;
          height: 2px;
          display: block;
          background: white;
        }

        & .inner {
          padding-left: 4rem;

          & .date {
            font-weight: bold;
            font-size: 1.5rem;
            margin-bottom: 0.5rem;
          }
        }
      }
    }
  }
</style>