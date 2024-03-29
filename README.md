# Бот для танцевальной школы
Бот для социальной сети *ВКонтакте*. 

<img src="https://user-images.githubusercontent.com/54308955/183393116-59164b63-600c-47b4-876f-8445ffc17e69.png" width="400">

## Цель бота:
1. Расширить каналы взаимодействия с клиентом
2. Разгрузить команду от второстепенных задач
3. Ускорить среднее время ответа клиенту
4. Ускорить среднее время записи на занятие

## Задачи:
1. Отвечать на часто задаваемые вопросы
2. Записывать новых клиентов на пробное занятие
3. Взаимодействовать с клиентами по средствам массовой рассылки
4. Автоматизировать сбор данных

## Возможности бота при общении с клиентом:

1. Бот умеет приветствовать собеседника
2. Если пользователь не понимает как общаться с ботом или ему требуется общение с реальным человеком, то бот может позвать администратора. Бот позовет администратора соответственно автоматически или по нажатию пользователем кнопки "Позвать человека" 
3. Бот может предоставить основную информацию о школе. Для этого пользователь выбирает нужную кнопку
* Для каких возрастов имеются группы?
* Какие направления танцев есть в школе?
* Расписание занятий
* Что требуется для занятия
* Адрес школы
* Контакты школы
4. Бот может записать собеседника на занятие. Когда собеседник выбрал нужную группу и время, администратору в личные сообщения ВК приходит заявка. 

## Возможности бота при общении с администратором 🙂:

Администраторы делятся на 2 уровня. 
1. Администраторы 1 уровня имеют доступ ко всем командам
2. Администраторы 2 уровня имеют доступ к командам массовой рассылки, узнать номер телефона, узнать n последних собеседников

Бот способен общаться с клиентами и одновременно выполнять одну команду администратора. Если при выполнении команды ботом администратор выполнит новую команду, то она добавится в очередь команд, а администратор получит соответствующее уведомление

* Для работы с ботом у администратора имеются команды. Список всех команд можно узнать с помощью команды
```
/help
```
<img src="https://user-images.githubusercontent.com/54308955/183400901-8ded354c-847d-4f6b-8ede-75bcb44ce4f1.png" width="400">

* Чтобы команды выполнялись собеседник должен находится в списке администраторов. Администратора можно добавить вручную внеся в базу или с помощью команды 
```
/aa <id> <level>
```
* Для удаления администратора выполните команду     
```
/dela <id>
```
* Чтобы вывести на экран список всех администраторов выполните команду 
```
/ca 
```
* Бот автоматически запоминает всех кто разрешил ему отправлять сообщения. Однака, имеется команда, которая запустит поиск таких пользователей по всем возможным каналам. Данная команда может выполнятся достаточно долго, при большом количестве доступных пользователей. После выполнения команды придет уведомление о количестве обнаруженных пользователей
```
/asp
```
* Для запуска массовой рассылки выполните команду. На один запуск команды стоит ограничение по количеству сообщений (со стороны ВК). Поэтому бот автоматически будет перевыполнять команду. После завершения рассылки придет уведомление о количестве сделанных сообщений  
```
/sp <id_content>
```
* Чтобы узнать номер клиента, если он его написал, выполните команду
```
/ph <id>
```
* Чтобы узнать n посдених добавленных в базу собеседников выполните команду
```
/lc <count>
```
**Вы можете пообщаться с ботом, для этого напишите ему https://vk.com/elclasicodance**
