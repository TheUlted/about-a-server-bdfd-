# i maked on RU languange
$nomention
$color[000000]
$thumbnail[$serverIcon[$guildID]]
$title[|**Информация о сервере**|]
$description[
----------
**Серверная информация:**
----------
• Создатель сервера: <@$serverOwner>
• Имя сервера: $serverName[$guildID]

• Приглашение в этот сервер: [$serverName[$guildID]]($getServerInvite[$guildID])

• Айди сервера: $guildID
• Сервер создан: $creationDate[$guildID]
• Уровень проверки: $serverVerificationLvl
----------

----------
**Кол-во участников:**
----------
• Всего пользователей: $membersCount

• Онлайн: $membersCount[online]
• Не активен: $membersCount[idle]
• Не беспокоить: $membersCount[dnd]

• В сети всего: $sum[$membersCount[online];$membersCount[idle];$membersCount[dnd]]

• Оффлайн: $sub[$membersCount;$membersCount[online];$membersCount[idle];$membersCount[dnd]]
----------

----------
**Каналы и роли:**
----------
• Всего Каналов: $channelCount
• Всего ролей: $roleCount
----------

----------
**Эмодзи:**
----------
• Количество эмодзи: $emoteCount
----------]
# and u can make  variable $icon. Example "$icon[icon link] 
