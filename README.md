Группа для выполнения курсовой: Булгаков Евгений Сергеевич, группа ЛАИ-195

Тема курсовой: Сайт для поиска работы

Структура окон
Структура окон представлена в виде activity-диаграммы:

![Схема](https://user-images.githubusercontent.com/81901959/166131488-4c970fcb-60e9-4fd8-a343-5404bfaed78b.jpg)

Пользователь имеет возможность перехода между Activity авторизации и регистрации. После удачной авторизации он попадает в MainMenuActivity, на которой находятся всех имеющиеся предложения по вакансиям, из которой может попасть в другие 3 activity: MessagesActivity, где будут распологаться входящие сообщения, FavouriteActivity, где можно просмотреть избранные вакансии, и ProfileActivity, где находятся данные пользователя. Если игрок решит нажать на сообщение, то попадёт в ChatingActivity, в котором будет реализована переписка с другим пользователем. Нажатие же на иконку вакансии из общего раздела, либо из раздела любимого, перенесёт на OrderActivity, в котором можно будет узнать всю информацию о вакансии.

Задание 2: приложение для отправки селфи на почту
В приложении есть кнопка "Take a shot", нажатие на которую открывает окно камеры для получения фото;
![image](https://user-images.githubusercontent.com/81901959/166134283-4e40d9d9-cb28-410d-ba35-6aa63fbfeb42.png)


После того, как вы сняли селфи, ваше приложение получает результат работы приложения в виде ссылки на изображение;
(опционально) также в приложении должен быть виджет ImageView, в котором будет показываться результат селфи;
![image](https://user-images.githubusercontent.com/81901959/166134290-2caee5bf-9c25-4353-bc95-28d1b54ce5e4.png)

Также в приложении есть кнопка "Send a selfie". По нажатию на кнопку, ваше приложение должно открыть приложения для работы с электронной почтой. Тема письма - "КПП <группа> <фамилия>". Например, "КПП АИ-191 Иванов". Содержимое письма - файл с фотографией. Слать на почту hodovychenko.labs@gmail.com
![image](https://user-images.githubusercontent.com/81901959/166134299-b4ad9e2f-c60f-416d-b8c1-ee13c8337cee.png)
![image](https://user-images.githubusercontent.com/81901959/166134300-03609857-3919-471d-8445-5298eb42a6f7.png)
