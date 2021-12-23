<template>
  <section class="registration">
    <div class="container-page">
      <div class="registration__inner">
        <h1 class="registration__title">Регистрация</h1>
        <div class="registration__text">
          Для того, чтобы стать полноправным участником Wikiplace, заполните
          поля нижею. Ваш пароль придет на указанную электронную почту.
        </div>
        <form
          action=""
          class="registration__form form"
          @submit.prevent="formSubmit"
        >
          <div class="form-group">
            <input
              id="login"
              class="form-control"
              placeholder="Придумайте логин"
            />
            <!-- <p>
              Обязательное поле
            </p>
            <p>
              Здесь должно быть больше 5-и символов
            </p> -->
          </div>
          <div class="form-group">
            <input
              id="email"
              type="email"
              class="form-control"
              placeholder="Email"
            />
            <!-- <p>
              Обязательное поле
            </p>
            <p>
              Email неккоректный
            </p> -->
          </div>
          <div class="form-group">
            <input id="password" type="password" class="form-control" />
            <!-- <p>
              Обязательное поле
            </p> -->
          </div>
          <div class="form-group">
            <select id="country" class="form-control">
              <option>Ваш город </option>
            </select>
          </div>

          <div class="form-group form-check">
            <input
              type="checkbox"
              class="form-check-input"
              id="notification"
              v-model="form.agreeWithSendEmail"
            />
            <label class="form-check-label" for="notification"
              >Уведомлять меня о новых курсах</label
            >
          </div>
          <div class="form__btn">
            <button type="submit" class="btn main-btn">Сохранить</button>
          </div>
        </form>
        {{ weather.main }}
      </div>
    </div>
  </section>
</template>
<script>
export default {
  data() {
    return {
      form: {
        login: "",
        email: "",
        password: "",
        agreeWithSendEmail: false
      },
      weather: ""
    };
  },
  methods: {
    formSubmit() {
      this.signIn();
      // signUp();
    },

    signIn() {
      fetch(
        "http://api.openweathermap.org/data/2.5/weather?q=Kiev&appid=978fdae46b741b21b0bf489fa70c6570"
      )
        .then(function(resp) {
          return resp.json();
        })
        // .then(resp => (this.weather = resp))
        .then(resp =>   {
        this.weather = resp;
        console.log("weather" in this)
          //  console.log(resp + weather);
        })
        .catch(function(e) {
          console.log(e);
        });
      // console.log(typeof this.weather + "  " + typeof this.weather.main);
      // console.log(+"  " + typeof this.weather.main);
      // console.log(+"  " + this.weather);
    }
    // signUp() {
    //   console.log("error")
    // },
  }
};
</script>

<style lang="scss">
.registration__form.form {
  // .form__btn

  &__btn {
  }
}
.form-group {
}
.form-control {
}
.form-check {
}
.form-check-input {
}
.form-check-label {
}
</style>
