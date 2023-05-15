# anime_is_all_you_need

Данный репозиторий - основная страница моего финального проекта в рамках курса Анализ данных на Python в НИУ ВШЭ. 

# Тема проекта: анализ популярности различных аниме и критериев их популярности

## Цель проект: выявить почему одни аниме популярны, а другие - нет. 

## Датасет
Я скачал датасет с сайта kaggle (https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020). В будущем также планирую дособрать в него данных (Мои попытки спарсить данные можно посмотреть в папке Fails). Сейчас все необходимые данные лежать в папке data
Что в сыром датасете? Табличка anime-2.csv содержит в себе следующие столбцы: 

MAL_ID: MyAnimelist ID of the anime. (e.g. 1)
Name: full name of the anime. (e.g. Cowboy Bebop)
Score: average score of the anime given from all users in MyAnimelist database. (e.g. 8.78)
Genres: comma separated list of genres for this anime. (e.g. Action, Adventure, Comedy, Drama, Sci-Fi, Space)
English name: full name in english of the anime. (e.g. Cowboy Bebop)
Japanese name: full name in japanses of the anime. (e.g. カウボーイビバップ)
Type: TV, movie, OVA, etc. (e.g. TV)
Episodes': number of chapters. (e.g. 26)
Aired: broadcast date. (e.g. Apr 3, 1998 to Apr 24, 1999)
Premiered: season premiere. (e.g. Spring 1998)
Producers: comma separated list of produducers (e.g. Bandai Visual)
Licensors: comma separated list of licensors (e.g. Funimation, Bandai Entertainment)
Studios: comma separated list of studios (e.g. Sunrise)
Source: Manga, Light novel, Book, etc. (e.g Original)
Duration: duration of the anime per episode (e.g 24 min. per ep.)
Rating: age rate (e.g. R - 17+ (violence & profanity))
Ranked: position based in the score. (e.g 28)
Popularity: position based in the the number of users who have added the anime to their list. (e.g 39)
Members: number of community members that are in this anime's "group". (e.g. 1251960)
Favorites: number of users who have the anime as "favorites". (e.g. 61,971)
Watching: number of users who are watching the anime. (e.g. 105808)
Completed: number of users who have complete the anime. (e.g. 718161)
On-Hold: number of users who have the anime on Hold. (e.g. 71513)
Dropped: number of users who have dropped the anime. (e.g. 26678)
Plan to Watch': number of users who plan to watch the anime. (e.g. 329800)
Score-10': number of users who scored 10. (e.g. 229170)
Score-9': number of users who scored 9. (e.g. 182126)
Score-8': number of users who scored 8. (e.g. 131625)
Score-7': number of users who scored 7. (e.g. 62330)
Score-6': number of users who scored 6. (e.g. 20688)
Score-5': number of users who scored 5. (e.g. 8904)
Score-4': number of users who scored 4. (e.g. 3184)
Score-3': number of users who scored 3. (e.g. 1357)
Score-2': number of users who scored 2. (e.g. 741)
Score-1': number of users who scored 1. (e.g. 1580)

## Предобработка данных

EDA, Визуализацию и генерацию фичей можно найти в папке data_prep. Я сильно почистил датасет, построил несколько графиков и нашел интересные зависимости, на основании которых планирую строить модели машинного обучения
