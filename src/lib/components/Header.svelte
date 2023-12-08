<script>
    import github from '$lib/images/github.svg';
    import telegram from '$lib/images/telegram.svg';
</script>

<header class="p-6">

    <nav class="w-100 px-10">
        <ul class="flex gap-10">
            <li><a href="#intro">Начало</a></li>
            <li><a href="#about-me">Обо мне</a></li>
            <li><a href="#skills">Навыки</a></li>
            <li><a href="#stack">Стек</a></li>
            <li><a href="#education">Образование</a></li>
            <li><a href="#portfolio">Портфолио</a></li>
            <li><a href="#contacts">Контакты</a></li>
        </ul>
    </nav>

    <div class="socials">
        <div class="socials__inner">
            <div class="socials__item">
                <a href="https://github.com/bullbulk" target="_blank">
                    <img alt="GitHub" src="{github}">
                </a>
            </div>
            <div class="socials__item">
                <a href="https://t.me/bulk_bulk" target="_blank">
                    <img alt="Telegram" src="{telegram}">
                </a>
            </div>
        </div>
    </div>
</header>

<style lang="scss">
  header {
    position: fixed;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    width: 100%;
    background-color: var(--background);
    height: var(--header-height);
    z-index: 10;
  }

  .socials__inner {
    @apply px-12 flex gap-5 items-center;
    justify-content: flex-end;

    & img {
      width: 2rem;
    }
  }
</style>
