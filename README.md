**Создвание ветки**
`git checkout -b "webpack"`

**Заливаем изменения в новую ветку:**
`git push -u origin webpack`

**Переходим в ветку master:**
`git checkout master`

**После соединения веток и перехода в master набираем:**
`git pull`

**Фиксим Eslint, если ругается**
`eslint --fix webpack.config.js`
webpack.config.js - это файл котрый надо фиксить

**Проверка файла/папки через Eslint**
`eslint webpack.config.js src` проверяем файл и папку
