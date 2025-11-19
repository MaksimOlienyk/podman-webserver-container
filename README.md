# podman-webserver-container
## - Запустити контейнер із вебсервером:
docker run -d -p 8080:80 nginx
<img width="922" height="344" alt="image" src="https://github.com/user-attachments/assets/47957d41-d289-41c5-a8ad-ae13601c464b" />

## - Відкрити браузер і перейти на http://localhost:8080
<img width="848" height="258" alt="image" src="https://github.com/user-attachments/assets/d4989ffb-8b26-435e-9fd3-b75e3ac3f4d3" />

## - Змінити конфігурацію сторінки:
<img width="924" height="177" alt="image" src="https://github.com/user-attachments/assets/3534f185-c95f-4e5b-af77-ae3b9df1cb1c" />
<img width="932" height="120" alt="image" src="https://github.com/user-attachments/assets/2797cddc-ab53-453b-ad88-4adcc20940b1" />
<img width="934" height="509" alt="image" src="https://github.com/user-attachments/assets/3a2b2131-727c-40ed-86a1-6b80928ad316" />

## - створити свій index.html;
<img width="855" height="544" alt="image" src="https://github.com/user-attachments/assets/ad1cadca-da8f-4614-a52f-cb58cee88a51" />

## - змонтувати директорію через volume:
docker run -d -p 8080:80 -v $(pwd)/site:/usr/share/nginx/html nginx
<img width="924" height="304" alt="image" src="https://github.com/user-attachments/assets/9c66cec8-8e65-4505-bd4b-a45b62e7dfd8" />
