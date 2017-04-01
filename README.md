# **Sources**

В директории `./src/web` находятся web-приложения для тестирования работы нескольких web-api различных разработчиков

## **WebSpeechApi**

*Приложение:* `browser_api.html` 

WebSpeechApi соответствует спецификации w3c и встроено в 2 браузера: Mozilla Firefox и Google Chrome.

> **Внимание:** *На данный момент web speech api не имеет оффициальной поддержки в Firefox и является эксперементальной технологией. Для ее активации необходимо в `about:config` установить флаг `media.webspeech.recognition.enable` в значение `true`. Стабильность работы не гарантируется!*

> **Внимание:** *Web-api в Google Chrome доступно только в десктопной версии браузера. Поддержка технологи в мобильной версии на сегодняшний день прекращена.*

> **Внимание:** *Для работы приложения( в случае, когда оно хостится не на localhost), необходим шифрованный тип соеднинения - https*



## **SpeachKit by Yandex**

*Приложение:* `yandex_api.html` 

Испольузется JavaScript-API предоставленное компанией Yandex для использования их речивых технологий. 

Api поддерживается любим современным браузером.

> **Внимание:** *Перед использованием убедитесь, что Api-key приложения не устарел. Так же будьте внимательны к версиии используемого javascript-api*

___________

# **Tests**

В директории `./tests` находятся логи работы различных приложений.

## 03.2017

`source.txt` - содержит исходный текст, который надиктовывался для проверки работы технологий распознавания речи

`goo.html` - лог работы WebSpeechApi в браузере Google Chrome v.57.0.2987.133

`ya.html` - лог работы SpeachKit JavaScript-Api (https://webasr.yandex.net/jsapi/v1/webspeechkit.js)