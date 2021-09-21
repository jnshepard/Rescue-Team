# Rescue-Team
Выбранное для тестирования ПО - Afterlife.
📁 Ссылка на скачивание: <font color="#337ab7">https://play.google.com/store/apps/details?id=com.StuckInTheLoopProductions.Afterlife&amp;hl=ru&amp;gl=US</font>

Состав команды:

- [Астафьева Жанна](https://github.com/jnshepard)
- [Воробьева Елизавета](https://github.com/Forrly)  
- [Воронцова Елизавета](https://github.com/lizyka)  

# Описание выбранного ПО&nbsp;

Afterlife – экшн-игра для мобильных устройств операционной системы Androd, разработанная в мае 2021 года в ходе участия в геймджеве Ludum Dare. Представляет собой простой в управлении кликер, где вы управляете душой человека после смерти в загробном мире. Поле игры – бесконечное пространство с рандомно генерируемыми препятствиями, которые игрок должен обходить или уничтожать. Управление выполнено следующим образом: прыжок и выстрел осуществляются путем нажатия на кнопку в правом нижнем углу экрана, передвижение влево-вправо – свайпом пальца по экрана в нужную сторону. В игре имеется меню следующих настроек: регулятор громкости звука, выбор качества графики. Также в Afterlife присутствует лидер-борд – таблица&nbsp;

# Диаграмма вариантов использования&nbsp;

![aFlQnp2Sf9M](https://user-images.githubusercontent.com/76455790/134154064-9f84cc5e-cfdd-46ee-987e-f189c0c3e372.jpg)


# Найденные методом черного ящика баги&nbsp;

**Баг №1**
В настройках не работает регулятор громкости – звук в игре воспроизводится либо на полной громкости, либо не воспроизводится вообще.

**Баг №**
<span style="color: rgb(0, 0, 0); font-family: -apple-system, BlinkMacSystemFont, Roboto, &quot;Helvetica Neue&quot;, Geneva, &quot;Noto Sans Armenian&quot;, &quot;Noto Sans Bengali&quot;, &quot;Noto Sans Cherokee&quot;, &quot;Noto Sans Devanagari&quot;, &quot;Noto Sans Ethiopic&quot;, &quot;Noto Sans Georgian&quot;, &quot;Noto Sans Hebrew&quot;, &quot;Noto Sans Kannada&quot;, &quot;Noto Sans Khmer&quot;, &quot;Noto Sans Lao&quot;, &quot;Noto Sans Osmanya&quot;, &quot;Noto Sans Tamil&quot;, &quot;Noto Sans Telugu&quot;, &quot;Noto Sans Thai&quot;, sans-serif, arial, Tahoma, verdana; font-size: 13px;">Если оружие персонажа лазер, то не игрок под собой не сломает землю, потому что пули летят в стенку, которая не ломается.</span>

**Баг №**
<span style="color: rgb(0, 0, 0); font-family: -apple-system, BlinkMacSystemFont, Roboto, &quot;Helvetica Neue&quot;, Geneva, &quot;Noto Sans Armenian&quot;, &quot;Noto Sans Bengali&quot;, &quot;Noto Sans Cherokee&quot;, &quot;Noto Sans Devanagari&quot;, &quot;Noto Sans Ethiopic&quot;, &quot;Noto Sans Georgian&quot;, &quot;Noto Sans Hebrew&quot;, &quot;Noto Sans Kannada&quot;, &quot;Noto Sans Khmer&quot;, &quot;Noto Sans Lao&quot;, &quot;Noto Sans Osmanya&quot;, &quot;Noto Sans Tamil&quot;, &quot;Noto Sans Telugu&quot;, &quot;Noto Sans Thai&quot;, sans-serif, arial, Tahoma, verdana; font-size: 13px;">В меню лидерборд выводится меньше людей чем заявлено – вместо 100 всего лишь 54.</span>

**Баг №**
<span style="color: rgb(0, 0, 0); font-family: -apple-system, BlinkMacSystemFont, Roboto, &quot;Helvetica Neue&quot;, Geneva, &quot;Noto Sans Armenian&quot;, &quot;Noto Sans Bengali&quot;, &quot;Noto Sans Cherokee&quot;, &quot;Noto Sans Devanagari&quot;, &quot;Noto Sans Ethiopic&quot;, &quot;Noto Sans Georgian&quot;, &quot;Noto Sans Hebrew&quot;, &quot;Noto Sans Kannada&quot;, &quot;Noto Sans Khmer&quot;, &quot;Noto Sans Lao&quot;, &quot;Noto Sans Osmanya&quot;, &quot;Noto Sans Tamil&quot;, &quot;Noto Sans Telugu&quot;, &quot;Noto Sans Thai&quot;, sans-serif, arial, Tahoma, verdana; font-size: 13px;">Приземление на противника – противник не получает урон, игрок не отталкивается.</span>

**Баг №**
<span style="color: rgb(0, 0, 0); font-family: -apple-system, BlinkMacSystemFont, Roboto, &quot;Helvetica Neue&quot;, Geneva, &quot;Noto Sans Armenian&quot;, &quot;Noto Sans Bengali&quot;, &quot;Noto Sans Cherokee&quot;, &quot;Noto Sans Devanagari&quot;, &quot;Noto Sans Ethiopic&quot;, &quot;Noto Sans Georgian&quot;, &quot;Noto Sans Hebrew&quot;, &quot;Noto Sans Kannada&quot;, &quot;Noto Sans Khmer&quot;, &quot;Noto Sans Lao&quot;, &quot;Noto Sans Osmanya&quot;, &quot;Noto Sans Tamil&quot;, &quot;Noto Sans Telugu&quot;, &quot;Noto Sans Thai&quot;, sans-serif, arial, Tahoma, verdana; font-size: 13px;">Если зажать стрельбу, игрок двигается вправо при прыжке.</span>

**Баг №**

<span style="color: rgb(0, 0, 0); font-family: -apple-system, BlinkMacSystemFont, Roboto, &quot;Helvetica Neue&quot;, Geneva, &quot;Noto Sans Armenian&quot;, &quot;Noto Sans Bengali&quot;, &quot;Noto Sans Cherokee&quot;, &quot;Noto Sans Devanagari&quot;, &quot;Noto Sans Ethiopic&quot;, &quot;Noto Sans Georgian&quot;, &quot;Noto Sans Hebrew&quot;, &quot;Noto Sans Kannada&quot;, &quot;Noto Sans Khmer&quot;, &quot;Noto Sans Lao&quot;, &quot;Noto Sans Osmanya&quot;, &quot;Noto Sans Tamil&quot;, &quot;Noto Sans Telugu&quot;, &quot;Noto Sans Thai&quot;, sans-serif, arial, Tahoma, verdana; font-size: 13px;">При вводе ника не всегда высвечивается ошибка с рекомендациями о написании имени. На видео показано, как надпись высвечивается лишь с четвертого нажатия</span>


https://user-images.githubusercontent.com/76455790/134153865-b0021e4a-ed71-4447-bd63-41ea5bc233eb.MP4


