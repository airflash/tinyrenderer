https://habr.com/ru/post/436790/
"256 строчек голого C++: пишем трассировщик лучей с нуля за несколько часов"


mkdir build							создать папку build
cd build							зайти в нее

cmake ../renderer/					сгенерировать скрипты для сборки
make								собрать
sudo ./main 						генерирует картинку

ИЛИ 

cmake ../renderer/ -G Xcode
открыть проект в x-code,
выбрать таргетом main
запустить

генерирует картинку