<script>
    import formula_hd from '$lib/images/formula_hd.svg';
    import rusal from '$lib/images/rusal.svg';
    import forum2035 from '$lib/images/forum2035.svg';
</script>

<section class="portfolio" id="portfolio">
    <div class="container">
        <h2>Портфолио</h2>
        <ul class="portfolio__items">
            <li>
                <div class="inner">
                    <div class="logo">
                        <img alt="Формула Хороших Дел" src="{formula_hd}"/>
                    </div>
                    <div class="description">
                        <p class="title">
                            Платформа обработки данных проекта ПАО «СИБУР Холдинг» «Формула Хороших Дел»
                        </p>
                        <p>
                            Реализация платформы сбора и обработки заявок проекта социальных инвестиций.
                            Сбор заявок и их обработка, нотификация заявителей, сбор отчётности, база данных волонтёров.
                        </p>
                        <p class="stack">
                            MPA, Django.
                        </p>
                        <b>
                            <a href="https://contest.formula-hd.ru/" target="_blank">
                                Перейти на сайт
                            </a>
                            <i class="fa-solid fa-external-link"></i>
                        </b>
                    </div>
                </div>
            </li>
            <li>
                <div class="inner">
                    <div class="logo">
                        <img alt="РУСАЛ" src="{rusal}"/>
                    </div>
                    <div class="description">
                        <p class="title">
                            Раздел "Устойчивое развитие" сайта ПАО «Русский алюминий»
                        </p>
                        <p>
                            Переработка существующего раздела с новым дизайном и данными.
                        </p>
                        <p>
                            (Ожидается в январе 2024)
                        </p>
                        <p class="stack">
                            PHP, Bitrix.
                        </p>
                        <b>
                            <a href="https://rusal.ru/sustainability/" target="_blank">
                                Перейти на сайт
                            </a>
                            <i class="fa-solid fa-external-link"></i>
                        </b>
                    </div>
                </div>
            </li>
            <li>
                <div class="inner">
                    <div class="logo">
                        <img alt="Форум 2035" src="{forum2035}"/>
                    </div>
                    <div class="description">
                        <p class="title">
                            Лендинг Форума «Стратегия 2035. Роль бизнеса в устойчивом будущем Сибири»
                        </p>
                        <p>
                            Создание лендинга с данными о программе форума.
                        </p>
                        <p class="stack">
                            HTML, CSS, Bootstrap
                        </p>
                        <b>
                            <a href="https://forum2035.ru/" target="_blank">
                                Перейти на сайт
                            </a>
                            <i class="fa-solid fa-external-link"></i>
                        </b>
                    </div>
                </div>
            </li>

            <li>
                <div class="inner">
                    <div class="logo">
                        <img alt="Формула Хороших Дел" src="{formula_hd}"/>
                    </div>
                    <div class="description">
                        <p class="title">
                            Мобильное приложение проекта ПАО «СИБУР Холдинг» «Формула Хороших Дел»
                        </p>
                        <p>
                            Разработка и публикация приложения для Android и iOS. Новости, билеты, записи на
                            мероприятия, опросы и прочее.
                        </p>
                        <p class="stack">
                            Flutter, Django, DRF.
                        </p>
                        <div class="flex gap-5">
                            <b>
                                <a href="https://play.google.com/store/apps/details?id=com.siburhd.android"
                                   target="_blank">
                                    Google Play
                                </a>
                                <i class="fa-solid fa-external-link"></i>
                            </b>
                            <b>
                                <a href="https://apps.apple.com/ru/app/%D1%84%D0%BE%D1%80%D0%BC%D1%83%D0%BB%D0%B0-hd/id6449192676"
                                   target="_blank">
                                    App Store
                                </a>
                                <i class="fa-solid fa-external-link"></i>
                            </b>
                        </div>
                    </div>
                </div>
            </li>
        </ul>
    </div>
</section>


<style lang="scss">
  .portfolio {
    padding: 7.5rem 10rem;
    min-height: 100vh;

    &__items {
      display: flex;
      flex-direction: column;
      row-gap: 2.5rem;

      & li {
        &:not(:last-child) {
          padding-bottom: 2.5rem;
          border-bottom: 2px white solid;
        }

        & .inner {
          display: grid;
          align-items: center;
          grid-template-columns: 1fr 5fr;
          gap: 5rem;

          & .logo {
            border-radius: 50%;
            background-color: white;
            padding: 1rem;
            width: 10rem;
            height: 10rem;

            & img {
              width: 100%;
              height: 100%;
            }
          }

          & .title {
            font-weight: bold;
            font-size: 1.5rem;
          }

          & .description {
            & p {
              margin-bottom: 1rem;
            }

            & .stack {
              font-size: 1.25rem;
            }
          }
        }
      }
    }
  }
</style>