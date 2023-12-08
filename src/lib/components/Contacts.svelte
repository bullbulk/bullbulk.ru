<script></script>

<section class="contacts" id="contacts">
    <div class="container">
        <h2>Контакты</h2>
        <table class="contacts__items">
            <tr>
                <td>Почта</td>
                <td>admin@bullbulk.ru</td>
            </tr>
            <tr>
                <td>Telegram</td>
                <td><a href="https://t.me/bulk_bulk" target="_blank">@bulk_bulk</a></td>
            </tr>
            <tr>
                <td>GitHub</td>
                <td><a href="https://github.com/bullbulk" target="_blank">@bullbulk</a></td>
            </tr>
        </table>
        <h3 class="mt-20 mb-5">Свяжитесь со мной</h3>
        <form method="POST">
            <div>
                <input placeholder="Ваше имя" type="text"/>
            </div>
            <div>
                <input placeholder="Ваша почта" type="text"/>
            </div>
            <div>
                <textarea placeholder="Текст сообщения"/>
            </div>
            <div>
                <button>Отправить</button>
            </div>
        </form>
    </div>
</section>


<style lang="scss">
  .contacts {
    padding: 10rem;
    min-height: 100vh;

    & form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      width: 50rem;

      & input, textarea {
        width: 100%;
      }
    }

    &__items {
      width: 50rem;
      font-size: 1.5rem;

      border-collapse: collapse;
      border-style: hidden;


      & td {
        padding: 0.5rem;
        border: 1px white solid;
      }
    }
  }
</style>