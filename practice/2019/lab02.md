# Задание на лабораторную работу №2
2018/2019 учебный год, ИВТ, весенний семестр
## Построение карт с использованием SLAM

1. В среде V-REP необходимо с реализовать пострование карты окружающего робота пространства с использованием библиотеки любой библиотеки SLAM (например, BreezySLAM) со сценой, разработанной в лаборатрной работе №1 в соответствии с вариантом.

Усложненное задание:
В среде V-REP Remote API необходимо разработать программу для робота и проверить ее работоспособность в симуляторе V-Rep, обеспечивающую передвижение робота из одной точки в другую (способ указания точки остается на усмотрение студента). 

На пути следования робота должны встретиться препятствия. Робот должен объехать их и вернуться на траекторию  следования. В качестве возможного способа реализации поставленной задачи можно рассмотреть вариант просчета точек пути следования робота. После объезда препятствия робот стремится к ближайшей точке на пути следования.


### Отчет по выполненной работе
1.	Титульный лист.
2.	Описание задания по варианту.
3.	Описания запускаемых команд
4.	Скриншот программы V-Rep, RViz и описание программы и всех функциональных блоков.
5.	[ Листинг программы с комментариями и описание работы программы].
6.	Выводы по лабораторной работе: что удалось сделать, с какими трудностями столкнулись, в чем видите пользу от используемых в лабораторной работе технологиях.


### Библиографический список
1.	М.Шахинпур. Курс робототехники.
2.	Юревич Е.И. Основы робототехники.
3.	http://ros.org
4.	http://learn.turtlebot.com/
5.	http://gazebosim.org/
6.	https://geektimes.ru/post/281760/ - описание установки ROS в среде Ubuntu на русском языке
7.	http://wiki.ros.org/turtlesim
8.	http://ros.org
9. Morgan Quigley, Brian Gerkey & William D. Smart. Programming robots with ROS. Автоматные модели: глава 13, State machines
10. Использование текстур в мире Gazebo: [1](http://answers.gazebosim.org/question/4761/how-to-build-a-world-with-real-image-as-ground-plane/) [2](http://answers.gazebosim.org/question/7922/ground-plane-texture-image/)
11. [Turtlebot docs](http://learn.turtlebot.com/)
12. [Interfacing ROS Kinetic with V-REP](http://analuciacruz.me/articles/RosInterface_kinetic/)
13. https://github.com/gentaiscool/ros-vrep-slam