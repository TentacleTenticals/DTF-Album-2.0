# DTF-Album-2.0

<p>Версия 1.2.2<ul>
<li>Поддержка Firefox браузера (по идее и остальных, работающих на его движке). Включается в cfg:browser:isFirefox:true</li>
<li>Фиксы z-index некоторых элементов.</li>
<li>Новые настройки</li>
<li>Чуть больше возможностей.</li>
<br>
<li>Чуть переписан режим зума.</li>
<li>1) Заместо процентного зума, зум идёт числовым значением.</li>
<li>2) В хромиум браузерах (Chrome, Chromium, Vivaldi, Opera, Yandex, и т.п) зум идёт через style.zoom.</li>
<li>3) В Firefox браузере зум идёт через transform.scale().</li>
<li>4) Зум теперь не требует наведения на изображение в режиме просмотра, но требует этого, если у Вас включена настройка smartZoom (о чём и сообщит оповещение).</li>
<li>5) Зум теперь возможен кнопками клавиатуры без зажимания "button1".</li>
<li>По-умолчанию, "E"/"Numpad+" (увеличение), "Q"/"Numpad-" (уменьшение)</li>
<li>6) Силу зума теперь можно менять в настройках. Лучше всего выбирать значения 0.10/0.15/0.20/0.25/и т.п.</li>
<br>
<li>Теперь возможен скролл кнопками клавиатуры.</li>
<li>Сила скролла меняется в cfg:scroll:scrollPower:</li>
<br>
<li>Настройки сменили название - теперь cfg заместо main.</li>
<li>Настройки клавиш перенесены (и добавлены новые) в cfg:buttons:</li>
</p></ul>
