# Kraken Websocket package

### Начальная конфигурация
typescript eslint prettier

tsconfig
https://gist.github.com/KRostyslav/82a25c469ffa6652825d58537ac6bc22

"files": [
// Список относительных или абсолютных путей до конкретных исходных файлов, которые обязательно надо скомпилировать.
// Если секция "files" не указана, то компилятор по умолчанию включает все файлы с расширением *.ts и *.tsx, которые находятся в корневой папке и внутренних подпапках проекта.
// Если секция "files" указана, то скомпилируются файлы, которые в ней перечислены.
// Все файлы, на которые есть ссылки в файлах из секции "files", также скомпилируются.
"core.ts",
"app.ts"
],
