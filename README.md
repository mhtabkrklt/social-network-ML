# VK Friends Graph and Recommendations

Этот проект демонстрирует, как получить данные друзей из ВКонтакте с помощью `vk_api`, построить граф друзей с помощью `NetworkX` и `Matplotlib`, раскрасить вершины по признакам (город, университет) и вычислить рекомендации новых друзей по метрике Adamic/Adar.

## Описание

- Подключение к API ВКонтакте по токену.
- Загрузка списка друзей с дополнительными полями (`city`, `universities`).
- Построение графа друзей.
- Раскраска вершин по признакам:
  - Город проживания.
  - Университет.
- Поиск возможных новых друзей по метрике Adamic/Adar.
- Визуализация графа и топ-5 рекомендаций.
![Image alt](https://github.com/mhtabkrklt/social-network-ML/blob/main/images/Screenshot%202025-08-01%20at%2019.08.11.png)
![Image alt](https://github.com/mhtabkrklt/social-network-ML/blob/main/images/Screenshot%202025-08-01%20at%2019.23.51.png)
![Image alt](https://github.com/mhtabkrklt/social-network-ML/blob/main/images/Screenshot%202025-08-01%20at%2019.05.46.png)
## Используемые библиотеки

- [`vk_api`](https://github.com/python273/vk_api) — работа с VK API.
- [`networkx`](https://networkx.org/) — создание и анализ графов.
- [`matplotlib`](https://matplotlib.org/) — визуализация.

##  Запуск

1. **Установите зависимости**:
    ```bash
    pip install vk_api networkx matplotlib
    ```

2. **Подготовьте токен VK**  
   Получите `access_token` [через VK OAuth](https://vk.com/dev/access_token).

3. **Запустите скрипт**  
   ```python
   python vk_friends_graph.py

