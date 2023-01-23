# Testing-API-with-Postman

### Задание 1:
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

### Задание 2:
Проверить [XML-файл](https://code.s3.yandex.net/qa/schemes/diploma-29.png) на ошибки

### Решение:
**[Updated XML](https://drive.google.com/file/d/1gzYwiMGIoOqbIZMLRGY27luCKiM_9WQC/view?usp=share_link)**
