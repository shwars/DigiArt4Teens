# DigiArt4Teens
# Создаём свой когнитивный портрет

[English Version](README.md)

Привет! Сейчас мы погрузимся в мир **Science Art**, где наука -- а именно **искусственный интеллект** -- поможет нам создавать произведения искусства! А именно, мы познакомимся с техникой [когнитивного портрета](http://eazify.net/peopleblending)

<img src="http://soshnikov.com/images/art/PhoBoGuy.png" width="30%"/>

В этой технике мы используем **[Microsoft Face API](https://docs.microsoft.com/azure/cognitive-services/face/overview/?WT.mc_id=digiart-github-dmitryso)** для выделения ключевых точек лица на серии фотографий, с последующим поворотом и масштабированием фотографий таким образом, чтобы глаза на всех снимках совпадали. Совмещая такие снимки, мы получаем интересный визуальный эффект. 

## Как начать

Весь необходимый код и инструкции содержатся в файле [MakeArt_Rus.ipynb](MakeArt_Rus.ipynb). Это стандартный Jupyter Notebook, запустить который можно одним из следующих способов:

1. Клонируйте или скачайте репозиторий на локальный компьютер и откройте его в [Visual Studio Code][VSCode] с установленным [расширением Python][VSCPyExt]. Вам также потребуется установить локальное Python-окружение (удобно использовать [miniconda][miniconda]), процесс описан [в Docs][VSCPyDoc]. 
1. Используйте [Github Codespaces][Codespaces] для запуска кода прямо на GitHub. В настоящее время доступ в Codespaces предоставляется по предварительной заявке, на одобрение которой может уйти некоторое время.
1. Откройте репозиторий [с помощью Binder][Binder]. Этот способ имеет существенный минус, т.к. в случае неактивности, или если вы закроете окружение - все изменения будут потеряны.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/shwars/DigiArt4Teens/master)

Далее следуйте инструкциям внутри ноутбука, выполняя поочередно ячейки.

[VSCode]: https://code.visualstudio.com/?WT.mc_id=digiart-github-dmitryso
[VSCPyExt]: https://marketplace.visualstudio.com/items?itemName=ms-python.python&WT.mc_id=digiart-github-dmitryso
[VSCPyDoc]: https://code.visualstudio.com/docs/python/python-tutorial/?WT.mc_id=digiart-github-dmitryso
[Codespaces]: https://github.com/features/codespaces/?WT.mc_id=digiart-github-dmitryso
[Binder]: https://mybinder.org/v2/gh/shwars/DigiArt4Teens/master
[miniconda]: https://conda.io/en/latest/miniconda.html