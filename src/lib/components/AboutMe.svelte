<script lang="ts">
    import me from '$lib/images/me.svg';
</script>

<section class="about-me" id="about-me">
    <div class="container text-lg">
        <div class="text leading-relaxed">
            <h2>Обо мне</h2>
            <p>
                Меня зовут Юрий Гребенщиков.
            </p>
            <p class="text-2xl"><b>И да, я не умею во фронтенд и дизайн.</b></p>
            <p class="mt-5">Этот сайт является резюме со всей необходимой информацией о моих навыках и проектах.</p>
            <p class="mt-10">Ещё с 14 лет я начал писать первые программы,
                и сразу же понял, что эта деятельность и станет моей основной.</p>
            <p>На текущий момент профессионально занимаюсь разработкой веб-приложений,
                спроектированных с учётом тенденций современного IT.</p>
        </div>
        <div class="p-24">
            <img alt="Me" class="rounded-full" src="{me}">
            <p class="mt-3 text-xs text-center text-gray-400"><i class="fa-solid fa-arrow-up"></i></p>
            <p class="mt-1 text-xs text-center text-gray-400">Это я</p>
        </div>
    </div>
    <button class="absolute text-center left-0 right-0 p-20 bottom-20"
            on:click={function() {
                document.getElementById('about-me')?.scrollIntoView(
                    {behavior: 'smooth', block: 'start', inline: 'nearest'}
                    );
            }}>
        <i class="text-gray-500 text-xl fa-solid fa-arrow-down"></i>
    </button>
</section>


<style lang="scss">
  .about-me {
    padding: 7.5rem 10rem;
    min-height: 100vh;

    & > .container {
      display: grid;
      grid-template-columns: 2fr 1fr;
    }

    & .text p {
      margin-bottom: 1rem;
    }
  }
</style>