# PetProjects

Здесь располагаются проекты, цель для которых придумывал я сам. Данные работы были выполнены на основе наборов данных, взятых из открытых источников. 

Также, при желании, с моими учебными проектами в Яндекс Практикум можно ознакомиться [здесь](https://github.com/Andrey-Mukoseev/YandexPracticum).

|№  |Наименование проекта         |Описание                          |Стек технологий      |
|---|------------------------------|---------------------------------|---------------------|
|1  |[Крушение Титаника](https://github.com/Andrey-Mukoseev/PetProjects/tree/main/Titanic) | В данной работе были проделаны такие действия, как предобработка данных, визуализация некоторых зависимостей между признаками, а также нахождение новых фичей для рассматриваемой задачи. В качестве подбора гиперпараметров для модели предсказания целевого признака (случайный лес) была взята идея совмещения случайного поиска гиперпараметров (RandomizedSearchCV) для определения более узкого диапазона значений и поиска по сетке (GridSeacrhCV) в выбранном диапазоне| Python, Pandas, Matplotlib, Scikit-learn, Seaborn, NumPy|
|2  |[Классификация музыки](https://github.com/Andrey-Mukoseev/PetProjects/tree/main/Music) | Данная работа была выполнена в ходе проекта Мастерской от Яндекс Практикум. За основу были взяты данные о различных характеристиках музыкальных произведений и их жанрах. Целью проекта было обучить модель предсказывать жанр музыки по ее характеристикам. В результате был проведен разведочный анализ данных, по результатам которого были выявлены различные аномалии в данных. Весь проект был построен таким образом, что после каждого способа устранения этих аномалий проверялась способность базовых моделей предсказывать целевой признак. Способы предобработки данных, показавшие наилучшие метрики, были взяты за основу.| Python, Pandas, Matplotlib, Scikit-learn, Seaborn, NumPy, CatBoost, LightGBM|
