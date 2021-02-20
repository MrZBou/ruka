# ENG

### Description:
By using request parameters, you can refine what you are asking for. 
Parameters are reads from end of the message and must be in duplicated square brackets ([[parameters]]. 
Parameters should be written separated by commas and specified as parameter=value ([[parameter=value,parameter2=value2]])

### Use Example:
Official Rick Astley[[cv=30]] - Add 30 last videos from youtube-channel Official Rick Astley.

Music To Be Murdered By[[pi=2]] - Add 2-st video (Unaccommodating) from Eminem's playlist instead of full playlist.

### Parameters:
**cv** *(channel videos)* - The number of videos that will be added when specifying a channel (youtube). By default - 20.

**ci** *(channel index)* - Add only the video with the specified position on the channel, starting from the last uploaded one.

**pv** *(playlist videos)* - Limit on the number of videos added when specifying a playlist (youtube). By default - playlist size.

**pi** *(playlist index)* - Add only the video with the specified position in the playlist, starting with the first video in the playlist (youtube).
Can be specified directly in the link by adding at the end '&index=(position)'.

**type** *(content type)* - Type of content which you want to find (YouTube). Helpful when for your request Ruka finds not that result that you want (for example: video instead of playlist). May be: **playlist**, **channel**, **video** и **shelf**.

# RU

### Описание:
Используя параметры, вы можете уточнить свой музыкальный запрос.
Параметры читаются с конца сообщения и должны находиться в двойных квадратных скобках ([[параметры]]. 
Параметры должны быть указаны через запятую и выглядеть как параметр=значение ([[параметр=значение,параметр2=значение2]])

### Пример использования:
Official Rick Astley[[cv=30]] - Добавить 30 последних видео с ютуб-канал Рика Астли.

Music To Be Murdered By[[pi=2]] - Добавить 2-ое видео (Unaccommodating) из плейлиста Эминема вместо всего плейлиста.

### Параметры:
**cv** *(channel videos)* - Количество видео, которые будут добавлены, если указан ютуб-канал. По умолчанию - 20.

**ci** *(channel index)* - Добавить только видео с указанной позицией на ютуб-канале, начиная с последнего загруженного.

**pv** *(playlist videos)* - Ограничивает количество видео, которые будут добавлены из указанного ютуб-плейлиста. По умолчанию - размер плейлиста.

**pi** *(playlist index)* - Добавить только видео с указанной позицией в ютуб-плейлисте.
Может быть указано прямо в ссылке, необходимо добавить в конец '&index=(позициия)'.

**type** *(content type)* - Тип контента, который вы хотите получить по запросу (YouTube). Полезен в том случае, если по вашему запросу находится не то, что вы хотите (например видео вместо плейлиста). Возможные значения: **playlist**, **channel**, **video** и **shelf**.
