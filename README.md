# whisper-test

Ничего не трогайте плз здесь. Описание будет позднее

В репозитории используються собственные модифицированные библиотеки geth, т.к. в оригинальных библиотеках найдены
баги не позволяющие использовать whisper как подключаемый модуль.
Внесены некоторые изменения в файл библиотеки whisper.go (пакет whisperv5) что бы исправить это

Так-же добавлен вывод логов на экран (очень коряво, надо это пофиксить) и некоторые другие небольшие изменения.

Для корректной работы программы можно скачать официальный go ethereum коммандой ```go get github.com/ethereum/go-ethereum ``` и затем
заменить папку go-ethereum папкой модифицированной библиотеки (из соответствующей директории этого репозитория)
