# DevOps-k8s
Работу выполни студент группы ИТХ-2-21 Трефилов Владимир.

Ход выполнения работы:
1. Устанавливаем kubectl и mincube
2. Содаем приложение Flask + Redis, пишем манифесты для k8s
3. Собираем образ из исхдников внутри minikube

![image](https://github.com/user-attachments/assets/7820f4cf-b81d-4851-9801-a87c41285704)

4. Для Redis загружаем образ, на основе манифестов создаем деплоймент

![image](https://github.com/user-attachments/assets/2b98a0c1-7db8-4c76-8514-f5eeddafca0e)

5. Пробрасываем тунель внутрь minikube

![image](https://github.com/user-attachments/assets/857c5609-dc91-40f6-88d2-6c6672c85777)

6. Добавляем в приложение вывод имени реплики приложения на веб-страницу

![image](https://github.com/user-attachments/assets/773cfa4a-a51b-40f3-abbc-6a5f6280ff75)

7. Обновим наше приложение до версии 2.0

![image](https://github.com/user-attachments/assets/d7d425d1-c69f-4e68-8619-a71358008b4c)

8. Пересоберем образ с тегом v2

![image](https://github.com/user-attachments/assets/03245193-ae9e-4e95-a5bb-32354cad243f)
![image](https://github.com/user-attachments/assets/a210406e-0cf5-4f08-bd90-aedcb7f90a58)

9. Промеряем нашу страницу и убеждаемся, что приложение обновилось

![image](https://github.com/user-attachments/assets/da5b980a-78ed-4965-a003-74bfd214c2c2)
