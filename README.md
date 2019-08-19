# VkLightApi
Light API to light using VK

### Принцип работы

* Написан на php с использованием библиотеки GuzzleHttp и vk_API

### Настройка

* В классе vkBot вставить в $token полученный токен от telegram

# Methods

* getUpdates() - Возвращает обновления на стороне клиента
* sendMessage(chat_id, text, answers) - Отправляет сообщение в chat_id, возможно добавление кнопок, answers - массив с ними 
* getNewServer() - Обновляет сервер отправки при ошибке на предыдущем
