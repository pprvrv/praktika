<html>

<head>
    <title>Главная</title>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="normalize.css">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
    <meta name="viewport" content="width=device-width, initial-scale=1">

</head>
<!--пока все ссылки ведут на сайт placestart-->

<body>
    <header>
        <div class="container">
            <div class="container_header">

                <a href="./index.html">
                    <img src="/logo.png" class="logo">
                </a>
                <nav id="mainnav" class="mainnav">
                    <ul class="menu">
                        <li><a href="overview.html">О компании</a></li>
                        <li class="programs"><a href="#">Услуги</a>
                            <ul class="submenu">
                                <li><a href="services.html">ЖКХ</a></li>
                                <li><a href="services-single.html">Дорожное хозяйство</a></li>
                                <li><a href="services-single.html">Архитектура</a></li>
                                <li class="programs"><a href="#">Программы</a>
                                    <ul class="submenu">
                                        <li><a href="#">Программа комплексного развития систем коммунальной
                                                инфраструктуры (ПКРСКИ)</a></li>
                                        <li><a href="#">Программа комплексного развития транспортной инфраструктуры
                                                (ПКРТИ)</a></li>
                                        <li><a href="#">Программа комплексного развития социальной инфраструктуры
                                                (ПКРСИ)</a></li>
                                        <li><a href="#">Программа энергосбережения и повышения энергетической
                                                эффективности (ПЭ)</a></li>
                                    </ul>
                                </li>
                            </ul>
                        </li>
                        <li><a href="case-v1.html">Контакты</a>
                        </li>

                    </ul>
                </nav>


                <a href="https://place-start.ru/" class="href_whatsapp_viber">
                    <img src="whatsapp.png" class="whatsapp">
                </a>
                <a href="https://place-start.ru/" class="href_whatsapp_viber">
                    <img src="viber.png" class="viber">
                </a>
                <p class="number_1">
                    +7 (911) 501-35-32
                </p>
                <p class="number_2">
                    8 (8172) 50-35-32
                </p>
                <a href="https://place-start.ru/" class="header_href_btn">
                    <button class="btn_zayavka" id="ostav_zayavku">Оставить заявку</button>
                </a>
            </div>
        </div>
    </header>
    <section class="section1">
        <div class="container">
            <div class="posmotret_uslugi">
                <div class="razrabotka_div">
                    <h1 class="zagolovok_razrabotka">Разработка и актуализация проектов в сфере ЖКХ</h1>
                    <a href="https://place-start.ru/" class="section1_href_btn">
                        <button class="btn_posmotret_uslugi">Посмотреть услуги</button>
                    </a>
                    <div class="strelki">
                        <div class="swiper-button-prev" id="str_prev">
                            <img src="btn_nazad.png">
                        </div>
                        <div class="swiper-button-next" id="str_prev">
                            <img src="btn_vpered.png">
                        </div>
                    </div>
                </div>
                <div class="swiper">
                    <!-- Additional required wrapper -->
                    <div class="swiper-wrapper">
                        <!-- Slides -->
                        <div class="swiper-slide">
                            <img src="slaid1.jpg" class="img_swiper">
                        </div>
                        <div class="swiper-slide">
                            <img src="slaid2.jpg" class="img_swiper">
                        </div>
                        <div class="swiper-slide">
                            <img src="slaid3.jpg" class="img_swiper">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <section class="section2">
        <div class="container">
            <div class="preimuchestva">
                <div class="komanda">
                    <p class="preimuchestva_text">Преимущества
                    </p>
                    <h1 class="komanda_text">Наша команда</h1>
                    <ul class="preimuchestva_spisok">
                        <li class="tochki">
                            <p class="text_plusy">Регулярно взаимодействует с клиентом на всех этапах – <br>Ваш
                                персональный
                                менеджер всегда готов ответить на Ваши вопросы <br>и помочь в выборе необходимого
                                проекта
                            </p>
                        </li>
                        <li class="tochki">
                            <p class="text_plusy">Строго соблюдает сроки проектирования</p>
                        </li>
                        <li class="tochki">
                            <p class="text_plusy">Разрабатывает качественную проектную документацию, <br>соответствующую
                                всем требованиям законодательства РФ</p>
                        </li>
                        <li class="tochki">
                            <p class="text_plusy">Гарантирует актуальность работ, так как наши специалисты постоянно
                                отслеживают нормативную базу</p>
                        </li>
                        <li class="tochki">
                            <p class="text_plusy">
                                Работает по всей России</p>
                        </li>
                        <li class="tochki">
                            <p class="text_plusy">Заботится о том, чтобы наши клиенты были довольны результатом работы
                            </p>
                        </li>
                    </ul>
                </div>

                <div class="cifri">
                    <div class="cifri_razdel">
                        <div class="cifri_2">7<span class="cifri_span">лет</span>
                        </div>
                        <div style="display: flex; flex-direction: column; justify-content: flex-end;">
                            <p class="text_razdel">успешной работы <br>по всей России</p>
                        </div>
                    </div>
                    <div class="cifri_razdel">
                        <div class="cifri_2">803</div>
                        <div style="display: flex; flex-direction: column; justify-content: flex-end;">
                            <p class="text_razdel">проекта успешно <br>выполнены</p>
                        </div>

                    </div>
                    <div class="cifri_razdel">
                        <div class="cifri_2">442</div>
                        <div style="display: flex; flex-direction: column; justify-content: flex-end;">
                            <p class="text_razdel">клиента остались <br>довольны</p>
                        </div>

                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="section3">
        <div class="container">
            <div class="block_3">
                <p class="okazanie_uslug">Компания оказывает услуги <br>в следующих сферах</p>
                <div class="block_3_2">
                    <a class="zhkh" href="https://place-start.ru/">
                        <div class="img_zhkh">
                            <img src="zhkh.png" class="img_in_block">
                        </div>
                        <div class="fon"></div>
                        <p class="text_block">ЖКХ</p>
                    </a>
                    <a class="doroga" href="https://place-start.ru/">
                        <div class="img_zhkh">
                            <img src="doroga.png" class="img_in_block">
                        </div>
                        <div class="fon"></div>
                        <p class="text_block">Дорожное хозяйство</p>
                    </a>
                </div>
                <div class="block3_3">
                    <a class="arhitectura" href="https://place-start.ru/">
                        <div class="img_zhkh">
                            <img src="arh.png" class="img_in_block">
                        </div>
                        <div class="fon"></div>
                        <p class="text_block">Архитектура</p>
                    </a>
                    <a class="programmy" href="https://place-start.ru/">
                        <div class="img_zhkh">
                            <img src="prog.png" class="img_in_block">
                        </div>
                        <div class="fon"></div>
                        <p class="text_block">Программы</p>
                    </a>
                </div>
            </div>
        </div>
    </section>
    <section class="section4">
        <div class="container">
            <div class="block_4">
                <p class="rost">Рост компании</p>
                <p class="vyp_proekt">Выполненных проектов</p>
                <div class="diagramma">
                    <div class="div_2014">

                        <p class="text_p_diagramma">4</p>
                        <div class="stolb_2014"></div>

                    </div>
                    <div class="div_2015">
                        <p class="text_p_diagramma">9</p>
                        <div class="stolb_2015"></div>
                    </div>
                    <div class="div_2016">
                        <p class="text_p_diagramma">82</p>
                        <div class="stolb_2016"></div>
                    </div>
                    <div class="div_2017">
                        <p class="text_p_diagramma">50</p>
                        <div class="stolb_2017"></div>
                    </div>
                    <div class="div_2018">
                        <p class="text_p_diagramma">203</p>
                        <div class="stolb_2018"></div>
                    </div>
                    <div class="div_2019">
                        <p class="text_p_diagramma">247</p>
                        <div class="stolb_2019"></div>
                    </div>
                    <div class="div_2020">
                        <p class="text_p_diagramma">245</p>
                        <div class="stolb_2020"></div>
                    </div>
                </div>

                <div class="diagramma_year">
                    <p class="text_div_year">2014</p>
                    <p class="text_div_year">2015</p>
                    <p class="text_div_year">2016</p>
                    <p class="text_div_year">2017</p>
                    <p class="text_div_year">2018</p>
                    <p class="text_div_year">2019</p>
                    <p class="text_div_year">2020</p>
                </div>
            </div>
        </div>
    </section>
    <section class="section5">
        <div class="container">
            <div class="etapy">
                <p class="etapy_text">Этапы работы</p>
                <div class="etapy_1">
                    <div class="etapy1_size">
                        <img src="etap1.png" class="img_etap">
                        <div class="etapy_text_container">
                            <p class="zagolovok_etap">Консультация клиента</p>
                            <p class="text_etap">Наш специалист поможет в выборе необходимого проекта,
                                который актуален для Вас на сегодняшний день
                            </p>
                        </div>
                    </div>
                    <img src="/image/btn_vpered_2.png" class="btn_etap">
                    <div class="etapy1_size">
                        <img src="etap2.png" class="img_etap">
                        <div class="etapy_text_container">
                            <p class="zagolovok_etap">Заключение договора</p>
                            <p class="text_etap">Обсуждение и согласование индивидуальных условий работы и оплаты
                            </p>
                        </div>
                    </div>
                    <img src="btn_vpered_2.png" class="btn_etap">
                    <div class="etapy1_size">
                        <img src="etap3.png" class="img_etap">
                        <div class="etapy_text_container">
                            <p class="zagolovok_etap">Сбор исходной информации</p>
                            <p class="text_etap">Технический специалист свяжется с Вами и
                                поможет решить все вопросы по сбору данных</p>
                        </div>
                    </div>
                </div>
                <div class="etapy_2">
                    <div class="etapy2_size">
                        <img src="etap4.png" class="img_etap">
                        <div class="etapy_text_container">
                            <p class="zagolovok_etap">Разработка <br>и согласование проекта</p>
                            <p class="text_etap">Проект разрабатывается с учётом всех предложений и
                                отправляется Заказчику на согласование</p>

                        </div>
                    </div>
                    <img src="btn_vpered_2.png" class="btn_etap">
                    <div class="etapy2_size">
                        <img src="etap5.png" class="img_etap">
                        <div class="etapy_text_container">
                            <p class="zagolovok_etap">Подписание акта <br>и оплата счета</p>
                            <p class="text_etap">После успешного согласования проекта, Заказчик оплачивает
                                оказанные услуги</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="section6">
        <div class="container">
            <div class="karta">
                <p class="zagolovok_karta">Карта оказания услуг</p>
                <p class="text_karta">Компания 5С-проект оказывает услуги <br>по всей России</p>
                <a href="https://place-start.ru/" class="href_btn">
                    <button class="btn_karta">Оставить заявку</button>
                </a>
            </div>
            <img src="map.png" class="img_karta">
        </div>

    </section>
    <section class="section7">
        <div class="container">
            <div class="sertifikaty">
                <div class="text_sertifikat">
                    <p class="zagolovok_sertifikat">Удостоверения<br>и сертификаты</p>
                    <div class="strelki3">
                        <div class="swiper-button-prev" id="str_prev">
                            <img src="btn_nazad_3.png">
                        </div>
                        <div class="swiper-button-next" id="str_prev">
                            <img src="btn_vpered_3.png">
                        </div>
                    </div>
                </div>
                <div class="slide">
                    <div class="swiper swiper-container second-swiper">
                        <!-- Additional required wrapper -->
                        <div class="swiper-wrapper">
                            <!-- Slides -->
                            <div class="swiper-slide">
                                <img src="sert1.png">
                            </div>
                            <div class="swiper-slide">
                                <img src="sert2.png">
                            </div>
                            <div class="swiper-slide">
                                <img src="sert3.png">
                            </div>
                            <div class="swiper-slide">
                                <img src="sert4.png">
                            </div>
                            <div class="swiper-slide">
                                <img src="sert1.png">
                            </div>
                            <div class="swiper-slide">
                                <img src="sert2.png">
                            </div>
                            <!-- Add more slides here -->
                        </div>
                        <div class="swiper-scrollbar"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="section8">
        <!-- <img src="doma2.png" class="img_section_8"> -->
        <div class="container">
            <div class="svyz">
                <div class="text_svyz">
                    <p class="zagolovok_svyz">Мы готовы<br>к сотрудничеству</p>
                    <p class="text_svyz_2">Оставьте заявку на сайте, наши менеджеры свяжутся с Вами<br>и
                        проконсультируют по всем интересующим вопросам</p>
                </div>
                <div class="form_svyz">
                    <form class="forma_svyazi">
                        <div class="input-wrapper">
                            <input class="name_org" placeholder="d">
                            <label class="placeholder">Наименование организации</label>
                        </div>
                        <div class="input-wrapper">
                            <input class="name_org" placeholder="d">
                            <label class="placeholder">Контактное лицо</label>
                        </div>
                        <div class="input-wrapper">
                            <input class="name_org" placeholder="d">
                            <label class="placeholder">Телефон</label>
                        </div>
                        <div class="input-wrapper">
                            <input class="name_org" placeholder="E-mail">
                            <label class="placeholder">E-mail</label>
                        </div>
                    </form>
                    <div class="btn_otpr_div">
                        <a href="https://place-start.ru/" class="href_btn">
                            <button class="btn_otpr">Отправить</button>
                        </a>
                        <p class="soglasie">Нажимая кнопку, Вы
                            соглашаетесь на <span class="pers_dan">обработку</span>
                            <span class="pers_dan">персональных данных</span>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <footer>
        <div class="container">
            <div class="footer_div">
                <a href="./index.html" class="footer_logo">
                    <img src="logo.png">
                </a>
                <div class="ssylki">
                    <a href="https://place-start.ru/">
                        <p class="o_kompanii_ftr">О компании</p>
                    </a>
                    <a href="https://place-start.ru/">
                        <p class="uslugi_ftr">Услуги</p>
                    </a>
                    <a href="https://place-start.ru/">
                        <p class="kontakty_ftr">Контакты</p>
                    </a>
                    <a href="https://place-start.ru/">
                        <p class="vakansii_ftr">Вакансии</p>
                    </a>
                </div>
                <div class="adress">
                    <p class="zag_adress_ftr">Адрес</p>
                    <p class="adress_ftr">160000, г.Вологда,
                        Пречистенская наб.,
                        д.72, оф. 1Н</p>
                    <p class="zag_rezhim_ftr">Режим работы</p>
                    <p class="rezhim_ftr">Пн — Пт
                        с 8:00 до 16:30</p>
                </div>
                <div class="numbers">

                    <p class="number_ftr">8 (8172) 50-35-32</p>
                    <div class="number_div_ftr">
                        <p class="number_ftr">+7 (911) 501-35-32</p>
                        <a href="https://place-start.ru/" class="href_whatsapp_viber">
                            <img src="whatsapp.png" class="whatsapp">
                        </a>
                        <a href="https://place-start.ru/" class="href_whatsapp_viber">
                            <img src="viber.png" class="viber">
                        </a>
                    </div>
                    <a href="mailto:ea503532@yandex.ru">
                        <p class="email_ftr"><u>ea503532@yandex.ru</u></p>
                    </a>
                </div>
            </div>
        </div>
        <div class="container_footer">
            <div class="container">
                <div class="prava">
                    <p class="kopyrait">© 2020 ООО «5С-Проект»</p>
                    <p class="politika"><u>Политика конфиденциальности</u></p>
                    <div class="sdelano_div">
                        <p class="sdelano">Сделано в</p>
                        <a href="https://place-start.ru/" class="footer_placestart_href">
                            <img src="PS.png" class="img_ps">
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </footer>


    <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
    <script>
        const swiper = new Swiper('.swiper', {
            // Optional parameters
            direction: 'horizontal',
            loop: true,


            // Navigation arrows
            navigation: {
                nextEl: '.swiper-button-next img',
                prevEl: '.swiper-button-prev img',
            },

        });
        const swiper2 = new Swiper('.second-swiper', {
            direction: 'horizontal',
            loop: true,
            spaceBetween: 10,

            // If we need pagination
            pagination: {
                el: '.swiper-pagination',
            },

            // Navigation arrows
            navigation: {
                nextEl: '.swiper-button-next',
                prevEl: '.swiper-button-prev',
            },

            // And if we need scrollbar
            scrollbar: {
                el: '.swiper-scrollbar',
            },

            // Media queries
            breakpoints: {
                768: {
                    slidesPerView: 3,
                },
            },
            slidesPerView: 1,
        });
    </script>
</body>

</html>
