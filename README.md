# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #4 выполнил(а):
- Цюприк Егор Васильевич 
- РИ220936
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
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
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Ознакомиться с работой перцептрона на примере работы с таблицами истиности.

## Задание 1
### в проекте Unity реализовать перцептрон, который умеет производить вычисления:
- OR | дать комментарии о корректности работы
- AND | дать комментарии о корректности работы
- NAND | дать комментарии о корректности работы
- XOR | дать комментарии о корректности работы
## решение для OR
![image_2023-12-07_14-38-38](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/4944d3fc-342d-482c-b9d6-75fcf2dadaca)
![image_2023-12-07_14-38-23](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/dc847e70-fa37-44aa-b26b-deb5657661fc)
### перцепторн максимально быстро обучился, и уже со второй эпохи, не совершает ошибок

## решение для and
![image_2023-12-07_14-43-24](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/7c144ca8-4e8a-4974-8d11-42c1a0d810e0)
![image_2023-12-07_14-43-07](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/1575576f-d1b9-45e8-a1ad-df918649fa59)
### перцептрон обучился уже не так быстро как с or, понадобилось 6-7 эпох, чтобы он не совершал ошибок

## решение для nand
![image_2023-12-07_14-47-25](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/f9446280-8db2-4800-9a01-5be207b0771f)
![image_2023-12-07_14-47-39](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/e8f8b708-4fbd-4544-9fb8-e55f3ce6dca4)
### перцептрон обучился чуть быстрее в сравнение с and, понадобилось 5-6 эпох, чтобы он не совершал ошибок

## решение для xor
![image_2023-12-07_14-50-44](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/93d4173a-22e4-4b41-a682-58a25dccc339)
![image_2023-12-07_14-50-29](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/7e8eb743-4a33-4ac3-9f04-f658e97d1502)
### перцептрон не смог обучится

## Задание 2
### Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.
## or
![2023-12-07 15 36 37 docs google com 4191aff8e5eb](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/431294b3-7e66-4e93-93e8-f9ceffe1eb78)

## and
![2023-12-07 15 36 43 docs google com b98943dd3d71](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/d727dd6d-aa7c-4195-ab11-06be465b88af)

## nand
![2023-12-07 15 36 49 docs google com 955246592f04](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/889e0462-3f4c-45b1-b14d-69fecf5f4ed3)

## xor
![2023-12-07 15 36 54 docs google com 3618ec58980f](https://github.com/iosif-buter-brodsky/hell_workshop-4/assets/146319327/e57cfb80-3340-49b9-969d-eaac83336a2c)

### https://docs.google.com/spreadsheets/d/19kC0ogC53MrGbcdrg3G5vhxIK0oxBisoDudb-S2Pym8/edit?usp=sharing

## Выводы

Мы научились работать с перцептроном на примере построения таблиц истиности.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
