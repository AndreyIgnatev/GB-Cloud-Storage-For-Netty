<p align="center">
  <img width="1200" height="260" src="img/logo.webp">
</p>

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

<h2> Назначение проекта </h2>

<h3> CLOUD STORAGE - приложение для обмена для различными файлами локальным диском пользователя и облачным хранилищем(Сервером).</h3>
<body>
   <dev>
   <p>Сервис позволяет:</p>
     <ul>
     <li>Производить регистрацию пользователей;</li>
     <li>Авторизовывать пользователей по логину и паролю;</li>
     <li>Сохранять файлы на локальном диске и отправлять их под учетной записью пользоваьеля на сервер;</li>
     <li>Проводить работу с файлами пользователя на клиентской и серверной стороне (копирование/удаление/переименование);</li>
     </ul>
   </dev>
  <dev>
   <p>Сервис в своей работе использует:</p>
   <ul>
     <li>Для передачи файла от клиента в облако (на сервер) Java фреймворк Netty.</li>
     <li>Для сохранения данных пользователей (логин\пароль) sqlite database;</li>
     <li>На стороне клиентской и серверной части приложения для работы с файлами используется библиотека java.nio и Stream API;</li>
     <li>Графический интерфейс клиента выполнен на платформе JavaFX ;</li>  
     <li>Для сборки проекта используем Apache Maven;</li>  
     </ul>
  </dev>

  <dev>
   <p>Иллюстрации работы приложения:</p>
   <ul>
   <img width="400" height="260" src="/img/cloud_open.png"> <p>Окно входа в приложение</p>
   <img width="400" height="260" src="/img/registration.png"> <p>Окно регистрации</p>
   <img width="400" height="260" src="img/cloud_menu.png"> <p> Основное меню приложения</p>
     </ul>
  </dev>

   <hr>

  <dev>
     <h2>Сборка приложения:</h2>

   <dev>
   <p>Требуется выполнить следующие шаги:</p>
     <ul>
     <li>Сделать git clone этого проекта: <a href="https://github.com/AndreyIgnatev/GB-Cloud-Storage-For-Netty.git">https://github.com/AndreyIgnatev/GB-Cloud-Storage-For-Netty.git</a></li>
     <li>Собрать архив при помощи maven, используя команду в терминале: <code>mvn clean package</code></li>
    </ul>
         </dev>
  </dev>
   <hr>
     <dev>
     <h2>Технические требования:</h2>
<ul> 
<li> Java версии не ниже 8; </li> 
</ul>
</dev>
