# Лабораторная работа № 1 "Изучение протокола HTTP" по дисциплине "Основы разработки Web-приложений"

## 1. Отправка запросов
   ### 1.1. Отправка OPTIONS-запросов <br/>
   1.1.1. Отправка на https://mail.ru/ <br/>
   
   ![image](https://github.com/user-attachments/assets/7d9fa68e-29fd-4489-ad84-83896debdfd0) <br/> 
   
   1.1.2. Отправка на https://ya.ru/ <br/>
   
   ![image](https://github.com/user-attachments/assets/42d1da06-a1dd-4159-bc87-86fc2b0831e6) <br/>
   ![image](https://github.com/user-attachments/assets/86fc525a-f1dd-4ec7-aa05-b50fc53cb648) <br/>
   
   1.1.3. Отправка на https://vk.com/ <br/>
   
   ![image](https://github.com/user-attachments/assets/fb54f901-3a5c-4457-a7f5-86c63881dd0a) <br/>
   
   1.1.4. Отправка на https://www.rambler.ru/ <br/>
   
   ![image](https://github.com/user-attachments/assets/738da019-a4a3-4e28-941d-f9ff8cb2ce40) <br/>
   
   1.1.5. Отправка на https://www.google.ru/ <br/>
   
   ![image](https://github.com/user-attachments/assets/32ca3c73-ed5d-4711-8891-c1bd05ee6e0f) <br/>
   
   1.1.6. Отправка на https://github.com/ <br/>
   
   ![image](https://github.com/user-attachments/assets/23510460-0981-4f3d-a7c2-fd15a8090d58) <br/>
   
   1.1.7. Отправка на https://www.apple.com/ <br/>
   ![image](https://github.com/user-attachments/assets/e035a519-9807-4980-b5c4-2251c188fd36) <br/>


  ### 1.2. Отправка HEAD-запросов <br/>
  
  1.2.1. Отправка на https://vk.com/ <br/>
  
  ![image](https://github.com/user-attachments/assets/395ff90e-22f6-4884-a8f9-f7ebc6ae95d5) <br/>

  1.2.2. Отправка на https://www.apple.com/ <br/>
  
  ![image](https://github.com/user-attachments/assets/67daab31-e392-4d7a-bc99-a2a431e98740) <br/>

  1.2.3. Отправка на https://www.msn.com/ru-ru <br/>
  
  ![image](https://github.com/user-attachments/assets/9b852d17-9a4d-42df-823d-054d61f46527) <br/>
  
  ### 1.3. Оправка GET-запросов <br/>
  1.3.1. Отправка на https://ya.ru/ <br/>
  
  ![image](https://github.com/user-attachments/assets/6079c41d-4357-44e4-9cbb-7eb5aa2427b8)
  ![image](https://github.com/user-attachments/assets/0f18030c-67d7-4b2b-b795-07f42b315fc5) <br/>
  
  1.3.2. Отправка на https://www.apple.com/ <br/>
  
  ![image](https://github.com/user-attachments/assets/4f6016c6-29bf-4510-adc9-c48b115a3185) <br/>
  
  1.3.3. Отправка на https://www.google.com/ <br/>
  
  ![image](https://github.com/user-attachments/assets/2c9cf177-82cc-4787-84d3-b0b3d3a265f6) <br/>

  ### 1.4. Отправка POST-запросов <br/>
  1.4.1. Отправка на https://ya.ru/ <br/>
  
  ![image](https://github.com/user-attachments/assets/47a1e813-645b-4912-a243-3edd78424fdb)
  ![image](https://github.com/user-attachments/assets/2aa6b6fa-602e-44e5-b803-18b590cd0064) <br/>

  1.4.2. Отправка на https://www.apple.com/ <br/>
  
  ![image](https://github.com/user-attachments/assets/60a5880e-8f2f-4ca7-8522-c8c309767f31) <br/>
 
  1.4.3. Отправка на https://www.google.com/ <br/>
  
  ![image](https://github.com/user-attachments/assets/d65ba8ff-a747-4284-94c5-e7f2cdc8950b) <br/>

## 2. Работа с api сайта. <br/>
В данной части лабораторной работы мы использовали API "Swagger Petstore", которое позволяет взаимодействовать с базой данных зоомагазина. <br/>
### 2.1. Использую документацию, мы отправили следующие GET-запросы: <br/>
2.1.1. Отправили GET-запрос «/pet/findByStatus», который находит питомцев в базе, исходя из их статуса: available, pending, sold. <br/>

![image](https://github.com/user-attachments/assets/d1f97a48-7bd8-4c50-8d52-2a3928fb0594) <br/>

Тело ответа: <br/>

![image](https://github.com/user-attachments/assets/a0b198e2-2130-4c30-85b9-9462164cd52d) <br/>

2.1.2. Отправили GET-запрос «/pet/{petId}» с ID собаки, взятой из списка, полученного в предыдущем запросе. <br/>

![image](https://github.com/user-attachments/assets/ed391d6f-f151-4159-a490-3bbf576dd125) <br/>

Тело ответа: <br/>

![image](https://github.com/user-attachments/assets/4cf1aa97-8a53-416f-a26d-a2ff3cb467d1) <br/>

### 2.2. Использую документацию, мы отправили POST-запросы <br/>
2.2.2. Отправляем запрос POST на добавление нового питомца: <br/>

![image](https://github.com/user-attachments/assets/c1167bcc-d390-4764-8880-c98580955e4f) <br/>

Тело ответа: <br/>

![image](https://github.com/user-attachments/assets/07d4ff37-2163-4837-b2aa-d70f22617fc1) <br/>

2.2.3. Отправили POST-запрос на добавление фото питомца. <br/>

![image](https://github.com/user-attachments/assets/0f07f2a9-3aa0-4a32-9f8e-18a0e3964510) <br/>

Тело ответа: <br/>

![image](https://github.com/user-attachments/assets/e9c53d79-d25b-4307-bebc-0577ff1aac2d) 
 
