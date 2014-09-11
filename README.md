Я сам переходил с SVN на GIT несколько лет назад и переводил других разработчиков. За это время у меня сформировалось понимание, что теория, книжка, google/stackoverflow - это хорошо, но есть нюанс. 

<b>“Чем отличается теория от практики? В теории - ничем! На практике все немного не так.”</b>
<ul>

	<li>Читать что “ветки - это круто” - это одно, а вот перестать бояться делать ветки — другое;</li>
	<li>Иметь возможность делать локальные коммиты — это одно, а делать их в реальности — совсем другое;</li>
	<li>Кто-то знает как использовать в теории, но на практике не делал и поэтому и не использует;</li>
	<li>Кто-то просто не знает, а чего не знаешь, то и не используешь.</li>
</ul>

Именно по этому, я написал Git Quiz для своих коллег — чтобы люди привыкли использовать git, как git, а не как svn; чтобы у разработчиков сформировалась мышечная память, чтобы теория стала практикой.

Особенность quiz в том, что это не учебник, не тест с вариантами ответа или без них. <b>GIT Quiz — это мини лабораторная работа.</b> Время прохождения теста 15-45 минут.

Всего 19 последовательных шагов. У каждого шага есть:
<ol>
	<li>Описание что нужно сделать по задаче;</li>
	<li>Версия репозитория до шага;</li>
	<li>Версия репозитория после шага;</li>
	<li>Скриншот после выполнения шага;</li>
	<li>Видео - как сделать задачу.</li>
</ol>
<b>Сами задачки - это пошаговое выполнение разработки по gitflow с использование git.</b>
Ссылка на проект в <a href="https://github.com/SychevIgor/git_quiz">github</a> 
<habracut text="Подробнее..." />

Все действия предполагается выполнять в локальном репозитории, без наличия сервера (push-pull). Причины простые:
<ul>
	<li>Так проще для начала (не нужно настраивать сервер);</li>
	<li>Этого достаточно, чтобы начать работать с git;</li>
	<li>Quiz будет продолжен и расширен серверными шагами.</li>
</ul>

<spoiler title="Так выглядит весь список задач:"><img src="http://habrastorage.org/getpro/habr/post_images/192/5de/4b7/1925de4b7e02322115c98609662eb9dd.jpg"/></spoiler>

<h5>Пример задачи</h5>
<h6>Шаг 4</h6>
<spoiler title="Структура в файловой системе">
<img src="http://habrastorage.org/getpro/habr/post_images/92b/cc6/39c/92bcc639c0aefb4bc0f880d28efd62af.jpg"/>
</spoiler>
<spoiler title="Текст задачи">
<img src="http://habrastorage.org/getpro/habr/post_images/ea6/11b/1ea/ea611b1eab6323bb32dd7a13998dabfc.jpg"/>
</spoiler>
<spoiler title="Репозитарий до выполнения задания">
<img src="http://habrastorage.org/getpro/habr/post_images/de3/d98/742/de3d98742ec5cc916a33278be920b3b5.jpg"/>
</spoiler>
<spoiler title="Репозитарий после выполнения задания">
<img src="http://habrastorage.org/getpro/habr/post_images/82e/516/1e4/82e5161e48020fecbad1bf14a88ae042.png"/>
</spoiler>
<spoiler title="Видео- как сделать в gitextensions">
<img src="http://habrastorage.org/getpro/habr/post_images/b49/a5a/e73/b49a5ae7393e35b83f39cb330660de3a.jpg"/>
</spoiler>

<h5>Результат тестирования на коллегах:</h5>
<ul>
	<li>Я тест прошел за 15 минут. У меня 1.5 года опыта работы с git + тест я же и создал.</li>
	<li>Коллега, который всю жизнь писал на svn и последний месяц потихоньку работал с git (использовал git как svn-> commit/push одной кнопкой). Ему потребовалось 45 минут. После прохождения он стал увереннее пользоваться git.</li>
	<li>Второй коллега, который всю жизнь работал с svn, и 1 день разбирался "что такое git" сказала, "классный тест, стало понятнее. Нужно еще работа с сервером правда."</li>
</ul>

<h5>Вопросы:</h5>
<ul>
	<li><b>Почему я не стал работать из консоли?</b> Во-первых, я сам ей редко пользуюсь, во-вторых, в мне UI нагляднее. Для тех, кто готов не просто упрекнуть меня в ереси за работу не из консоли- помогите проекту и снимите видео работы из консоли. Задача такая <a href="https://github.com/SychevIgor/git_quiz/issues/4">есть</a>.  </li>
	<li><b>Почему я работал через gitextensions?</b> Tortoise git мне не нравится по субъективным причинам. Клиент из Visual Studio — это сразу привязка к Microsoft. Smartgit — штука хорошая, но тащит за собой java + для коммерческого использования платная. Если есть желающие помочь, можно снять видео по выполнению задач через SmartGit тк <a href="https://github.com/SychevIgor/git_quiz/issues/5">задачка </a>такая есть. Другими клиентами не довелось пользоваться. Тк в комментариях много плюсов набрал Atlassian SourceTree, то <a href="https://github.com/SychevIgor/git_quiz/issues/6">задачу </a>на съемку видео завел к этому клиенту.</li>
	<li><b>Почему без звука </b>— в следующей версии, если окажется полезным добавлю описание того, что я делаю.</li>
</ul>

<b>Буду рад фидбеку, если кто-то готов дополнить примеры и записать видео, то буду вдвойне счастлив.</b>


P.S.
Часть по работе с сервером, тоже пока в стадии формирования. Тут есть момент, что людей много может быть, и создать вот так же просто папку с примерами на флешке не получится. Из разных шагов не последовательно на сервер не сделаешь push/pull/fetch. Если мысли на тему сделать все в виде виртуалки и выдавать ее всем, но там начинаются свои проблемы.

Благодарности: 

Пользователю https://github.com/ewancoder за перекодировку файлов в utf-8. https://github.com/SychevIgor/git_quiz/issues/2 

