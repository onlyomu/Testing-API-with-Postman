# Testing-API-with-Postman

### Задание 1:
Задание выполняется на площадке Swagger Petstore https://petstore.swagger.io/

1. Прописать скрипт, который берет из тела ответа id созданного питомца и записывает в  окружение
2. Прописать скрипт, который будет брать тело ответа, менять параметр «status» на  «sold» (продан) и перенаправлять его в запрос на изменение питомца

### Решение:
**[Задание 1](https://github.com/onlyomu/Testing-API-with-Postman/blob/main/petstore)**

### Задание 2:
Задание выполняется на площадке open api NASA - https://api.nasa.gov/

Необходимо найти запросы Mars Rover Photos
Выполнить запрос по Querying by Earth date на дату 21.01.2022
Передать в переменную окружения id второй фотографии, распарсив json
Ответ на задание прислать в следующем виде:

1. URL получившегося запроса
2. Код js для передачи переменной

### Решение:
**[NASA](https://github.com/onlyomu/Testing-API-with-Postman/blob/main/nasa)**

### Задание 3:
1. Проанализируй требования к новой функциональности бэкенда Яндекс.Прилавка. Изучи документацию к API в Apidoc. [Требования к бэкенду](https://code.s3.yandex.net/qa/files/backend_requirements.pdf).
2. Спроектируй тесты в виде чек-листа, чтобы покрыть функциональность, которую тебе передали на тестирование. Авторизацию проверять не нужно.

**Работа с наборами**: возможность добавлять продукты в набор — ручка ```POST /api/v1/kits/:id/products```.

**Работа с курьерами**: возможность проверить, есть ли доставка курьерской службой «Привезём быстро» и сколько она стоит. Ручка ```POST /fast-delivery/v3.1.1/calculate-delivery.xml```. 

**Работа с корзиной**:
* возможность получить список продуктов, которые добавили в корзину. Ручка ```GET /api/v1/orders/:id```;
* возможность добавлять продукты в корзину. Ручка ```PUT /api/v1/orders/:id```;
* возможность удалять корзину. Ручка ```DELETE /api/v1/orders/:id```.

### Решение:
**[API check-list](https://drive.google.com/file/d/1NoAnmTxQNccwdqd8SyUMFj6b056HZe9l/view?usp=share_link)**

### Задание 4:
Проверить [XML-файл](https://code.s3.yandex.net/qa/schemes/diploma-29.png) на ошибки

### Решение:
**[Updated XML](https://drive.google.com/file/d/1gzYwiMGIoOqbIZMLRGY27luCKiM_9WQC/view?usp=share_link)**
