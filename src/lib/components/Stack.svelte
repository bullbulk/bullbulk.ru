<script>
    import python from '$lib/images/python.svg';
    import django from '$lib/images/django.svg';
    import flutter from '$lib/images/flutter.svg';
    import rust from '$lib/images/rust.svg';
    import docker from '$lib/images/docker.svg';
    import svelte from '$lib/images/svelte.svg';
</script>

<section class="stack" id="stack">
    <div class="container">
        <h2>Стек технологий</h2>
        <div class="stack__items">
            <div class="stack__item">
                <img alt="Python" src="{python}">
                <div class="description">
                    <h4>Python</h4>
                    <p>Скрипты, веб-приложения, боты</p>
                </div>
            </div>
            <div class="stack__item">
                <img alt="Django" src="{django}">
                <div class="description">
                    <h4>Django</h4>
                    <p>REST API, MPA, интеграция с существующими сервисами</p>
                </div>
            </div>
            <div class="stack__item">
                <img alt="Flutter" src="{flutter}">
                <div class="description">
                    <h4>Flutter</h4>
                    <p>Desktop и мобильные кросплатформенные приложения</p>
                </div>
            </div>
            <div class="stack__item">
                <img alt="Svelte" src="{svelte}">
                <div class="description">
                    <h4>Svelte</h4>
                    <p>SPA, PWA, микросервисы</p>
                </div>
            </div>
            <div class="stack__item">
                <img alt="Docker" src="{docker}">
                <div class="description">
                    <h4>Docker</h4>
                    <p>Создание окружения разработки, дистрибуция продуктов в контейнерах</p>
                </div>
            </div>
            <div class="stack__item">
                <img alt="Rust" src="{rust}">
                <div class="description">
                    <h4>Rust</h4>
                    <p>Модули Python, веб-серверы</p>
                </div>
            </div>
        </div>
    </div>
</section>


<style lang="scss">
  .stack {
    padding: 10rem;
    min-height: 100vh;

    &__items {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 5rem;
    }

    &__item {
      display: flex;
      align-items: center;
      gap: 2rem;

      .description {
        & h4 {
          font-weight: bold;
        }

        display: flex;
        flex-direction: column;
        gap: 0.5rem;
        width: 100%;
      }

      & img {
        width: 5rem;
      }
    }
  }
</style>