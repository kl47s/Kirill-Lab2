# Лабораторная Работа №2 . Создание инструмента для автоматической генерации описаний изображений: использование текстовых данных для описания визуального содержимого.
Вэб сервис был реализован  с помощью веб-фреймворка Streamlit предназначенного для простого развертывания моделей.
Для начала склонируйте к себе этот репозиторий:
```Ruby
!git clone https://github.com/kl47s/Kirill-Lab2.git
```
А теперь перейдите с помощью команды cd в созданную папку Factory_detection
```Ruby
cd Image_captioning
```
Загрузите все необходимые библиотеки:
```Ruby
pip install -r requirements.txt
```
Запустите вэб сервис:
```Ruby
streamlit run web.py --server.port 80
```
Перейдите на данный сайт:
```Ruby
 http://localhost:80
```
Выберите файл с вашего ПК и ждите компиляции.
Модель была до обучена, потому ничего лишнего вам делать не придётся. Иногда может быть некорректный вывод, загрузити картинку повторно для изменения результата.

![image](https://github.com/Vokoon/Laba1_Akimov/assets/120046709/e89c4caa-35fd-4d4c-883f-4b9dcef1d073)

![image](https://github.com/Vokoon/Laba1_Akimov/assets/120046709/0a92dac4-699e-4b17-8e2b-ecba38904bb5)

Для корректной работы streamlit веб-фреймворка может потребоваться наличие python версии не ниже 3.9.12.
Иногда сайт может не запустится с первого раза или же код скажет что вам нехватает конкретной библиотеки, потому вам может понадобится загрузить их по новой.

# Источники!:
https://github.com/Koldim2001/Image_captioning/tree/main?tab=readme-ov-file
https://nbviewer.org/github/Koldim2001/Image_captioning/blob/main/image_captioning_no_attention.ipynb
