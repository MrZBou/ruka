# ENG
Command usage guide.

**Prefix** - short phrase, which must be in the start of the message to gives Ruka understand, that you are referring to her and trying to execute the command, instead of just sending message.
Instead of prefix Ruka's mention can be used, if you forgot the prefix. Further, "r!" prefix will be used as prefix, because its prefix by default.

Command "r!command" displays information about command, includes it's usage.
In the field "Usage" can be brackets and quotes, the purpose of which will be described below.
* <> - if parameter has on such brackets, then command will not work without specify it's (you mustn't write the brackets)
    * *Example:* command <command name> - Command name must be specified, for example: **r!command install**. Otherwise, the Ruka will notify you of the impossibility to execute the command.
* [] - if parameter has on such brackets, then its use is optional and the command will work differently with and without it (you mustn't write the brackets)
    * *Example:* prefix [prefix] - You can specify a prefix, then it will be set as new, for example **r!prefix !**. If you do not specify it, the Ruka will send you the current prefix.
* "" - if parameter has on quotes, then it is used in the form in which it is written, but without quotes.
    * *Example:* help ["here"] - You can add the word "here" to command (without quotes), so that the response goes to the current text channel - **r!help here**. If no word is added, or
     you write it incorrectly, then the answer will be sent to you in direct messages.
    
# RU
Руководство по использованию комманд.

**Префикс** - короткое выражение, которое должно находиться в начале команды, чтобы Рука понимала, что вы обращаетесь к ней и пытаетесь выполнить команду, а не просто пишете сообщение.
Вместо префикса может быть упоминание Руки, если вы вдруг забыли его. Ниже в качестве примера будет использоваться префикс "r!", так как он является префиксом Руки по умолчанию.

С помощью команды "r!command" вы получаете информацию о команде, включая её использование.
В поле "Использование" могут находиться скобки и кавычки, назначение которых будет описано ниже.
* <> - если параметр находится в таких скобках, то команда не будет работать, если его не указать. Скобки писать не нужно.
    * *Пример:* command <имя команды> - Необходимо указать имя команды, например **r!command install**. Иначе Рука уведомит вас о невозможности выполнить команду.
* [] - если параметр находится в таких скобках, то его использование необязательно, и команда будет работать по-разному с ним и без него. Скобки писать не нужно.
    * *Пример:* prefix [префикс] - Можно указать префикс, тогда он установится как новый, например **r!prefix !**. Если его не указать, Рука отправит вам текущий префикс.
* "" - если параметр находится в кавычках, значит он используется в том виде, в котором написан, но без кавычек.
    * *Пример:* help ["here"] - Можно добавить слово "here" к команде (без кавычек), чтобы ответ отправился в текущий канал - **r!help here**. Если слово не будет добавлено, либо
    вы напишите его неправильно, то ответ отправится вам в личные сообщения.
