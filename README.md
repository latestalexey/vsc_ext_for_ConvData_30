# vsc_ext_for_ConvData_30

## Расширение для конфигурации 1С: Конвертация данных 3.0.  

Общие требовани:  
    1С:Предприятие 8.3.10+ (разработка на 8.3.10.2580)  
    Конвертация данных, редакция 3.0 (3.0.5.3)

## Возможноcти:  

## • Добавляет возможность налету генерировать epf файл, содержащий правила обмена КД 3.0 (для подключения / отладки доработанных правил)  
см. подробнее [1С: Конвертация данных 3. Инструкции и примеры.](https://infostart.ru/public/695523 "Заголовок ссылки")
    
    Вызов на форме ctrl+S  

	 Требования (ограничения по работе):  
	 Для генерации обработки используется база конвертации, поэтому:
	 - База КД должна быть файловой.
	 - База КД не должна содержать пользователей
     - Конфигуратор базы КД должнен быть закрыт
	 - Для генерации используется версия 1С, под которой запущено клиентское приложение.
Заполняем настройки генерации epf
![image](https://user-images.githubusercontent.com/18395787/48792617-c32e2200-ed05-11e8-8e1f-49136c19882e.png)  

В настройках правил обмена нажимаем на кнопку.  
![image](https://user-images.githubusercontent.com/18395787/48792721-0a1c1780-ed06-11e8-8c05-32152eebee98.png)  

## • Добавляет кнопку вызова Visual Studio Code для удобства редактирования правил.
    Для быстрого открытия редактора используйте комбинацию ctrl+Shift+E  

    Требования:
        VS Code должен быть настроен на открытие файлов bsl.  
        Установлен плагин Language 1C (BSL)  
        https://marketplace.visualstudio.com/items?itemName=xDrivenDevelopment.language-1c-bsl


![image](https://user-images.githubusercontent.com/18395787/48768558-63665580-ecca-11e8-9784-5a52c8dd50cd.png)

![image](https://user-images.githubusercontent.com/18395787/48768641-a4f70080-ecca-11e8-8caf-633f0fcf443b.png)
