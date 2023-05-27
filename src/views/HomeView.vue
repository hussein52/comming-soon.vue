<template>
  <div>
    <header>
      <div class="brand">
        <div class="logo">
          <img src="../assets/logo1.png" alt="logo" />
        </div>
        <div class="slogo">
          <img src="../assets/logo2.png" alt="slogo" />
        </div>
      </div>
      <div class="heading-page">
        <h1>انتظروا انطلاق التطبيق قريبا</h1>
        <p>
          هو ببساطة نص شكلي(بمعنى ان الغاية هي الشكل وليس المحتوى)ويستخدم في
          صناعات المطابع
        </p>
      </div>
      <div class="count-down">
        <div class="counter">
          <span class="count-amount" id="months"></span>
          <span class="count-period">أشهر</span>
        </div>
        <div class="counter">
          <span class="count-amount" id="days"></span>
          <span class="count-period">أيام</span>
        </div>
        <div class="counter">
          <span class="count-amount" id="hours"></span>
          <span class="count-period">ساعات</span>
        </div>
        <div class="counter">
          <span class="count-amount" id="minutes"></span>
          <span class="count-period">دقائق</span>
        </div>
        <div class="counter">
          <span class="count-amount" id="seconds"></span>
          <span class="count-period">ثواني</span>
        </div>
      </div>
      <div class="send-notification">
        <p>هل تريد إرسال إشعار فور الانطلاق</p>
        <from class="needs-validation" novalidate>
          <div class="input-group">
            <input
              type="email"
              class="form-control"
              placeholder="البريد الالكتروني"
              required
            />
            <button type="submit" class="btn">
              <img src="../assets/Untitled-2.png" alt="" />
            </button>
            <div class="invalid-feedback">
              عذرا يرجى إدخال البريد الالكتروني
            </div>
          </div>
        </from>
      </div>
    </header>
    <div>
      <div class="features">
        <div class="container">
          <br />
          <h2>مميزات اللعبة</h2>
          <div class="row">
            <div class="col-md-6">
              <div class="d-flex">
                <div class="flex-shrink-0">
                  <img src="../assets/prush.png" alt="prush icon" />
                </div>
                <div class="flex-grow-1 ms-3">
                  <h4>تصميم أنيق وعصري</h4>
                  <p>
                    هو ببساطة نص شكلي (بمعنى ان الغاية هي الشكل وليس المحتوى)
                    ويستخدم في صناعات المطابع
                  </p>
                </div>
              </div>
            </div>

            <div class="col-md-6">
              <div class="d-flex">
                <div class="flex-shrink-0">
                  <img src="../assets/phone.png" alt="phone icon" />
                </div>
                <div class="flex-grow-1 me-3">
                  <h4>اللعبة متوفرة بوضع الشاشة الممتلئ</h4>
                  <p>
                    هو ببساطة نص شكلي (بمعنى ان الغاية هي الشكل وليس المحتوى)
                    ويستخدم في صناعات المطابع
                  </p>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="d-flex">
                <div class="flex-shrink-0">
                  <img src="../assets/photo.png" alt="photo icon" />
                </div>
                <div class="flex-grow-1 ms-3">
                  <h4>يوجد صور لتوضيح تفاصيل اللعبة</h4>
                  <p>
                    هو ببساطة نص شكلي (بمعنى ان الغاية هي الشكل وليس المحتوى)
                    ويستخدم في صناعات المطابع
                  </p>
                </div>
              </div>
            </div>

            <div class="col-md-6">
              <div class="d-flex">
                <div class="flex-shrink-0">
                  <img src="../assets/mail.png" alt="mail icon" />
                </div>
                <div class="flex-grow-1 me-3">
                  <h4>يمكنك إرسال الهدايا لأصدقاءك عبر اللعبة</h4>
                  <p>
                    هو ببساطة نص شكلي (بمعنى ان الغاية هي الشكل وليس المحتوى)
                    ويستخدم في صناعات المطابع
                  </p>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="d-flex">
                <div class="flex-shrink-0">
                  <img src="../assets/fork.png" alt="fork icon" />
                </div>
                <div class="flex-grow-1 ms-3">
                  <h4>يمكنك مشاركة اللعبة كمجموعة</h4>
                  <p>
                    هو ببساطة نص شكلي (بمعنى ان الغاية هي الشكل وليس المحتوى)
                    ويستخدم في صناعات المطابع
                  </p>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <div class="d-flex">
                <div class="flex-shrink-0">
                  <img src="../assets/person-plus.png" alt="person-plus icon" />
                </div>
                <div class="flex-grow-1 me-3">
                  <h4>إضافة أصدقاء جدد لاستخدام اللعبة</h4>
                  <p>
                    هو ببساطة نص شكلي (بمعنى ان الغاية هي الشكل وليس المحتوى)
                    ويستخدم في صناعات المطابع
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <div class="footer-notification">
        <h3>قم بإضافة بريدك الألكتروني ليصلك إشعار فور الانطلاق</h3>
        <form class="needs-validation" novalidate>
          <div class="input-group">
            <input
              type="email"
              class="form-control"
              placeholder="البريد الالكتروني"
              required
            />
            <button type="submit">
              <img src="../assets/send2.png" alt="send icon" />
            </button>
            <div class="invalid-feedback">
              عذرا يرجى ادخال البريد الالكتروني
            </div>
          </div>
        </form>
      </div>
      <div class="social-media">
        <h3>تابعنا على القنوات الإجتماعية</h3>
        <ul class="list-inline">
          <li class="list-inline-item">
            <a href="#"
              ><img src="../assets/facebook black-app-symbol.png"
            /></a>
          </li>
          <li class="list-inline-item">
            <a href="#"><img src="../assets/twitter.png" /></a>
          </li>
          <li class="list-inline-item">
            <a href="#"><img src="../assets/instagram.png" /></a>
          </li>
          <li class="list-inline-item">
            <a href="#"><img src="../assets/linkedin.png" /></a>
          </li>
        </ul>
        <hr />
        <a href="mailto:info@example.com" class="email">
          <i class="far fa-envelope"></i>
          info@example.com"
        </a>
      </div>
    </footer>
  </div>
</template>

<script>
// var countDownDate = new Date();
// countDownDate = new Date(countDownDate.getFullYear() + 1 , countDownDate.getMonth() -6 , 01);

// var x = setInterval(function(){
//     var now = new Date();
//     var diff = countDownDate - now;

//     var months = Math.floor(diff / (1000 * 60 * 60 * 24 * 30));
//     var days = Math.floor((diff % (1000 * 60 * 60 * 24 * 30)) / (1000 * 60 * 60 * 24));
//     var hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
//     var minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
//     var seconds = Math.floor((diff % (1000 * 60))/ 1000);

//     document.getElementById("months").innerHTML = months;
//     document.getElementById("days").innerHTML = days;
//     document.getElementById("hours").innerHTML = hours;
//     document.getElementById("minutes").innerHTML = minutes;
//     document.getElementById("seconds").innerHTML = seconds;

// }, 1000)

// Example starter JavaScript for disabling form submissions if there are invalid fields
// (function () {
//     'use strict'

// Fetch all the forms we want to apply custom Bootstrap validation styles to
// var forms = document.querySelectorAll('.needs-validation')

// Loop over them and prevent submission
//   Array.prototype.slice.call(forms)
//     .forEach(function (form) {
//       form.addEventListener('submit', function (event) {
//         if (!form.checkValidity()) {
//           event.preventDefault()
//           event.stopPropagation()
//         }

//         form.classList.add('was-validated')
//       }, false)
//     })
// })()
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

// export default {
//   name: "HomeView",
//   components: {
//     HelloWorld,
//   },
// };
</script>

<style>
* {
  padding: 0;
  margin: 0;
  font-family: "Cairo", sans-serif;
}
/* font-face {
  font-family: Cairo-SemiBold;
  src: url("../fonts/Cairo-SemiBold.ttf");
} */

/* body {
  font-family: Cairo-SemiBold;
  direction: rtl;
} */
@import url("https://fonts.googleapis.com/css2?family=Cairo&display=swap");
header {
  background-image: url(../assets/header.jpg);
  background-size: cover;
  background-position: center center;
  text-align: center;
}

header .brand {
  margin: 100px auto 60px;
  display: inline-block;
  padding-bottom: 35px;
  border-bottom: 5px solid #464b52;
}

header .heading-page h1 {
  font-size: 60px;
  font-weight: bold;
  line-height: 75px;
  color: #fff;
}

header .heading-page p {
  font-size: 18px;
  line-height: 25px;
  color: #acacac;
  width: 40%;
  margin: auto;
}

header .count-down {
  width: 60%;
  margin: 90px auto;
}

header .counter {
  display: inline-block;
  margin: 0 15px;
}

header .count-amount {
  font-size: 60px;
  display: block;
  font-weight: bold;
  color: #ffce00;
}
header .count-period {
  font-size: 30px;
  display: block;
  font-weight: bold;
  color: #fff;
}

header .send-notification p {
  font-size: 18px;
  color: #fff;
}

header .input-group {
  width: 30%;
  margin: auto;
  transform: translateY(30%);
}

header .send-notification .input-group button {
  background-color: #ffce00;
  padding: 13px 10px 10px 5px;
  border-radius: 0;
}

header .send-notification .input-group input {
  border-radius: 0;
  border: 2px solid #e6e6e6;
  color: #e6e6e6;
  font-size: 18px;
  text-align: right;
}
.invalid-feedback {
  margin-bottom: -30px;
}
div.features {
  padding: 100px 0;
}

div.features h2 {
  font-size: 45px;
  color: #555;
  margin-bottom: 50px;
  font-weight: bold;
}
div.features .row .d-flex {
  border: 4px solid #fafafa;
  padding: 40px 10px;
  margin-bottom: 20px;
  max-height: 190px;
}

div.features .row .d-flex h4 {
  font-size: 24px;
  color: #555;
  font-weight: bold;
}
div.features .row .d-flex p {
  font-size: 15px;
  line-height: 25px;
  color: #a1a1a1;
}

div.features .row .col-md-6:nth-child(even) {
  direction: ltr;
}

footer {
  background-image: url(../assets/footer-bg.jpg);
  background-size: cover;
  background-position: center;
  text-align: center;
}

footer .footer-notification {
  background-color: rgba(255, 206, 0, 0.7);
  padding: 70px 0;
}

footer .footer-notification h3 {
  font-size: 30px;
  margin-bottom: 30px;
  font-weight: bold;
}

footer .input-group {
  width: 30%;
  margin: auto;
}

footer .input-group input {
  border-radius: 0;
  font-size: 18px;
  color: #c7c7c7;
  border-color: #fff;
  text-align: right;
}
footer .input-group button {
  border-radius: 0;
  background-color: #393939;
  padding: 13px 33px;
}

footer .social-media {
  background-color: rgba(57, 57, 57, 0.9);
  padding: 100px 0 30px;
}

footer .social-media h3 {
  font-size: 30px;
  margin-bottom: 30px;
  color: #fff;
}

footer .social-media .list-inline a {
  width: 70px;
  height: 70px;
  line-height: 70px;
  font-size: 24px;
  background-color: rgba(255, 255, 255, 0.068);
  color: #fff;
  display: block;
  transition: 0.5s;
}

footer .social-media .list-inline li {
  padding: 5px !important;
}

footer .social-media .list-inline a:hover {
  background-color: #fad32f;
  color: rgba(248, 236, 236, 0.9);
}

footer .social-media hr {
  width: 25%;
  margin: 50px auto 30px;
}

footer .social-media a.email {
  color: #b4b4b4;
  text-decoration: none;
}
footer .social-media a.email i {
  color: #ffce00;
  margin-left: 5px;
}

@media (max-width: 992px) {
  header .heading-page p {
    width: 70%;
  }

  .input-group {
    width: 50% !important;
  }

  section.features .row .d-flex {
    padding: 15px 10px;
  }

  section.features .row .d-flex h4 {
    font-size: 20px;
  }
}
@media (max-width: 768px) {
  header .count-down {
    width: 80%;
  }
}
@media (max-width: 576px) {
  header .heading-page h1 {
    font-size: 45px;
  }
  header .heading-page p {
    width: 80% !important;
  }
}
</style>
