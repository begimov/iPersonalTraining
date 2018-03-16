<template>
  <div>
    <div class="jumbotron jumbotron-fluid text-white">
      <div class="container">
        <div class="row">
          <div class="col"><img src="../assets/logo.png" class="logo" width="110"></div>
        </div>
        <h1 class="display-3 d-none d-sm-block text-uppercase"><strong>Персональное обучение и&nbsp;коучинг руководителей</strong></h1>
        <h1 class="display-5 d-sm-none text-uppercase">Персональное обучение и&nbsp;коучинг руководителей</h1>
      </div>
    </div>

    <div class="container">
      <div class="row last-row mt-5">
        <div class="col">
          <h2>Если Вам необходимо</h2>
        </div>
        <div class="col">
          <ul>
            <li>Восполнить недостаток знаний в&nbsp;области управления</li>
            <li>Посоветоваться с&nbsp;авторитетным экспертом-управленцем</li>
            <li>Поработать с опытным наставником над сложной задачей</li>
            <li>Найти ключ к&nbsp;решению застарелых проблем компании</li>
          </ul>
        </div>
      </div>
      <div class="row">
        <div class="col">
          <h2>Мы&nbsp;предлагаем Вам помощь Александра Кочнева, управляющего партнера консалтинговой компании iTeam.</h2>
        </div>
      </div>
      <div class="row last-row mt-3">
        <div class="col-md-3">
          <img class="img-fluid" src="../assets/kochnev.jpg">
        </div>
        <div class="col-md-9">
          <ul>
            <li>Наставник и&nbsp;коуч собственников компаний с&nbsp;2002 года</li>
            <li>Руководитель 200+ консалтинговых проектов</li>
            <li>Автор 50+&nbsp;мастер-классов и&nbsp;программ обучения управленцев</li>
            <li>Ведущий семинаров и&nbsp;бизнес-тренингов, на&nbsp;которых обучились 50+&nbsp;тысяч управленцев</li>
            <li>Автор книги &laquo;Как найти миссию компании&raquo;</li>
            <li>Автор 100+ статей об&nbsp;управлении компаниями</li>
            <li>Создатель системы &laquo;Русский Менеджмент&raquo;&nbsp;&mdash; комплекса знаний и&nbsp;технологий управления компаниями</li>
          </ul>
        </div>
      </div>
      <div class="row text-center">
        <div class="col">
          <h2>Подать заявку на&nbsp;бесплатную консультацию с&nbsp;Александром Кочневым</h2>
        </div>
      </div>
      <div class="row text-center last-row ">
        <div class="col">
          <Grform 
            campaign_token="1"
          />
        </div>
      </div>
      <div class="row last-row text-center">
        <div class="col">
          <a href="#" class="btn btn-primary btn-lg text-uppercase" @click.prevent="scrollMeTo('join-block')">Заказать платное обучение</a>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row text-center">
        <div class="col">
          <h2>За&nbsp;20&nbsp;лет нашей работы с&nbsp;собственниками и&nbsp;руководителями компаний сложился перечень вопросов, беспокоящих большинство управленцев высшего звена:</h2>
        </div>
      </div>
      <div class="row">
        <div class="col">
          <ol class="p-0">
            <div class="card mt-2">
              <div class="card-body pl-5 py-3">
                <li>Как добиться того, чтобы планы выполнялись?</li>
              </div>
            </div>
            <div class="card mt-2">
              <div class="card-body pl-5 py-3">
                <li>Как сократить время совещаний и&nbsp;повысить их&nbsp;продуктивность?</li>
              </div>
            </div>
            <div class="card mt-2">
              <div class="card-body pl-5 py-3">
                <li>Как повысить исполнительскую дисциплину?</li>
              </div>
            </div>
            <div class="card mt-2">
              <div class="card-body pl-5 py-3">
                <li>Как мотивировать топ-менеджеров?</li>
              </div>
            </div>
            <div class="card mt-2">
              <div class="card-body pl-5 py-3">
                <li>Как делегировать полномочия и&nbsp;не&nbsp;потерять контроль?</li>
              </div>
            </div>
            <div class="card mt-2">
              <div class="card-body pl-5 py-3">
                <li>Как преодолеть низкую заинтересованность сотрудников в&nbsp;результатах работы?</li>
              </div>
            </div>
            <div class="card mt-2">
              <div class="card-body pl-5 py-3">
                <li>Как навести порядок в&nbsp;рабочих процессах?</li>
              </div>
            </div>
            <div class="card mt-2">
              <div class="card-body pl-5 py-3">
                <li>Как найти &laquo;правильных&raquo; руководителей?</li>
              </div>
            </div>
            <div class="card mt-2">
              <div class="card-body pl-5 py-3">
                <li>Как добиться командной работы?</li>
              </div>
            </div>
            <div class="card mt-2">
              <div class="card-body pl-5 py-3">
                <li>Как преодолеть сопротивление изменениям?</li>
              </div>
            </div>
          </ol>
        </div>
      </div>
      <div class="row last-row">
        <div class="col">
          <div class="card bg-dark text-light">
            <div class="card-body pt-4 pb-3">
              <p>Эти и&nbsp;многие другие вопросы мы&nbsp;рассматриваем с&nbsp;руководителями сотен предприятий, находим решения и&nbsp;воплощаем их&nbsp;на&nbsp;практике.</p>
            </div>
          </div>
        </div>
      </div>
      <div class="row text-center last-row">
        <div class="col-lg-6 offset-lg-3">
          <h5>Александр Красный, собственник компании &laquo;ГаРус&raquo;</h5>
            <p><a href="http://groupautorus.ru/" target="_blank"><img src="https://iteam.ru/landing/template/img/logo_garus.png" class="img-fluid rounded"></a></p>
            <div class="embed-responsive embed-responsive-16by9" style="margin-bottom:30px;">
              <iframe width="560" height="315" src="https://www.youtube.com/embed/Rp4Jh-DP7is" frameborder="0" allowfullscreen></iframe>
            </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row text-center">
        <div class="col">
          <h2></h2>
        </div>
      </div>
      <div class="row last-row">
        <div class="col-lg-8">
          <ul>
            <li></li>
          </ul>
          <p></p>
        </div>
        <div class="col-lg-4 mt-3 mt-lg-0 mp-is-usefull-block">&nbsp;</div>
      </div>
    </div>

    <div class="container">
      <div class="row text-center" ref="join-block">
        <div class="col" style="margin-top:30px">
          <h2>Я участвую!</h2>
        </div>
      </div>
      <div class="row last-row text-center">
        
        <div class="col-xl-3 col-md-6 mt-2">
          <div class="card h-100">
            <div class="card-header bg-primary text-light">
              <span style="font-size: 0.8em;">&nbsp;</span><br>
              <span class="lead"><strong>ПАКЕТ &laquo;ЛАЙТ&raquo;</strong></span><br>
              <span class="lead"><strong>&nbsp;</strong></span>
            </div>
            <ul class="list-group list-group-flush">
              <li class="list-group-item">Участие в мастер-классах.</li>
              <li class="list-group-item">Записи мастер-классов.</li>
            </ul>
            <div class="card-body"></div>
            <div class="card-footer bg-white border-top-0 pb-3">
              <h2><span class="badge badge-primary">12&thinsp;000&nbsp;&#8381;</span></h2>
              <Payment
                WMI_PAYMENT_AMOUNT="12000"
                WMI_DESCRIPTION="iTeam"
                WMI_SUCCESS_URL="https://iteam.ru/promo/processes"
                WMI_FAIL_URL="https://iteam.ru/promo/processes"
                campaign_token="nlaW6"
                product_name="ПАКЕТ «ЛАЙТ»"
              />
            </div>
          </div>
        </div>

        <div class="col-xl-3 col-md-6 mt-2">
          <div class="card border-danger card-accent h-100">
            <div class="card-header bg-danger text-light">
              <span class="lead"><strong>ПАКЕТ &laquo;БАЗОВЫЙ&raquo;</strong></span><br>
              <span class="badge badge-warning" style="font-size: 0.8em;">Включает ПАКЕТ &laquo;ЛАЙТ&raquo;</span><br>
              <span class="lead"><strong>+</strong></span>
            </div>
            <ul class="list-group list-group-flush">
              <li class="list-group-item">Презентационные материалы.</li>
              <li class="list-group-item">Методические материалы, шаблоны, образцы документов.</li>
            </ul>
            <div class="card-body"></div>
            <div class="card-footer bg-white border-top-0 pb-3">
              <h2><span class="badge badge-primary">40&thinsp;000&nbsp;&#8381;</span></h2>
              <Payment
                WMI_PAYMENT_AMOUNT="40000"
                WMI_DESCRIPTION="iTeam"
                WMI_SUCCESS_URL="https://iteam.ru/promo/processes"
                WMI_FAIL_URL="https://iteam.ru/promo/processes"
                campaign_token="pu9s"
                product_name="ПАКЕТ «БАЗОВЫЙ»"
              />
            </div>
          </div>
        </div>

        <div class="col-xl-3 col-md-6 mt-2">
          <div class="card h-100">
            <div class="card-header bg-danger text-light">
              <span class="lead"><strong>ПАКЕТ &laquo;СУПЕР&raquo;</strong></span><br>
              <span class="badge badge-warning" style="font-size: 0.8em;">Включает ПАКЕТ &laquo;БАЗОВЫЙ&raquo;</span><br>
              <span class="lead"><strong>+</strong></span>
            </div>
            <ul class="list-group list-group-flush">
              <li class="list-group-item">10 рабочих сессий с Александром Кочневым по Skype.</li>
              <li class="list-group-item">Рецензирование документов.</li>
              <li class="list-group-item">Ответы на вопросы по e-mail и телефону. Онлайн-консультации.</li>
            </ul>
            <div class="card-body"></div>
            <div class="card-footer bg-white border-top-0 pb-3">
              <h2><span class="badge badge-primary">160&thinsp;000&nbsp;&#8381;</span></h2>
              <Payment
                WMI_PAYMENT_AMOUNT="160000"
                WMI_DESCRIPTION="iTeam"
                WMI_SUCCESS_URL="https://iteam.ru/promo/processes"
                WMI_FAIL_URL="https://iteam.ru/promo/processes"
                campaign_token="nlaKD"
                product_name="ПАКЕТ «СУПЕР»"
              />
            </div>
          </div>
        </div>

        <div class="col-xl-3 col-md-6 mt-2">
          <div class="card h-100">
            <div class="card-header bg-danger text-light">
              <span class="lead"><strong>ПАКЕТ &laquo;ПРЕМИУМ&raquo;</strong></span><br>
              <span class="badge badge-warning" style="font-size: 0.8em;">Включает ПАКЕТ &laquo;БАЗОВЫЙ&raquo;</span><br>
              <span class="lead"><strong>+</strong></span>
            </div>
            <ul class="list-group list-group-flush">
              <li class="list-group-item">3 очных стратегических сессий и 7 рабочих сессий с Александром Кочневым по Skype.</li>
              <li class="list-group-item">Рецензирование документов.</li>
              <li class="list-group-item">Ответы на вопросы по e-mail и телефону. Онлайн-консультации.</li>
            </ul>
            <div class="card-body"></div>
            <div class="card-footer bg-white border-top-0 pb-3">
              <h2><span class="badge badge-primary">800&thinsp;000&nbsp;&#8381;</span></h2>
              <Payment
                WMI_PAYMENT_AMOUNT="800000"
                WMI_DESCRIPTION="iTeam"
                WMI_SUCCESS_URL="https://iteam.ru/promo/processes"
                WMI_FAIL_URL="https://iteam.ru/promo/processes"
                campaign_token="nlaoj"
                product_name="ПАКЕТ «ПРЕМИУМ»"
              />
            </div>
          </div>
        </div>
        
      </div>

      <div class="row text-center">
        <div class="col">
          <h2>Отзывы наших участников:</h2>
        </div>
      </div>
      <div class="row text-center last-row">
        <div class="col-md-6">
          <h5>Александр Красный, &laquo;ГаРус&raquo;</h5>
            <p><a href="http://groupautorus.ru/" target="_blank"><img src="https://iteam.ru/landing/template/img/logo_garus.png" class="img-fluid rounded"></a></p>
            <div class="embed-responsive embed-responsive-16by9" style="margin-bottom:30px;">
              <iframe width="560" height="315" src="https://www.youtube.com/embed/Rp4Jh-DP7is" frameborder="0" allowfullscreen></iframe>
            </div>
        </div>
        <div class="col-md-6">
          <h5>Александр Соловьев, &laquo;FIS&raquo;</h5>
          <p><a href="http://neofood.de/" target="_blank"><img src="https://iteam.ru/landing/template/img/logo_neofood.png" class="img-fluid rounded"></a></p>
          <div class="embed-responsive embed-responsive-16by9" style="margin-bottom:30px;">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/U4QFO0ILnmE" frameborder="0" allowfullscreen></iframe>
          </div>
        </div>
        <div class="col-md-6">
          <h5>Геннадий Черкасов, &laquo;Миг Плюс&raquo;</h5>
          <p><a href="http://migplus.ru/" target="_blank"><img src="https://iteam.ru/landing/template/img/logo_migplus.png" class="img-fluid rounded"></a></p>
          <div class="embed-responsive embed-responsive-16by9" style="margin-bottom:30px;">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/C2MVqTRj40w" frameborder="0" allowfullscreen></iframe>
          </div>
        </div>
        <div class="col-md-6">
          <h5>Яна Ходак, &laquo;МК&nbsp;Практик&raquo;</h5>
          <p><a href="http://practicmed.ru/" target="_blank"><img src="https://iteam.ru/landing/template/img/logo_mkpraktik.png" class="img-fluid rounded"></a></p>
          <div class="embed-responsive embed-responsive-16by9" style="margin-bottom:30px;">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/rlzpDK1my58" frameborder="0" allowfullscreen></iframe>
          </div>
        </div>
      </div>

      <div class="row text-center">
        <div class="col">
          <h2>FAQ</h2>
        </div>
      </div>
      <div class="row last-row">
        <div class="col">
          <div class="card">
            <div class="card-body">
              <div class="row">
                <div class="col-sm-4">
                  <div class="nav flex-column nav-pills" id="v-pills-tab" role="tablist" aria-orientation="vertical">
                    <a class="nav-link active" id="v-pills-home-tab" data-toggle="pill" href="#v-pills-home" role="tab" aria-controls="v-pills-home" aria-selected="true">Какие методы оплаты доступны?</a>
                    <a class="nav-link" id="v-pills-profile-tab" data-toggle="pill" href="#v-pills-profile" role="tab" aria-controls="v-pills-profile" aria-selected="false">Оплата на&nbsp;вашем сайте безопасна?</a>
                    <a class="nav-link" id="v-pills-messages-tab" data-toggle="pill" href="#v-pills-messages" role="tab" aria-controls="v-pills-messages" aria-selected="false">Вы&nbsp;принимаете карты стран СНГ?</a>
                  </div>
                </div>
                <div class="col-sm-8">
                  <div class="tab-content" id="v-pills-tabContent">
                    <div class="tab-pane fade show active" id="v-pills-home" role="tabpanel" aria-labelledby="v-pills-home-tab">
                      <p>Мы&nbsp;осуществляем оплату с&nbsp;помощью платежного сервиса WalletOne. Вы&nbsp;можете оплатить продукт практически любым доступным сегодня способом. Все способы вы&nbsp;можете <a href="https://www.walletone.com/ru/merchant/payments/#country=RU&amp;section=cash" target="_blank">увидеть здесь.</a></p>
                    </div>
                    <div class="tab-pane fade" id="v-pills-profile" role="tabpanel" aria-labelledby="v-pills-profile-tab">
                      <p>Wallet One использует стандарт безопасности PCI&nbsp;DSS, SSL-протокол, системы безопасности Verified by&nbsp;Visa и&nbsp;MasterCard SecureCode.</p>
                      <p><a href="https://www.walletone.com/ru/merchant/security/" target="_blank">Подробнее здесь</a></p>
                    </div>
                    <div class="tab-pane fade" id="v-pills-messages" role="tabpanel" aria-labelledby="v-pills-messages-tab">
                      <p>Да, мы&nbsp;принимаем карты, выпущенные на&nbsp;территории Украины, Беларуси, Казахстана и&nbsp;ряда других стран. Список всех стран и&nbsp;вариантов оплаты можно <a href="https://www.walletone.com/ru/merchant/payments/#country=RU&amp;section=cash" target="_blank">увидеть по&nbsp;ссылке</a></p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<script src="./home.js"></script>

<style scoped>
.header-title {
  margin-top: 30px;
}
.header-date {
  margin-top: 20px;
  margin-bottom: 10px;
}
.badge {
  font-size: 1.1em;
}
.last-row {
  margin-bottom: 50px;
}
h2 {
  margin-bottom: 20px;
}
.jumbotron {
  padding-top: 20px;
  background-image: url("../assets/bg.jpg");
  background-size: cover;
}
.container-fluid {
  padding: 20px 10px;
  margin-bottom: 50px;
}
.nav-tabs-links a {
  color: #fff;
  text-decoration: underline;
}
.logo {
  margin-bottom: 20px;
}
.card-accent {
  box-shadow: 0 0 20px rgba(0,0,0,0.3);
  border-width: 2px;
}
.mp-is-block {
  background-image: url("../assets/mp.jpg");
  background-size: cover;
  min-height: 150px;
}
.mp-is-usefull-block {
  background-image: url("../assets/usefull.jpg");
  background-size: cover;
}


@media (max-width: 767.98px) {
  .header-title {
    margin-top: 20px;
  }
}
@media (max-width: 575.98px) {
  .header-title {
    margin-top: 10px;
  }
}
</style>
