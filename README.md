# Детектор побега
### Как заранее узнать, кто собирается уйти? (Проект Яндекс.Практикум)

![Python](https://img.shields.io/badge/Python-3.9.5-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)

Проект решает две задачи на данных HR-агентства «Работа с заботой»:
- **Регрессия**: оценка уровня удовлетворенности сотрудника
- **Классификация**: прогноз вероятности увольнения

### 🚀 Основные результаты
- Лучшая модель регрессии: **KNeighborsRegressor** (SMAPE ≈ 14.25)
- Лучшая модель классификации: **KNeighborsClassifier** (ROC-AUC ≈ 0.91)
- Ключевые признаки ухода: удовлетворенность человека своей работой.

### 📊 Превью результатов
<img src="screenshots/correlation_heatmap.png" width="600" alt="Корреляционная матрица">

<img src="screenshots/satisfaction_kde.jpg" width="600" alt="Распределение удовлетворенности">

<img src="screenshots/workload_bar.jpg" width="600" alt="Загруженность по отделам">

### 🛠 Технологический стек
- **Python 3.9.5**
- **Библиотеки**: pandas, numpy, matplotlib, seaborn, scikit-learn, phik
- **Jupyter Notebook**

### 📓 Ноутбук проекта
Полный цикл: EDA, предобработка, моделирование, интерпретация и рекомендации бизнесу.

[Открыть с графиками (nbviewer)](https://nbviewer.org/github/Dayana373/Escape_detector/blob/main/escape_detector.ipynb)  
[Открыть на GitHub](https://github.com/Dayana373/Escape_detector/blob/main/escape_detector.ipynb)

### 📁 Данные
Данные HR-агентства (анонимизированные):

[Скачать датасет](https://disk.yandex.ru/d/nmJSwXRCamJsSw)

### 👩‍💻 Автор
Диана Сергеева  
Junior Data Scientist  
GitHub: [@Dayana373](https://github.com/Dayana373)
