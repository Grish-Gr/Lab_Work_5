# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #5 выполнил(а):
- Терещенко Максим Сергеевич
- РИ210913
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | # | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.

## Цель работы
Интегрировать экономическую систему в проект Unity и обучение ML-Agent

## Задание 1
### Задание 1 Интегрировать экономическую систему в проект Unity и обучение ML-Agent.
Ход работы:
- Откроем проект Unity. Добавим в него ml-agents
![add_package_mlagent](https://user-images.githubusercontent.com/101037462/209569362-abfc272c-5971-4910-a195-da52b305b40b.PNG)
- Создадим сцену с одним префабом, где находится RollerAgent, который будет бегать от Target и до GoldMine, тем самым мы имитируем добычу и продажу ресурсов
- Запустим MLAgent через Anaconda Prompt и начнем обучение на одном префабе
![image](https://user-images.githubusercontent.com/101037462/209571790-73639086-9502-4631-9d54-89c1146cb36f.png)
- Попробуем повторить тоже самое, но увеличим количество префабов для быстроты обучения
![MLA_Lab4-Economic-ML-Agent-Windows_-Mac_-Linux-Unity-2021 3](https://user-images.githubusercontent.com/101037462/209570207-c2ef2a3d-bd22-436d-8c1c-e689d7a9ec10.gif)
- Получаем вывод в консоль
```
[INFO] Economic. Step: 5000. Time Elapsed: 28.472 s. No episode was completed since last summary. Training.
[INFO] Economic. Step: 10000. Time Elapsed: 45.891 s. Mean Reward: -0.667. Std of Reward: 0.745. Training. ELO: 1194.840.
[INFO] Economic. Step: 15000. Time Elapsed: 65.886 s. Mean Reward: 1.000. Std of Reward: 0.000. Training. ELO: 1190.019.
[INFO] Economic. Step: 20000. Time Elapsed: 84.663 s. No episode was completed since last summary. Training.
[INFO] Economic. Step: 25000. Time Elapsed: 104.691 s. Mean Reward: 1.000. Std of Reward: 0.000. Training. ELO: 1190.032.
[INFO] Economic. Step: 30000. Time Elapsed: 121.811 s. Mean Reward: 1.000. Std of Reward: 0.000. Training. ELO: 1190.045.
[INFO] Economic. Step: 35000. Time Elapsed: 140.757 s. No episode was completed since last summary. Training.
[INFO] Economic. Step: 40000. Time Elapsed: 157.983 s. Mean Reward: 1.000. Std of Reward: 0.000. Training. ELO: 1190.057.
[INFO] Economic. Step: 45000. Time Elapsed: 180.607 s. Mean Reward: 1.000. Std of Reward: 0.000. Training. ELO: 1190.070.
[INFO] Economic. Step: 50000. Time Elapsed: 196.611 s. No episode was completed since last summary. Training.
[INFO] Economic. Step: 55000. Time Elapsed: 216.509 s. Mean Reward: 1.000. Std of Reward: 0.000. Training. ELO: 1190.083.
[INFO] Economic. Step: 60000. Time Elapsed: 233.649 s. Mean Reward: 0.833. Std of Reward: 0.553. Training. ELO: 1189.679.
[INFO] Economic. Step: 65000. Time Elapsed: 253.574 s. Mean Reward: 1.000. Std of Reward: 0.000. Training. ELO: 1188.525.
[INFO] Economic. Step: 70000. Time Elapsed: 272.454 s. Mean Reward: 0.714. Std of Reward: 0.700. Training.
[INFO] Economic. Step: 75000. Time Elapsed: 293.572 s. Mean Reward: 1.000. Std of Reward: 0.000. Training. ELO: 1188.121.
[INFO] Economic. Step: 80000. Time Elapsed: 311.146 s. Mean Reward: 1.000. Std of Reward: 0.000. Training. ELO: 1188.134.
[INFO] Economic. Step: 85000. Time Elapsed: 330.556 s. No episode was completed since last summary. Training.
```
- Теперь визуализация обучение с помощью Tensorboard
![download_tensor](https://user-images.githubusercontent.com/101037462/209569873-f8fd045a-0cee-4387-9139-6f8fc3d3d33b.PNG)
- Получаем отчет о проделанном обучении на нескольких префабов
![res_tensor](https://user-images.githubusercontent.com/101037462/209569945-553a5489-1fea-4bcc-9d37-a5d4bdb1899c.PNG)

## Выводы

Я научился интегрировать экономическую систему в проект Unity

**BigDigital Team: Denisov | Fadeev | Panov**
