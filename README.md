# jmeter
load website

Скрипт нагрузки для JMeter который нужно открыть. как установить JMeter? для этого нам нужно зайти на сайт

http://jmeter.apache.org/download_jmeter.cgi скачиваем jmeter !(http://apache-mirror.rbc.ru/pub/apache//jmeter/binaries/apache-jmeter-3.1.zip) делаем unzip, в папке bin найдем jmeter.sh и открываем скрипт приложенный в репозитории

Запускаем JMeter без GUI. Для этого будем использовать следующую команду

jmeter -n -t spring-boot-hello-world.jmx -l myResults.jtl
