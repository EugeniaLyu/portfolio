# Портфолио: инженер по тестированию

## Обо мне 

👋 Меня зовут Евгения и я начинающий тестировщик. <br>
Представляю вашему вниманию учебные проекты, которые я выполняла в процессе прохождения курса.
<br>

## Навыки и технологии
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg" title="Java" alt="Java" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="React" alt="React" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/spring/spring-original-wordmark.svg" title="Spring" alt="Spring" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/materialui/materialui-original.svg" title="Material UI" alt="Material UI" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/flutter/flutter-original.svg" title="Flutter" alt="Flutter" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/redux/redux-original.svg" title="Redux" alt="Redux " width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain-wordmark.svg"  title="CSS3" alt="CSS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original.svg" title="HTML5" alt="HTML" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="JavaScript" alt="JavaScript" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/firebase/firebase-plain-wordmark.svg" title="Firebase" alt="Firebase" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/gatsby/gatsby-original.svg" title="Gatsby"  alt="Gatsby" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="MySQL"  alt="MySQL" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="NodeJS" alt="NodeJS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" title="AWS" alt="AWS" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
</div>




## Проекты

<p> Проект 1: тестирование веб-приложения для учителей от Skyeng</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Сделать тест-план</li>
  <li>Подготовить тестовую документацию</li>
  <li>Провести тестирование</li>
  <li>Написать отчет о результатах тестирования.</li>
</ol>

<p>Как решала(-а):<p>

> <a href="https://drive.google.com/file/d/1EaH79fz-OH_LCu0l0toBGlfcLKPQVURg/view?usp=drive_link">Ссылка на проект</a>
 
 <p>Выводы (итоги):<p>
<ol>
  <li>Из первоначальной версии продукта после завершения регрессионного тестирования возникли баги с высоким приоритетом, но
само их воспроизведение не постоянно, тем не менее их устранение не стоит откладывать на длительный срок. Так же стоит
подсветить отсутствие интеграции старого функционала (уроки) с новым (личные события) системы. Прежде чем развивать
продукт дальше, необходимо доработать документацию к проекту нового функционала (личные события), а также создать
документацию к старому функционалу (уроки), это окажет благотворное влияние на качество продукта, но и облегчит работу
команде разработки не только во время тестирования, но и при непосредственной взаимосвязи между отдельными членами
команды.</li>
  <li>По результатам проверки, я считаю, что продукт не готов к полноценному релизу, но вполне может существовать как минимально
жизнеспособный продукт (MVP).</li>
</ol>


<br> 

<p> Проект 2: тестирование кабинета учителя в приложении Skyeng</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Дополнить тест-план</li>
  <li>Создать API-тест-кейсы</li>
  <li>Создать коллекцию в Postman</li>
  <li>Провести тест-ран</li>
  <li>Провести тест-ран</li>
  <li>Дополнить отчет о тестировании (на основе результатов тест-рана).</li>
</ol>

<p>Как решала(-а): краткое описание решения (автореферат)<p>

>  <a href="https://www.postman.com/cryosat-astronomer-71304009/workspace/2/collection/28557272-58fc36a5-01e5-4501-b96a-03402ea0baea?action=share&creator=28557272">Ссылка на проект</a>
 
 <p>Выводы (итоги):<p>
<ol>
  <li>После проведения тестирования API было выявлено, что система в целом работает стабильно и соответствует
заявленным требованиям из документации. Но также было отмечено, что интерфейс вкладки “Расписание” в полной мере не
реализован, например: перенос личного события из будущего на ближайшую дату к настоящему или прошедшую, невозможно на
вкладке “Расписание” во время редактирования, т.к. изменение дат доступно только в рамках одной недели, но тем не менее
данная фича реализована на Backend.</li>
  <li>На что еще хотелось бы обратить внимание, через API возможна установка любого цвета
события, возможно стоит реализовать данный функционал выбора любого цвета на усмотрение пользователей при
взаимодействии через интерфейс.</li>
</ol>



## Контактная информация
- Email: evgeniya.lyubimovah@gmail.com
