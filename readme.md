# Инструкция

1. склонируй этот репозиторий 

```shell
git clone https://github.com/lesha-co/bloje-moi.git
```

гит создаст папку `bloje-moi` внутри папки, в которой ты находишься

2. Установи Node.js.

Node — это программа, которая позволяет выполнять другие программы, написанные на JavaScript. Нам она понадобится для запуска веб-сервера (не только для него, но в том числе)

Перейди [на сайт](https://nodejs.org/), нажми `Download Node.js (LTS)`.
Запусти установщик, который скачала, можно в нем ничего не менять, только галку про лицензию поставить. Когда закончишь установку, открой командную строку (cmd.exe или git bash), и введи там 

```shell
node -v
```
параметр `-v` дает команду "выведи свою версию и закройся". в ответ должно вывестись что-то вроде

```
v20.15.0
```

Если вместо версии ты видишь ошибку, значит что-то пошло не так, я помогу

введи еще раз 
```shell
npm -v
```
в ответе должно быть 
```
10.7.0
```

если все так, значит установка прошла корректно.

3. запуск сервера

перейди в папку bloje-moi, если еще не там. Для навигации используй `cd bloje-moi`, чтоб переместиться в папку с этим именем или `cd ..`, чтобы переместиться на уровень выше

когда дойдешь до папки, выполни в консоли

```
npx serve 
```

если оно спросит что-то типа "хочешь ли ты установить пакет (y/n)", отвечай `y`

в конце концов тебе должно показать такой экран:

```
   ┌─────────────────────────────────────────┐
   │                                         │
   │   Serving!                              │
   │                                         │
   │   - Local:    http://localhost:3000     │
   │   - Network:  http://192.168.0.3:3000   │
   │                                         │
   │   Copied local address to clipboard!    │
   │                                         │
   └─────────────────────────────────────────┘
```

адрес сайта уже должен быть скопирован к тебе в буфер обмена, можешь открыть браузер и вставить его туда

если же нет, то просто нажми [на эту ссылку](http://localhost:3000)

если в браузере появилась страница, то всё готово! Ты запустила самый простой веб-сервер, можешь открыть эту же папку в vscode и начать менять веб-страницы и обновлять вкладку в браузере (не закрывая консоль только)