# PythonTask

## 1 задача: IO-bound
Я попробовал сделать все по заданию, что же у меня получилось?

![Screenshot_1](https://user-images.githubusercontent.com/74401943/144027972-8129ca04-0b4d-48ab-82e6-b4f4d9ccabc3.png)

Такой результат я получил без использования ThreadPoolExecutor.

После переписывания кода я получил такие результаты:
5 воркеров: 

2:37 

![Screenshot_2](https://user-images.githubusercontent.com/74401943/144028222-1d4ec0dd-2809-4a25-98f1-f0f7df12023d.png)


10 воркеров: 

2:51 

![Screenshot_4](https://user-images.githubusercontent.com/74401943/144028311-c7c0fb4e-94d8-478f-9fda-619b5a3de0cb.png)


100 воркеров:

2:59

![Screenshot_5](https://user-images.githubusercontent.com/74401943/144028464-045f0dd2-49b0-40ad-a793-b01c87d2ef61.png)


При этом загруженность процессора варьировалась от 0.7% до 2.1%. 

### Итого: Странно, но от кол-ва воркеров ничего не зависит. Видимо, я что-то сделал не так. 

## Задача 2: 

Итог примерно тот же. Я не понял, где нужно менять кол-во воркеров. 
