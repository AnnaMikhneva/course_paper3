# Проект по программированию
Классификатор для верификации аннотаций: Classifier for annotation verification
Работу выполнили: Михнева Анна, Шостак Татьяна, Шишкова Алина \
Цель нашей работы состояла в создании обученного классификатора, который сможет определять пригодность аннотации для использования, то есть ее качество и информативность.
Основными шагами проекта были:
1. сбор данных из openalex (файл "r скрипт.R")
2. доразметка данных для наших целей при помощи первого классификатора и матриц ошибок, которые были выведены, а также анализ датасета (файлы "preprocessing.ipynb" и "classificator1.ipynb")
3. векторизация, снижение размерности векторов и визуализация аннотаций ("vizualization.ipynb")
4. применение к данным 4 моделей машинного обучения ("classificator2.ipynb") \
Папка graphics содержит диаграммы рассеяния, которые получились в результате визуализации векторизированых аннотаций. Папка matrix содержит аннотации из матриц ошибок после применения различных моделей.
