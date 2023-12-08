<script>
    import distributed from '$lib/images/distributed.svg';
    import web from '$lib/images/web.svg';
    import mobile from '$lib/images/mobile.svg';
    import design from '$lib/images/design.svg';
</script>

<section class="skills" id="skills">
    <div class="container">
        <h2>Навыки</h2>
        <div class="skills__items">
            <div class="skill">
                <img alt="web" src="{web}">
                <div>
                    <h4>Веб-разработка</h4>
                    <p>Создание веб-приложений с использованием современных технологий,
                        доработка существующих продуктов</p>
                </div>
            </div>
            <div class="skill">
                <img alt="design" src="{design}">
                <div>
                    <h4>Дизайн интерфейса</h4>
                    <p>Отрисовка прототипов и готовых компонентов</p>
                </div>
            </div>
            <div class="skill">
                <img alt="mobile" src="{mobile}">
                <div>
                    <h4>Мобильная разработка</h4>
                    <p>Разработка кроссплатформенных приложений и публикация в маркетах</p>
                </div>
            </div>
            <div class="skill">
                <img alt="distributed" src="{distributed}">
                <div>
                    <h4>Разработка архитектуры распределённых систем</h4>
                    <p>Создание архитектуры компонентов сложных приложений</p>
                </div>
            </div>
        </div>
    </div>
</section>


<style lang="scss">
  .skills {
    padding: 10rem;
    min-height: 100vh;

    &__items {
      & .skill {
        display: flex;
        align-items: center;
        gap: 2rem;

        & h4 {
          font-weight: bold;
        }

        & > div {
          display: flex;
          flex-direction: column;
          gap: 0.5rem;
        }

        & img {
          width: 5rem;
        }
      }

      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2rem;
    }
  }
</style>