Здравствуйте!

Это Катерина из команды поддержки CS-Cart. 

Я пишу вам, чтобы сообщить вам о результатах SEO-аудита, который мы проводим для клиентов в рамках технической поддержки. Цель этого аудита состояла в том, чтобы выявить факторы, негативно влияющие на видимость вашего сайта в поисковых системах. Вот основные выводы и рекомендации:

<h2>Веб-сайт в результатах поиска.</h2>

Ваш сайт уже проиндексирован Google, и в индексе почти 1410 страниц. В результатах поиска ваш магазина выглядят хорошо, но есть некоторое количество страниц с длинным содержимым тега <b>title</b>. Вот примеры таких страниц:

https://clovermall.ru/zaschitnoe-steklo-dlya-ekrana-samsung-araree-by-kdlab-dlya-samsung-galaxy-m32-prozrachnaya-1sht.-gp-ttm325kdatr/
https://clovermall.ru/zaschitnoe-steklo-belkin-invisiglass-ultracurve-dlya-apple-iphone-11-pro-max-prozrachnaya-f8w944dsblk-apl/
https://clovermall.ru/steklo-ceramic-samsung-galaxy-a72-5g-protivoudarnoe-v-teh.upak.-v-komp.-25-sht-art.-012537-chernyy/
https://clovermall.ru/zaschitnoe-steklo-dlya-ekrana-redline-corning-chernyy-dlya-samsung-galaxy-s21-1sht.-ut000023709/
https://clovermall.ru/zaschita-ekrana-armor-pro-dlya-samsung-galaxy-a02-a02s-a12-m12-a03-a03s-a03-core-borasco/
https://clovermall.ru/zaschitnoe-steklo-dlya-ekrana-redline-chernyy-dlya-apple-iphone-x-xs-11-pro-3d-1sht-ut000012290/
https://clovermall.ru/zerkalnyy-fotoapparat-canon-eos-5d-mark-iv-chernyy-30.4mpix-3.2-1080p-4k-cf-li-ion-bez-obektiva/

В основном это страницы товаров. Так как в результатах поиска отображается только <a href="https://developer.mozilla.org/ru/docs/Web/HTML/Element/title" target="_blank">55-60 первых символов заголовка</a>, то часть заголовка, содержащая название товара, будет скрыта. 

В CS-Cart содержимое этого тега формируется автоматически, и длина заголовка зависит от вложенности категории, в которую входит товар. Для товаров с большой вложенностью категорий, мы можем изменить способ формирования содержимого тега <b>title</b>, чтобы в результате была более короткая строка. Для этого потребуется небольшая модификация. Пожалуйста, напишите мне, если вам это интересно.

<h2>Карта сайта</h2>

Файл <b>sitemap.xml</b> для вашего магазина отсутствует. Обычно рекомендуется иметь такой файл для ускорения процесса индексации. Вы можете создать файл <b>sitemap.xml</b>, используя встроенный модуль <a href="https://docs.cs-cart.com/latest/user_guide/addons/google_sitemap/set_google_sitemap.html">Google Sitemap</a>.

<h2>"Битые" ссылки</h2>

Страница https://clovermall.ru/sport-tovary-i-otdyh/ содержит ссылки, возвращающие ответ 404. Это ссылки в блоке с подкатегориями:

https://clovermall.ru/naushniki-i-garnitury/
https://clovermall.ru/stroitelnye-materialy/izolyacionnye-materialy/polikarbonat-ru/
https://clovermall.ru/wi-fi-tochki-dostupa/velotovary/
https://clovermall.ru/wi-fi-tochki-dostupa/trenazhery/
https://clovermall.ru/wi-fi-tochki-dostupa/vidy-sporta/
https://clovermall.ru/wi-fi-tochki-dostupa/zimniy-sport/


Рекомендую удалить такие ссылки.

<h2>Скорость работы сайта</h2>

Я проверила несколько страниц вашего магазина с помощью инструмента PageSpeed Insights. Вот средние результаты для трех разных типов страниц:

Домашняя страница: Десктоп — 84, Мобильный — 44
Страница категории: Десктоп — 80, Мобильный — 38
Страница продукта: Десктоп — 75, Мобильный — 32

Для ускорения загрузки страниц, рекомендую вам включить Gzip на сервере. Он поддерживается большинством браузеров и улучшает производительность веб-сайта за счет передачи сжатых файлов. Пожалуйста, обратитесь к администратору вашего серевера, чтобы включить Gzip.

Надеюсь, эта информация будет полезной. Пожалуйста, напишите, если возникнут какие-либо вопросы.