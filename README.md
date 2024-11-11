
## **Настройка конфигов:**
***
В файле **.env** указать свои конфиги бд и апи ключ.

В **sheets.json**, поле sheetIds в массив передать id таблиц, также можно указать ссылки.

В файле **credentials.json** указать свой конфиг гугла соответствующего формата (можно скачать файл, когда настраиваешь api гугла).

Далее нужно будет подтвердить подлиность приложения(гугла), в логах будет ссылка от гугла, по которой нужно будет перейти и подтвердить с аккаунта.

После проверки, появится файл **token.json**, по которому в дальнейшем будет проходить авторизация.
***
## **Установка:**

Запустить можно либо через npm или докер.

* **Using NPM**
```
npm run build
npm run start:prod
```
***
* **Using Docker**
```
docker-compose up --build
```



