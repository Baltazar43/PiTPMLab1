# PiTPMLab1
 **Отчет**

Сделал студент

Группы ИСП-320п

Рыкшин Илья

1. POST <http://127.0.0.1:5000/user>

` `body: 

{

`    `"name": "Alesha",

`    `"password": "qwert",

`    `"email": "alesha123@gmail.com",

`    `"group": "isp-320p"

}

Принимаемая информация: Пользователь добавлен

![](Aspose.Words.b1448d81-4234-430b-823e-6a40efa153ac.001.png)

Рисунок 1. Post user

1. GET <http://127.0.0.1:5000/user>

body:

{

`    `"name": "Alesha",

`    `"password": "qwert",

`    `"email": "alesha123@gmail.com",

`    `"group": "isp-320p"

}

Принимаемая информация: Alesha qwert alesha123@gmail.com isp-320p

![](Aspose.Words.b1448d81-4234-430b-823e-6a40efa153ac.002.png)

Рисунок 2. GET user

1. ` `PUT <http://127.0.0.1:5000/user/0>

body:

{

`    `"name": "Andrey"

}

`		`Принимаемая информация: Пользователь изменен

![](Aspose.Words.b1448d81-4234-430b-823e-6a40efa153ac.003.png)

Рисунок 3. PUT user

1. GET http://127.0.0.1:5000/user 

body:

` `{

}

`		`Принимаемая информация: Andrey qwert alesha123@gmail.com isp-320p

`		`![](Aspose.Words.b1448d81-4234-430b-823e-6a40efa153ac.004.png)

Рисунок 4. GET измененный user

1. ` `DELETE <http://127.0.0.1:5000/user/0>

body:

{

}

Принимаемая информация: Пользователь удален

`	`![](Aspose.Words.b1448d81-4234-430b-823e-6a40efa153ac.005.png)

Рисунок 5. DELETE user

1. ` `POST <http://127.0.0.1:5000/music>

`  `{

`    `"name": "Magnolia",

`    `"executor": "Playboycarti",

`    `"year": "2017"

}

Принимаемая информация: Музыка добавлена

![](Aspose.Words.b1448d81-4234-430b-823e-6a40efa153ac.006.png)

Рисунок 6. POST music

1. ` `GET <http://127.0.0.1:5000/music>

body:

` `{

`    `"name": "Magnolia",

`    `"executor": "Playboycarti",

`    `"year": "2017"

}

`		`Принимаемая информация: Magnolia Playboycarti 2017

`		`![](Aspose.Words.b1448d81-4234-430b-823e-6a40efa153ac.005.png)

Рисунок 7. GET music

1. ` `PUT <http://127.0.0.1:5000/music/0>

` `body:

{

`    `"name": "Miss the rage"

}

Принимаемая информация: Музыка изменена

![](Aspose.Words.b1448d81-4234-430b-823e-6a40efa153ac.007.png)

Рисунок 8. PUT music

1. ` `GET <http://127.0.0.1:5000/music>

body:

{

}

Принимаемая информация: 

`		`Miss the rage Playboycarti 2017

![](Aspose.Words.b1448d81-4234-430b-823e-6a40efa153ac.008.png)

Рисунок 9. GET измененный music

1. DELETE <http://127.0.0.1:5000/music/0>

body:

{

}

Принимаемая информация: Музыка удалена

![](Aspose.Words.b1448d81-4234-430b-823e-6a40efa153ac.009.png)

Рисунок 10. DELETE music




