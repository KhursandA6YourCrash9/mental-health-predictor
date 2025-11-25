# mental-health-predictor
Прогноз уровня депрессии по данным ВОЗ (Казахстан + мир)

# Прогноз уровня депрессии в регионах и странах  
(1990–2035 гг.) — интерактивная модель машинного обучения

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

## О проекте
Анализ глобальных данных о психических расстройствах (IHME / Our World in Data)  
Модель предсказывает риск роста депрессии по текущим показателям шизофрении, тревожности и другим факторам.

### Главный вывод:
> **Самый сильный предиктор высокого уровня депрессии — низкая доля шизофрении в популяции**  
> (обратная корреляция −0.47, объясняет ~78% прогноза)

## Особенности
- Accuracy модели — 99% (Random Forest)
- Реальные плавные вероятности (не 100/0)
- Интерактивный интерфейс прямо в ноутбуке
- Прогноз на 2025–2035 годы
- Специальный блок для Казахстана

## Как запустить
1. Открыть ноутбук: [Mental_Health_Predictor.ipynb](Mental_Health_Predictor.ipynb)
2. Запустить все ячейки по порядку
3. В последней ячейке — интерактивный прогнозатор (перемещай ползунки → получай прогноз)

## Скриншоты
![image](https://github.com/ТВОЙ_НИК/mental-health-predictor/assets/123456789/screenshot1.png)  
(после первого коммита вставишь реальные скрины)

## Автор
[Твоё имя] — студент, который сделал реально полезный проект

Данные: IHME Global Burden of Disease 2021  
Лицензия: MIT
