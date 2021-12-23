<template>
  <footer class="footer">
    <div class="container">
      <div class="footer__inner">
        <div class="footer__logo">
          <Logo></Logo>
        </div>

        <div class="terms-use">
          <a href="" class="terms-use">Условия использования</a>
        </div>
        <div class="сopyright">
          <a href="" class="сopyright__link">Авторские права</a>
        </div>
        <div class="social-icons">
          <ul class="social-icons__list">
            <li class="social-icons__item">
              <a href="">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="10"
                  height="19"
                  viewBox="0 0 10 19"
                >
                  <path
                    fill="#006cac"
                    fill-rule=" evenodd"
                    id="Контур"
                    class="cls-1"
                    d="M1058.62,1183h-2.4c-2.69,0-4.43,1.83-4.43,4.67v2.16h-2.41a0.388,0.388,0,0,0-.38.39v3.13a0.386,0.386,0,0,0,.38.38h2.41v7.89a0.378,0.378,0,0,0,.37.38h3.14a0.382,0.382,0,0,0,.39-0.38v-7.89h2.81a0.38,0.38,0,0,0,.38-0.38v-3.13a0.438,0.438,0,0,0-.1-0.28,0.411,0.411,0,0,0-.28-0.11h-2.81V1188a1.087,1.087,0,0,1,1.32-1.32h1.61a0.382,0.382,0,0,0,.38-0.39v-2.9A0.388,0.388,0,0,0,1058.62,1183Z"
                    transform="translate(-1049 -1183)"
                  />
                </svg>
              </a>
            </li>
            <li class="social-icons__item">
              <a href="">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="22"
                  height="13"
                  viewBox="0 0 22 13"
                >
                  <path
                    id="Контур"
                    fill="#006cac"
                    fill-rule=" evenodd"
                    class="cls-1"
                    d="M1105.94,1194.26c0.72,0.76,1.49,1.45,2.14,2.28a6.462,6.462,0,0,1,.78,1.15,0.853,0.853,0,0,1-.49,1.31l-3.2-.01a2.4,2.4,0,0,1-2.04-.87c-0.44-.47-0.86-0.98-1.28-1.45a2.932,2.932,0,0,0-.58-0.54,0.655,0.655,0,0,0-1.07.26,3.7,3.7,0,0,0-.34,1.57,0.866,0.866,0,0,1-1.01,1.03,7.933,7.933,0,0,1-4.59-1.03,10.4,10.4,0,0,1-3.08-3.01,40.911,40.911,0,0,1-4.07-7.58c-0.25-.59-0.06-0.9.56-0.92,1.05-.02,2.1-0.02,3.14,0a0.931,0.931,0,0,1,.87.68,20.256,20.256,0,0,0,2.13,4.11,3.583,3.583,0,0,0,.8.93,0.483,0.483,0,0,0,.83-0.26,3.138,3.138,0,0,0,.18-0.86,13.957,13.957,0,0,0-.05-3.03,1.229,1.229,0,0,0-1.02-1.15c-0.32-.06-0.26-0.18-0.12-0.36a1.122,1.122,0,0,1,.97-0.51h3.64a0.9,0.9,0,0,1,.77.99v4.19a1.294,1.294,0,0,0,.52,1.08,0.692,0.692,0,0,0,.72-0.38,12.745,12.745,0,0,0,2.03-3.26c0.25-.52.46-1.06,0.67-1.6a0.753,0.753,0,0,1,.81-0.58h3.49a1.774,1.774,0,0,1,.32.02,0.625,0.625,0,0,1,.56.96,9.319,9.319,0,0,1-1.39,2.51c-0.59.84-1.2,1.66-1.77,2.51A1.151,1.151,0,0,0,1105.94,1194.26Z"
                    transform="translate(-1087 -1186)"
                  />
                </svg>
              </a>
            </li>
            <li class="social-icons__item">
              <a href="">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  xmlns:xlink="http://www.w3.org/1999/xlink"
                  width="14"
                  height="21"
                  viewBox="0 0 14 21"
                >
                  <image
                    id="Сгруппировать:_1_объект"
                    data-name="Сгруппировать: 1 объект"
                    width="14"
                    height="21"
                    xlink:href="data:img/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAVCAMAAABBhy+7AAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAABC1BMVEX///8AbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAbKwAAABQw2N4AAAAV3RSTlMAE4TW+/zXhTPl5jQW6uuP0mXc4woL2vWrrfPd5w/ojXR1ihQSLN5HuJQrye3GKpO68PpmREJiqOzVGbOwOdDPNQEDnaIEBq6v9klFtTo47m302C3T+HNIswKZAAAAAWJLR0RY7bXEjgAAAAlwSFlzAAALEgAACxIB0t1+/AAAAAd0SU1FB+UMBAw5MZaPLiMAAADXSURBVBjTTY/nUgJBEIQHReUUuOOICkgSkCDImcmYkSQK9Pu/ib23Utp/pr+t7alpERHPzq53b//AI658BlwdHinyB/CroJ9o0lihkMVhEm0gHBGJhoEYMQ4kVOgYOOFIAqm0SPoUsIkZhuxsjq/IEwvGdrNxpkLFkqZkkVA+r1RztXrwIttoXpalBTiJq+ub2zsHuBcL//Qg7c4fdQtM95p95QeVoa40yis0R5oen/TX5xdFr2+0DteiwybyTjP+mIw5prpRayYyXwBe4ufy69u9dbXeyA+ssTd67BuqIQAAAABJRU5ErkJggg=="
                  />
                </svg>
              </a>
            </li>
          </ul>
        </div>
       
      </div>
    </div>
  </footer>
</template>
<script>
import Logo from "./Logo.vue";
export default {
  components: {
    Logo
  }
};
</script>

<style lang="scss">
@import "~/assets/sсss/variables.scss";
.footer {
  // background-color: var(--bac-fon);
  background-color: $bac-fon;
  max-height: 100px;
  // .footer__inner

  &__inner {
    display: flex;
    justify-content: space-between;
    padding: 30px 0;
  }

  // .footer__logo

  &__logo {
  }
}
.terms-use {
}
.сopyright {
  // .сopyright__link

  &__link {
  }
 


}
 .social-icons {

		// .social-icons__list

		&__list {
      display: flex;
		}

		// .social-icons__item

		&__item {
      margin: 0 15px;
		}
}
</style>
