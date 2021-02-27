# ENG

##### Instructions:
1. **index** - track position in the playlist/queue (depends on the context), or a specific range with the start and end position separated by a hyphen. Examples: 2, 4, 5-6, 1-5
2. **indices** - unlimited number of 'index' separated by a space.
3. **playlist** - your playlist, or a playlist with the specified id in cases where this is allowed. 
The playlist does not need to be created, it is created automatically upon request.
4. **main folder** - the main folder of your playlist. Used if the folder name is not specified in the command, or when you click on a special reaction.
By default - "favorite", set when creating a playlist. May be changed.
5. **folder** - the name of the folder in the playlist. Size of folder name can't be more than 20 characters, also folder name can't contain spaces. By default - main folder.
6. **user ID** - id or mention of the user (member) of the server.

## In server (with prefix)
* **pl <"add"> [indeces from queue] [folder]** - Add queued tracks to your playlist.
* **pl <"delete"> [indices from queue] [folder]** - Remove tracks from the playlist.
* **pl <"play"> [indices from playlist] [folder] [user ID]** - Add tracks from the playlist to the queue.

## In direct messages (DM)
* **pl** - Your playlist. Displays folders with the number of tracks in them, as well as playlist privacy and the main folder name.
* **pl ["delete"]** - Delete your playlist. You need to write the command again within 10 seconds. 
* **pl ["private"]** - Make your playlist private if it is public and vice versa.
* **pl ["folder"] ["create" or "delete" or "show" or "rename" or "clear" or "main"] [folder name] [new name of folder]** - Manage your playlist's folders.
  * **create** - сreate folder with name, specified as folder name or named "unnamed". 
  * **delete** - delete folder with name, specified as folder name or main folder.
  * **show** - show tracks inside folder with name, specified as folder name, or main folder. If instead of show you specify a folder name, then result will be identical.
  * **rename** - change name of folder with name, specified as folder name to name specified as new name of folder.
  * **clear** - remove tracks from folder with name, specified as folder name or main folder.
  * **main** - make main the folder, which name specified as folder name.
  * *Example* - pl folder create hiphop (create folder named hiphop)
  * *Example* - pl folder rename hiphop jazz (rename hiphop folder to jazz)
  
* **pl ["track"] < action >** - Manage your tracks in folders. Actions with tracks:
 * **delete [indices] [folder name]**
    * **Deletes tracks by indices or first track from folder with name, specified as folder name or main folder.**
 * __move [indices] < position > [folder name]__
    * __Move tracks by indices of first track to specified position in folder with name, specified as folder name or main folder.__
 * __copy [indices] < position > [folder-from] < folder-to >__
    * __Copy tracks by indices of first track from folder with name, specified as folder name or main folder to specified position in folder specified as folder-to.__
    * *Example* - pl track copy 2 5-8 1 favorite special (move tracks with positions 2,5,6,7,8 from folder favorite to folder special and position 1)
* **pl ["access"] <"give" or "take"> <user ID or "all">** - Premium feature. The ability to allow the user to play your playlist, or to take away this right from him. Also you can take access from all users, using "all" parameter. *Example* - pl access give 123456789012141618


# RU

##### Обозначения:
1. **индекс** - позиция трека в очереди/плейлисте (в зависимости от контекста), или диапазон с указанным началом и концом через дефис. Например: 2, 4, 5-6, 1-5
2. **индексы** - неограниченное количество индексов, разделенных пробелом.
3. **плейлист** - ваш плейлист, или плейлист с указанным ИД, если это доступно. 
Плейлист не нужно создавать, он создается автоматически при обращении.
4. **главная папка** - главная папка в плейлисте. Используется, если название папки в команде не указано, или при нажатии на специальную реакцию. 
По умолчанию - "favorite", устанавливается при создании плейлиста. Может быть изменена.
5. **папка** - название папки в плейлисте. Название папки не может превышать 20 символов или содержать пробелы. По умолчанию - главная папка.
6. **ИД пользователя** - идентификатор или упоминание пользователя (участника) сервера.

## Команды сервера (с префиксом)
* **pl <"add"> [индексы из очереди] [папка]** - Добавить треки в ваш плейлист.
* **pl <"delete"> [индексы из очереди] [папка]** - Удалить треки из вашего плейлиста.
* **pl <"play"> [индексы из очереди] [папка] [ИД пользователя]** - Добавить треки из вашего плейлиста в очередь.

## Команды в личных сообщениях (DM)
* **pl** - Ваш плейлист. Отображаются папки плейлиста, количество треков в них, а также приватность плейлиста и название главной папки.
* **pl ["delete"]** - Удалить ваш плейлист. Необходимо написать команду ещё раз в течение 10 секунд.
* **pl ["private"]** - Сделать ваш плейлист приватным, если он является публичным и наоборот.
* **pl ["folder"] ["create" или "delete" или "show" или "rename" или "clear" или "main"] [название папки] [новое имя папки]** - Работа с папками плейлиста. 
  * **create** - создать папку с именем, указанным как название папки, или с именем "unnamed". 
  * **delete** - удалить папку с именем, указанным как название папки, или главную папку.
  * **show** - показать содержимое папки с именем, указанным как название папки, или содержимое главной папки. Если вместо show указать имя папки, то работа функции будет идентичной.
  * **rename** - поменять имя папки с именем, указанным как название папки, на имя, указанное как новое имя папки.
  * **clear** - очистить содержимое папки с именем, указанным как название папки, или содержимое главной папки.
  * **main** - сделать главной папку с именем, указанным как название папки.
  * *Пример* - pl folder create хипхоп (создать папку "хипхоп")
  * *Пример* - pl folder rename хипхоп джаз (переименовать папку "хипхоп" в "джаз")
  
 * **pl ["track"] <действие> ...** - Управление треками в плейлисте. Действия с треками:
  * **delete [индексы] [папка]**
    * **Удалить треки по индексам или первый трек из папки.**
  * **move [индексы] <position> [папка]**
    * **Переместить треки по индексам или первым на указанную позицию в папке.**
  * **copy [индексы] <position> [папка] <папка для копирования>**
    * **Копировать треки по индексам из папки на позицию в папке для копирования.**
    * *Пример* - pl track copy 2 5-8 1 favorite special (переместить треки с позициями 2,5,6,7,8 из папки favorite в папку special на позицию 1)
* **pl ["access"] <"give" или "take"> <ID пользователя или "all">** - Премиум функция. Возможность дать пользователю возможность включать ваш плейлист, или отобрать у него эту возможность. Также вы можете отобрать право у всех, у кого оно есть, используя "all". *Пример* - pl access give 123456789012141618
...
