---
permalink: /preparation-fuse.html
title: Подготовка к запуску кастомной прошивки через Fusée Gelée
author_profile: true
---
{% include toc title="Разделы" %}

В этом разделе нас ждёт практическое применение теоретических знаний, полученных в прошлый раз. Каждый из пунктов **обязателен** к выполнению, если вы хотите получить максимум от прошивки своей консоли. Каждый из этих пунктов самодостаточен. Если вы по какой-то причине ранее не выполнили любой из них, вы можете вернуться к этому позже.

Вот краткий план того, чем мы займёмся: 

После выполнения каждой инструкции из нижеследующего списка, возвращайтесь на эту страницу и переходите к следующему пункту. Если какие-то из действий вы уже выполняли, повторно их делать не нужно. 
{: .notice--warning}

1. [Создание резервной копии прошивки](backup-nand){:target="blank_"}
1. [Выбор кастомной прошивки](cfw){:target="blank_"} - на данном этапе вам необходимо определиться какой {% include abbr/cfw.txt abbr="кастом" %} вы будете использовать в дальнейшем, поскольку методы запуска и методы создания {% include abbr/emunand.txt abbr="EmuNAND" %} у них сильно разные. Просто прочитайте эту страницу и остановитесь на одной из двух прошивок. Делать пока ничего не надо. 
1. [Создание EmuNAND](emunand){:target="blank_"}
1. [Запуск кастомной прошивки](cfw){:target="blank_"} - теперь запускаем кастом. Он автоматически запустится из созданного ранее {% include abbr/emunand.txt abbr="EmuNAND" %} для того, чтобы обновить его на актуальную версию системного ПО, при этом оставив {% include abbr/sysnand.txt abbr="SysNAND" %} в его первозданном виде, без следов запуска кастомной прошивки
1. [Обновление EmuNAND до последней версии системного ПО](update-to-latest){:target="blank_"}
1. [Блокировка обновлений](block-update){:target="blank_"} - блокируем доступ к серверам Nindendo в EmuNAND для того, чтобы иметь возможность использовать интернет на приставке при этом не боясь быть забаненными и без страха получить на консоль внезапное обновление прошивки, которое испортит работу кастома
1. [Привязка аккаунта](link-account){:target="blank_"} - последний штрих. Привязки аккаунта для работы требуют некоторые игры
1. [Запуск игр](games){:target="blank_"} - финальная часть, ради которой всё и делалось

___

{% spoiler Материалы для самостоятельного изучения %}

{% include inc/additional.txt %}

{% endspoiler %}