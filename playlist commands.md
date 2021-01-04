# ENG

##### Instructions:
1. **index** - track position in the playlist/queue (depends on the context), or a specific range with the start and end position separated by a hyphen. Examples: 2, 4, 5-6, 1-5
2. **indices** - unlimited number of 'index' separated by a space.
3. **playlist** - your playlist, or a playlist with the specified id in cases where this is allowed. 
The playlist does not need to be created, it is created automatically upon request.
4. **main folder** - the main folder of your playlist. Used if the folder name is not specified in the command, or when you click on a special reaction.
By default - "favorite", set when creating a playlist. May be changed.
5. **folder** - the name of the folder in the playlist. By default - main folder.
6. **user ID** - id or mention of the user (member) of the server.

## In server (with prefix)
* **pl <"add"> [indeces from queue] [folder]** - Add queued tracks to your playlist.
* **pl <"delete"> [indices from queue] [folder]** - Remove tracks from the playlist.
* **pl <"play"> [indices from playlist] [folder] [user ID]** - Add tracks from the playlist to the queue.

## In direct messages (DM)
* **pl** - Your playlist. Displays folders with the number of tracks in them, as well as playlist privacy and the main folder name.
* **pl ["delete"]** - Delete your playlist. You need to write the command again within 10 seconds. 
* **pl ["private"]** - Make your playlist private if it is public and vice versa.
...


# RU

##### Обозначения:
1. **индекс** - позиция трека в очереди/плейлисте (в зависимости от контекста), или диапазон с указанным началом и концом через дефис. Например: 2, 4, 5-6, 1-5
2. **индексы** - неограниченное количество индексов, разделенных пробелом.
3. **плейлист** - ваш плейлист, или плейлист с указанным ИД, если это доступно. 
Плейлист не нужно создавать, он создается автоматически при обращении.
4. **главная папка** - главная папка в плейлисте. Используется, если название папки в команде не указано, или при нажатии на специальную реакцию. 
По умолчанию - "favorite", устанавливается при создании плейлиста. Может быть изменена.
5. **папка** - название папки в плейлисте. По умолчанию - главная папка.
6. **ИД пользователя** - идентификатор или упоминание пользователя (участника) сервера.

## Команды сервера (с префиксом)
* **pl <"add"> [индексы из очереди] [папка]** - Добавить треки в ваш плейлист.
* **pl <"delete"> [индексы из очереди] [папка]** - Удалить треки из вашего плейлиста.
* **pl <"play"> [индексы из очереди] [папка] [ИД пользователя]** - Добавить треки из вашего плейлиста в очередь.

## Команды в личных сообщениях (DM)
* **pl** - Ваш плейлист. Отображаются папки плейлиста, количество треков в них, а также приватность плейлиста и название главной папки.
* **pl ["delete"]** - Удалить ваш плейлист. Необходимо написать команду ещё раз в течение 10 секунд.
* **pl ["private"]** - Сделать ваш плейлист приватным, если он является публичным и наоборот.
...
