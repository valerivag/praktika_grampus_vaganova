<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter&display=swap" rel="stylesheet">
    <link rel="icon" href="img/Favicon.png">

    <title>отопительное оборудование</title>
</head>
<body>
    <header>
        <div id="header_section"> 
        <div id="header_section1">
             ОТОПИТЕЛЬНОЕ <br> ОБОРУДОВАНИЕ
        </div>
        <div id="header_section2">
            <div > 
            <a class="header_navi_a" href="https://grampus-studio.ru/"> Выгодно  </a>
            <a class="header_navi_a" href="https://grampus-studio.ru/"> Услуги и товары  </a>
            <a class="header_navi_a" href="https://grampus-studio.ru/"> Контакты  </a>
            <a class="header_navi_a" href="https://grampus-studio.ru/"> Еще <img src="img/Vector 1.png"> </a>
            </div>
            <div class="header_navi_icon">
             <a href="https://grampus-studio.ru/">   <img id="icon" src="img/mingcute_telegram-fill.png"></a>
             <a href="https://grampus-studio.ru/"> <img src="img/ri_whatsapp-fill.png"></a>
            </div>
            <div class="header_navi_telefon">
                +7 (999) 123-45-67
            </div>
        </div>
        <div id="header_section3">
            <a href="https://grampus-studio.ru/"> 
            <button id="btn_header">
                Обратный звонок
            </button>
        </a>
        </div>
    </div>
    </header>
    <div class="section">
        <div class="body_section1">
            
            <div class="Bsec1_box">
                <div class="Bsec1_box_text">
                    <div id="box_text1">
                        Установка и обслуживание <span id="text1">отопительного оборудования </span> в Москве

                    </div>
                    <div id="box_button1">
                        <div class="sec1_button">
                            <button id="btn_sec1_presentation">Профессионализм</button>
                            <button id="btn_sec1_presentation">Честность</button>
                        </div>
                        <div class="sec1_button">
                            <button id="btn_sec1_presentation">Открытость</button>
                            <button id="btn_sec1_presentation">Инновационность</button>
                        </div>
                    </div>
                </div>
                <div id="ot"></div>
                <div class="Bsec1_svyaz">
                    <div id="Bsec1_svyaz1">
                        <a href="https://grampus-studio.ru/"> 
                        <button id="Bsec1_svyaz1_btn">
                            Оставить заявку
                        </button>
                        </a>
                    </div>
                    <div id="Bsec1_svyaz2">
                        <img id="strelaLeft" src="img/Стрелка для слайдера.png"  onclick="showSlide(currentSlide - 1)">
                        <div class="dots">
                            <span class="dot" onclick="showSlide(0)"></span>
                            <span class="dot" onclick="showSlide(1)"></span>
                            <span class="dot" onclick="showSlide(2)"></span>
                        </div>
                        <img src="img/Union.png" id="strelaRight" onclick="showSlide(currentSlide + 1)" >
                    </div>
                </div>
            </div>
            <script>
             let currentSlide = 0;

    const slides = [
        {
            text: "Установка и обслуживание <span id='text1'>отопительного оборудования</span> в Москве", // Обернули текст в span
            image: "img/Фото.png"
        },
        {
            text: "Профессионализм и качество обслуживания",
            image: "img/Фото_oKompanii.png"
        },
        {
            text: "Инновационные решения для вашего дома",
            image: "img/Фото.png"
        }
    ];

    function showSlide(index) {
        if (index >= slides.length) {
            currentSlide = 0;  
        } else if (index < 0) {
            currentSlide = slides.length - 1;  
        } else {
            currentSlide = index;  
        }

        
        document.getElementById('box_text1').innerHTML = slides[currentSlide].text;

        document.getElementById('slideImage').src = slides[currentSlide].image;

        updateDots();
    }

    function updateDots() {
        const dots = document.querySelectorAll('.dot');
        
        dots.forEach((dot, index) => {
            dot.classList.remove('active');
            if (index === currentSlide) {
                dot.classList.add('active');
            }
        });
    }

    
    showSlide(currentSlide);
            </script>
            <div class="Bsec1_box">
                <img id="slideImage" src="img/Фото.png">
            </div>
        </div>
        <div class="body_section2">
            <div class="image-container_section2 ">
                <img src="img/Баннер.png" alt="Баннер">
                <a href="https://grampus-studio.ru/"> 

                <button class="button_section2">Заказать услугу</button>
                </a>
            </div>
        </div>
        <div class="section">
        <div class="body_section3">
            <div id="section_h2"><span id="text1">Услуги и товары</span> нашей компании</div>
            <div class="section3">
                <div class="section3_uslugi">
                    <div class="usluga">
                        <div class="usluga_zagolovok">
                            <div class="zagolovok_name">
                                Проектирование, монтаж,<br> сервисное обслуживание систем<br> отопления и водоснабжения
                            </div>
                            <div class="zagolovok_cena">
                                от 50 000 руб
                            </div>
                        </div>
                        <div class="usluga_GLrazdel">
                            <div class="usluga_opisanie">
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">   Проектирование 
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">   Монтаж 
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">   Сервисное обслуживание 
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">   Любой масштаб 
                                </div>
                                <div id="btn_zu"> 
                                    <a href="https://grampus-studio.ru/"> 
                                <button id="Zakaz_uslugibtn"> Заказать услугу</button>
                                    </a>
                            </div>
                            </div>
                            <div class="usluga_foto">
                                <img src="img/usluga1.png">
                            </div>
                        </div>
                    </div>
                    <script>
                        function toggleItems() {
                    const hiddenItems = document.getElementById('hiddenItems');
                    const toggleText = document.getElementById('Otkit_eche');

                   
                    if (hiddenItems.style.display === 'none') {
                        hiddenItems.style.display = 'block';  
                        toggleText.innerHTML = 'Скрыть <img src="img/Line 1.png" id="line">';  
                    } else {
                        hiddenItems.style.display = 'none';  
                        toggleText.innerHTML = 'Открыть еще <img src="img/Line 1.png" id="line">';  
                    }
                }
                    </script>
                    <div class="usluga">
                         <div class="usluga_zagolovok">
                            <div class="zagolovok_name">
                                Установка<br> автоматики
                            </div>
                            <div class="zagolovok_cena">
                                от 50 000 руб

                            </div>
                        </div>
                        <div class="usluga_GLrazdel" id="razdel2">
                            <div class="usluga_opisanie">
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">   Для систем водоснабжения 
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">   Для отопления 
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">   Для систем водоснабжения в<br> частных домах 
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">   Для систем водоснабжения в многоквартирных домах 
                                </div>
                                <div id="hiddenItems" style="display: none;">
                                    <div id="opisanie_usl">
                                        <img id="punkt" src="img/-.png"> Для систем отопления в <br>многоквартирных домах
                                    </div>
                                    <div id="opisanie_usl">
                                        <img id="punkt" src="img/-.png"> Для любых <br>высоконагруженных систем
                                    </div>
                                    
                                </div>
                                 
                                <div id="opisanie_usl">
                                     <div id="Otkit_eche" onclick="toggleItems()">Открыть еще
                                        <img src="img/Line 1.png" id="line">
                                     </div>
                                </div>
                                <div id="btn_zu2"> 
                                    <a href="https://grampus-studio.ru/"> 
                                    <button id="Zakaz_uslugibtn"> Заказать услугу</button>
                                    </a>
                                </div>
                            </div>
                            <div class="usluga_foto">
                                <img src="img/usluga2.png">
                            </div>
                        </div>
                    </div>
                </div>
                <div class="uslugi_otst"> 
                <div class="section3_uslugi">
                    <div class="usluga">
                        <div class="usluga_zagolovok">
                            <div class="zagolovok_name">
                                Промывка систем <br>отопления
                            </div>
                            <div class="zagolovok_cena">
                                от 50 000 руб

                            </div>
                        </div>
                        <div class="usluga_GLrazdel">
                            <div class="usluga_opisanie">
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">  Качественно
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">   В день обращения
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">   В частных и многоквартирных<br> домах
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">  С помощью современного<br> немецкого оборудования
                                </div>
                                <div id="hiddenItems" style="display: none;">
                                    <div id="opisanie_usl">
                                        <img id="punkt" src="img/-.png"> Для систем отопления в <br>многоквартирных домах
                                    </div>
                                    
                                    
                                </div>
                                 
                                <div id="opisanie_usl">
                                     <div id="Otkit_eche" onclick="toggleItems()">Открыть еще
                                        <img src="img/Line 1.png" id="line">
                                     </div>
                                </div>
                                <div id="btn_zu3"> 
                                    <a href="https://grampus-studio.ru/"> 
                                    <button id="Zakaz_uslugibtn"> Заказать услугу</button>
                                    </a>
                                </div>

                            </div>
                            <div class="usluga_foto">
                                <img src="img/usluga3.png">
                            </div>
                        </div>
                    </div>
                    <div class="usluga">
                        <div class="usluga_zagolovok">
                            <div class="zagolovok_name">
                                Ремонт оборудования
                            </div>
                            <div class="zagolovok_cena">
                                от 50 000 руб

                            </div>
                        </div>
                        <div class="usluga_GLrazdel">
                            <div class="usluga_opisanie">
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">  Котлы
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">  Насосные станции
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">  Системы автоматики
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">  Иное оборудование
                                </div>
                                <div id="btn_zu"> 
                                    <a href="https://grampus-studio.ru/"> 
                                    <button id="Zakaz_uslugibtn"> Заказать услугу</button>
                                    </a>
                                </div>
                            </div>
                            <div class="usluga_foto">
                                <img src="img/usluga4.png">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
                <div class="section3_uslugi">
                    <div class="usluga2">
                        <div class="usluga_zagolovok2">
                            <div class="zagolovok_name">
                                Продажа оборудования
                            </div>
                            <div class="zagolovok_cena">
                                от 500 руб

                            </div>
                        </div>
                        <div class="usluga_GLrazdel2">
                            <div class="usluga_opisanie">
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">  Газовые котлы
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">  Электрические котлы
                                </div>
                                <div id="opisanie_usl">
                                    <img id="punkt" src="img/-.png">  Расходные материалы и комплектующие
                                </div>
                                
                                 
                                <div id="btn_zu4"> 
                                    <a href="https://grampus-studio.ru/"> 
                                    <button id="Zakaz_uslugibtn"> Заказать услугу</button>
                                    </a>
                                </div>

                            </div>
                            <div class="usluga_foto2">
                                <img src="img/usluga5.png">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        </div>
        <div class="body_section4">
            <div id="section_h2">
                О <span id="text1">компании</span> 
            </div>
            <div class="section4_slideshow">
                <div class="section4_foto">
                    <div class="slide_Foto" id="slide1">
                        <img src="img/Фото_oKompanii.png" alt="Слайд 1">
                    </div>
                    <div class="slide_Foto" id="slide2" style="display: none;">
                        <img src="img/rabota2sl.png" alt="Слайд 2">
                    </div>
                    <div class="slide_Foto" id="slide3" style="display: none;">
                        <img src="img/rabota1sl.png" alt="Слайд 3">
                    </div>
                    <div class="slide_strelki">
                        <img id="strelaLeft2" src="img/Стрелка для слайдера.png" onclick="changeCompanySlide(-1)"  >
                        <div class="dot_box"> 
                        <div class="dots2">
                            <span class="dot2" onclick="showCompanySlide(0)" ></span>
                            <span class="dot2" onclick="showCompanySlide(1)" ></span>
                            <span class="dot2" onclick="showCompanySlide(2)"></span>
                        </div>
                    </div>
                        <img src="img/Union.png" id="strelaRight2"   onclick="changeCompanySlide(1)">
                    </div>
                </div>
                <div class="section4_information">
                     <div class="section4_information_text" id="infoText">
                        
                     </div>
                     <div class="section4_information_counts">
                        <div class="section4_information_count">
                            <hr class="section4_hr">
                            <div class="section4_number">
                                1998
                            </div>
                            <div class="section4_podpis">
                                год основания компании
                            </div>
                        </div>
                        <div class="section4_information_count">
                            <hr class="section4_hr">
                            <div class="section4_number">
                                12
                            </div>
                            <div class="section4_podpis">
                                квалифицированных<br> инженеров в команде
                            </div>
                        </div>
                        <div class="section4_information_count">
                            <hr class="section4_hr">
                            <div class="section4_number">
                                100
                            </div>
                            <div class="section4_podpis">
                                довольных клиентов
                            </div>
                        </div>
                     </div>
                </div>
                <script>
                              let currentCompanySlide = 0;  
            const companySlides = document.querySelectorAll('.slide_Foto');  
            const companyTexts = [
                `<p>Не каждый уделяет монтажу системы отопления достаточно внимания.</p>
                 <p>Это приводит к отказам оборудования, проблемам с пуском в начале сезона и другим проблемам, которых можно избежать.</p>
                 <p>Составлением проекта, установкой и наладкой (всем, что связано с коммуникациями) должны заниматься исключительно профессионалы.</p>
                 <p>А проводить монтаж систем отопления квалифицированный персонал. Независимо от объекта.</p>
                 <p>Качественный монтаж, точно в срок. Мы исключили всех посредников, чтобы предоставить одни из лучших цен. Квалифицированные славянские рабочие.</p>`,
                
                "Текст 2",
                "Текст 3"
            ];
            function changeCompanySlide(direction) {
                
                companySlides[currentCompanySlide].style.display = 'none';
                
               
                currentCompanySlide += direction;

                 
                if (currentCompanySlide < 0) {
                    currentCompanySlide = companySlides.length - 1;  
                } else if (currentCompanySlide >= companySlides.length) {
                    currentCompanySlide = 0; 
                }

                 
                companySlides[currentCompanySlide].style.display = 'block';

               
                document.getElementById('infoText').innerHTML = companyTexts[currentCompanySlide];  

                 
                updateDots();
            }

            function updateDots() {
                const dots = document.querySelectorAll('.dot2');
                
                dots.forEach((dot, index) => {
                    dot.classList.remove('active');  
                    if (index === currentCompanySlide) {
                        dot.classList.add('active');  
                    }
                });
            }

            function showCompanySlide(index) {
                changeCompanySlide(index - currentCompanySlide); 
            }

            
            changeCompanySlide(0);
                </script>
            </div>
        </div>
            <div class="sec1_button4_end"></div>
        </div>
        <div class="body_section5">
            <div class="section5">
                <div class="section5_etapi">
                    <div class="box_sec5"> 
                    <div class="section5_etapi_text">
                        <div class="section5_h1">
                            Этапы работы с нами
                        </div>
                        <div class="section5_vse_etapi">
                            <div class="etapi_img">
                                <img src="img/etap_img.jpg"  height="378">
                            </div>
                            <div class="etapi_text">
                                <div class="box_etapi_text">
                                    <div class="etapi_h">
                                        01. Созваниваемся и знакомимся
                                    </div>
                                    <div class="etapi_p">
                                        Вы оставляете заявку любым удобным способом, наш менеджер <br> свяжется с вами.
                                    </div>
                                </div>
                                    <div class="box_etapi_text">
                                    <div class="etapi_h">
                                        02. Составляем смету
                                    </div>
                                    <div class="etapi_p">
                                        Рассчитываем и согласовываем смету, готовим и подписываем<br> договор.
                                    </div>
                                </div>
                                <div class="box_etapi_text">
                                    <div class="etapi_h">
                                        03. Выполняем работы
                                    </div>
                                    <div class="etapi_p">
                                        Вы можете участвовать на любом этапе работы для личного<br> контроля, а также будете получать ежедневные отчеты.
                                    </div>
                                </div>
                                <div class="box_etapi_text"> 
                                    <div class="etapi_h">
                                        04. Сдаем работы
                                    </div>
                                    <div class="etapi_p">
                                        Осуществляем приемку-передачу. На этом этапе вы можете<br> приглашать для проверки любых сторонних экспертом.
                                    </div>
                                </div>
                                 
                            </div>
                        </div>
                        <a href="https://grampus-studio.ru/"> 
                        <button class="section5_btn">Заказать услугу</button>
                        </a>
                    </div>
                    <div class="section5_etapi_foto">
                        <img src="img/etapi.png">
                    </div>
                </div>
                </div>
            </div>
        </div>
         <div class="section">
            <div class="body_section6">
                <div class="section6_h">
                    Наша<br> <span id="text1">команда</span>  
                </div>
                <div class="section6_sotrudniki">
                    <div class="section6_sotrudniki_name">
                        <div class="section6_sotrudnik_Fio">
                            Зарубин Андрей Андреевич
                        </div>
                        <div class="section6_sotrudnik_doljnost">
                            главный инженер
                        </div>
                        <div class="section6_sotrudnik_foto">
                            <img src="img/sotrudnik1.png">
                        </div>
                        <div class="section6_sotrudniki_all">
                            <a href="https://grampus-studio.ru/" id="a">  <div id="Otkit_eche2" > Показать всех
                                <img src="img/Line 1.png" id="linee">
                             </div></a>
                        </div>
                    </div>


                    <div class="section6_sotrudniki_name">
                        <div class="section6_sotrudnik_Fio">
                            Иванов Александр Викторович
                        </div>
                        <div class="section6_sotrudnik_doljnost">
                            заместитель главного инженера
                        </div>
                        <div class="section6_sotrudnik_foto">
                            <img src="img/sotrudnik2.png">
                        </div>
                    </div>


                    <div class="section6_sotrudniki_name">
                        <div class="section6_sotrudnik_Fio">
                            Волков Валентин <br> Иванович
                        </div>
                        <div class="section6_sotrudnik_doljnost">
                            мастер-сметчик
                        </div>
                        <div class="section6_sotrudnik_foto">
                            <img src="img/sotrudnik3.png">
                        </div>
                    </div>
                </div>
            </div>

            <div class="body_section7">
                <div class="section7_h">
                    Отзывы и благодарности <span id="text1">клиентов</span>  
                </div>
                <div class="section7_slideshow">
                    <div class="section7_slideshow_otzyvi">
                        <div class="section7_slideBox1">
                            <img src="img/Видео.png" id="slidebox_foto">
                            <div class="slideBox1_text1">
                                ООО «Агрокомплекс», владелец компании Сармат Алиев
                            </div>
                            <div class="slideBox1_text2">
                                Проект: Промышленная система теплохолодоснабжения
                            </div>
                        </div>


                        <div class="section7_slideBox2">
                            <div class="slideBox_avatar">
                                <div class="slideBox_avatar_foto">
                                <img src="img/avatar.png">
                                </div>
                                <div class="slideBox_avatar_text">
                                    <div class="slideBox1_text1">
                                        Александр Рыбаков
                                     </div>
                                    <div class="slideBox1_text2">
                                        Проект: Отопление загородного дома “под ключ”
                                    </div>
                                </div>
                            </div>
                            <div class="slidebox_otzv">
                                «Компания выполнила работу на отличном уровне. Работники были
                                 профессиональны и внимательно относились к каждой детали. Результат 
                                 работы полностью оправдал мои ожидания — теперь в доме очень комфортно 
                                 и тепло. Спасибо за качественное выполнение услуги!»
                            </div>
                            <div class="slidebox_otzv_foto">
                                <div class="image_container_otzv" >
                                    <img src="img/otzv.png"  >
                                    <div class="overlay_icon">
                                        <img src="img/Lupa.png" >
                                    </div>
                                     
                                </div>
                                <div class="image_container_otzv">
                                    <img src="img/otzv2.png"  >
                                    <div class="overlay_icon">
                                        <img src="img/Lupa.png" >
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="slide_strelki" id="strl">
                        <img id="strelaLeft3" src="img/Стрелка для слайдера.png"  onclick="changeReviewSlide(-1)"  >
                        <div class="dot_boxx"> 
                        <div class="dots2">
                            <span class="dot2"  onclick="showReviewSlide(0)" ></span>
                            <span class="dot2"  onclick="showReviewSlide(1)" ></span>
                            <span class="dot2" onclick="showReviewSlide(2)" ></span>
                        </div>
                    </div>
                        <img src="img/Union.png" id="strelaRight3"  onclick="changeReviewSlide(1)"  >
                    </div>
                </div>
            </div>
            <div class="body_section8">
                <div class="section7_h">
                    Выполненные <span id="text1">работы</span> 
                </div>
                <div class="section8_Show">
                    <div class="First_work">
                        <div class="section8_foto">
                            <img src="img/rabota1.png">
                        </div>
                        <div class="work_name">
                            Система воздушного отопления с автоматизацией и диспетчеризацией
                        </div>
                        <div class="work_info">
                            <div class="work_adres">
                                <img src="img/skobkaVerh.png">
                                <div class="adres_icon">
                                    <img src="img/adr.png" id="adr">  Щелковский район
                                </div>
                                <img src="img/skobkaNiz.png">
                            </div>
                            <div class="work_year">
                                
                                <img src="img/skobkaVerh.png" id="sk1">
                                <div class="year_icon">
                                    <img src="img/year.png" id="yer"> Май 2023 года
                                </div>
                                <img src="img/skobkaNiz.png" id="sk1">
                            </div>
                        </div>
                    </div>
                    <div class="second_work">
                        <div class="section8_foto">
                            <img src="img/rabota2.png">
                        </div>
                        <div class="work_name">
                            Промышленная система теплохолодоснабжения (VRF системы, канальные электрические нагреватели)
                        </div>
                        <div class="work_info">
                            <div class="work_adres">
                                <img src="img/skobkaVerh.png" id="sk2">
                                <div class="adres_icon">
                                    <img src="img/adr.png" id="adr"> Мытищи
                                </div>
                                <img src="img/skobkaNiz.png" id="sk2">
                            </div>
                            <div class="work_year">
                                
                                <img src="img/skobkaVerh.png">
                                <div class="year_icon">
                                    <img src="img/year.png" id="yer">Ноябрь 2022 года
                                </div>
                                <img src="img/skobkaNiz.png">
                            </div>
                        </div> 
                    </div>
                </div>
                <div class="slide_strelki" id="strl">
                    <img id="strelaLeft3" src="img/Стрелка для слайдера.png"  onclick="changeReviewSlide(-1)"  >
                    <div class="dot_boxx"> 
                    <div class="dots2">
                        <span class="dot2"  onclick="showReviewSlide(0)" ></span>
                        <span class="dot2"  onclick="showReviewSlide(1)" ></span>
                        <span class="dot2" onclick="showReviewSlide(2)" ></span>
                    </div>
                </div>
                    <img src="img/Union.png" id="strelaRight3"  onclick="changeReviewSlide(1)"  >
                </div>
            </div>
            <div class="body_section9">
                <div class="section7_h">
                    Сертификаты   <span id="text1">качества</span> 
                </div>
                <div class="section9_sertificate">
                    <div class="section9_sertificate_name">
                         
                    <div class="section9_box active">
                        <div class="section9_box_name">
                            Сертификат официального дилера ZOTA
                        </div>
                        <div class="section9_box_date">
                            от 14 ноября 2019 года
                        </div>
                        <hr class="section9_hr">
                    </div>
                    
                    <div class="section9_box">
                        <div class="section9_box_name">
                            Сертификат официального дилера ТЕПЛОДАР
                        </div>
                        <div class="section9_box_date">
                            от 12 мая 2021 года
                        </div>
                        <hr class="section9_hr">
                    </div>

                    
                    <div class="section9_box">
                        <div class="section9_box_name">
                            Сертификат официального дилера СТЭН
                        </div>
                        <div class="section9_box_date">
                            от 2 апреля 2022
                        </div>
                        <hr class="section9_hr">
                    </div>

                    
                    <div class="section9_box">
                        <div class="section9_box_name">
                            Сертификат официального дилера ТЕПЛОДАР
                        </div>
                        <div class="section9_box_date">
                            от 2 апреля 2022
                        </div>
                        <hr class="section9_hr">
                    </div>

                    
                    <div class="section9_box">
                        <div class="section9_box_name">
                            Сертификат официального дилера СТЭН
                        </div>
                        <div class="section9_box_date">
                            от 2 апреля 2022
                        </div>
                        <hr class="section9_hr">
                    </div>

                    
                    <div class="section9_box">
                        <div class="section9_box_name">
                            Сертификат официального дилера ZOTA
                        </div>
                        <div class="section9_box_date">
                            от 2 апреля 2022
                        </div>
                        <hr class="section9_hr">
                    </div>
                    <div class="pokazat_echee">
                        <a href="https://grampus-studio.ru/" id="a">  <div id="Otkit_eche2" > Показать ещё
                        <img src="img/Line 1.png" id="linee">
                     </div>
                    </a>
                    </div>
                     

                    </div>
                    <div class="section9_sertificate_foto">
                        <div class="sert_foto_container" style="margin-left: 130px;">
                            <img src="img/Group 2.png" id="sert_foto">
                            <div class="overlay_icon_sert_foto">
                                <img src="img/Lupa.png">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <script>
                document.querySelectorAll('.section9_box').forEach(box => {
                    box.addEventListener('click', function() {
                    // Удалить активный класс со всех элементов
                    document.querySelectorAll('.section9_box').forEach(item => item.classList.remove('active'));
                    
                    // Добавить активный класс текущему элементу
                    this.classList.add('active');
                    });
                    });
             </script>
             <div class="ot"></div>
         </div>
         <div class="body_section10">
            <div class="section10">
                <div class="section10_voprosi">
                    <div class="section10_h">
                        Остались вопросы?
                    </div>
                    <div class="section10_text">
                        Мы готовы ответить на любой их них, оставьте свои <br>данные и мы перезвоним
                    </div>
                    <div class="section10_foto">
                        <img src="img/voprosi.png" height="242" width="470">

                    </div>
                </div>

                <div class="section10_forma">
                    <div class="name_input">
                        Имя
                    </div>
                    <input type="text" class="input" placeholder="Александр">

                    <div class="name_input" id="last_nameinput">
                        Номер телефона*
                    </div>
                    <input type="text" class="input" placeholder="+7 (___)___-__-__">
                    <div class="forma_soglasie">
                        *Нажимая на кнопку, Вы соглашаетесь <br> <u>на обработку персональных данных</u>
                    </div>
                    <a href="https://grampus-studio.ru/" id="a">
                        <button class="btn_forma">Отправить</button>
                    </a>
                </div>
            </div>
         </div>
         <div class="ots"></div>
         <div class="section">
            <div class="body_section11">
                <div class="section7_h">
                    <span id="text1">Связаться</span>  с нами    
                </div>
                <div class="section11_kontakti">
                    <div class="section11_kontakti_box">
                        <div class="kontakti_name">
                            [Телефон]
                        </div>
                    <div class="kontakti_opisanie">
                        <div class="kont_t">
                            +7 (999) 123-45-67
                        </div>
                        <div class="kont_time">
                            Пн-пт: с 8:00 до 17:00
                        </div>
                    </div>
                    </div>

                    <div class="section11_kontakti_box">
                    <div class="kontakti_name">
                        [Соцсети]
                        </div>
                        <div class="kontakti_opisanie">
                            <div class="kont_2">
                                <img src="img/tg.png" width="28" height="24" id="tg">
                                <img src="img/wat.png" width="24" height="24">
                            </div>
                            <div class="kont_time">
                                В любое время
                            </div>
                        </div>
                    </div>

                    <div class="section11_kontakti_box">
                        <div class="kontakti_name">
                            [Адрес]
                        </div>
                        <div class="kontakti_opisanie2">
                        <div class="opisanie_adres">
                            Московская область<br><span id="text1"> 
                                г. Видное, Бульвар Зеленые Аллеи, <br>
                                д. 11</span>
                        </div>
                        <div class="kont_time">
                            Пн-пт: с 8:00 до 17:00
                        </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="karta">
                <div style="position:relative;overflow:hidden;"><a href="https://yandex.ru/maps/10719/vidnoe/?utm_medium=mapframe&utm_source=maps" 
                    style="color:#eee;font-size:12px;position:absolute;top:0px;">Видное</a><a href="https://yandex.ru/maps/10719/vidnoe/house/bulvar_zelyonyye_allei_11/Z04YcQdnQUYCQFtvfXl3cXlkZA==/?ll=37.707835%2C55.560571&utm_medium=mapframe&utm_source=maps&z=16"
                     style="color:#eee;font-size:12px;position:absolute;top:14px;">Бульвар Зелёные Аллеи, 11 — Яндекс Карты</a>
                     <iframe src="https://yandex.ru/map-widget/v1/?ll=37.707835%2C55.560571&mode=search&ol=geo&ouri=ymapsbm1%3A%2F%2Fgeo%3Fdata%3DCgoxNjM0MTgwNTcwEp8B0KDQvtGB0YHQuNGPLCDQnNC-0YHQutC-0LLRgdC60LDRjyDQvtCx0LvQsNGB0YLRjCwg0JvQtdC90LjQvdGB0LrQuNC5INCz0L7RgNC-0LTRgdC60L7QuSDQvtC60YDRg9CzLCDQktC40LTQvdC-0LUsINCx0YPQu9GM0LLQsNGAINCX0LXQu9GR0L3Ri9C1INCQ0LvQu9C10LgsIDExIgoN0tQWQhUGPl5C&z=16"
                     width="1920" height="500" frameborder="1" allowfullscreen="true" style="position:relative;"></iframe></div>
            </div>
            <div class="foot">
                <div class="foot_name">
                    ОТОПИТЕЛЬНОЕ <br> ОБОРУДОВАНИЕ
                </div>
                <div class="foot_btns">
                    <div class="foot_icon">
                        <a href="https://grampus-studio.ru/">   <img id="icon" src="img/mingcute_telegram-fill.png"></a>
                        <a href="https://grampus-studio.ru/"> <img src="img/ri_whatsapp-fill.png"></a>
                         
                    </div>
                    <a href="https://grampus-studio.ru/">
                <button id="btn_header">
                    Обратный звонок
                </button>
            </a>

                </div>
            </div>
            <footer>
                <div class="footer1">
                    <u id="fu">Политика конфиденциальности</u>
                </div>
                <div class="footer2">
                    <div id="fu2">Сайт разработан</div> 
                    <a href="https://grampus-studio.ru/"><img src="img/GRAMPUS.png" width="100" height="15"></a>
                </div>
                <div class="footer3" >
                    © 2024. ООО «Отопительное оборудование»
                </div>

            </footer>
         </div>
    
 </body>
</html>
