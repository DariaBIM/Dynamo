Apartment Calculation Script - Kvartirografia-Zimovets
Описание
Этот скрипт предназначен для работы в Dynamo, выполняет расчёт параметров квартир в проекте Autodesk Revit. Скрипт собирает данные о помещениях, учитывает их номера, этажи и типы, вычисляет жилую и общую площади квартир, а также количество комнат и записывает результаты в выбранные параметры Revit.

Функциональность
Сбор данных из помещений:
  Обрабатывает помещения на основе следующих параметров:
       ADSK_Номер квартиры.
       ADSK_Этаж.
       ADSK_Тип помещения.
       ADSK_Площадь.

  Расчёт данных:
   Вычисляет:
      Количество жилых комнат.
      Общую площадь с коэффициентом.
      Жилую площадь.
      Общую площадь.
  
  Запись данных в Revit:
      Записывает рассчитанные значения в параметры Revit.

Apartment Calculation Script - Kvartirografia-Zimovets
Description
This script is designed for use in Dynamo and performs calculations of apartment parameters in Autodesk Revit projects. The script collects data from rooms, taking into account their numbers, floors, and types, calculates the living and total areas of apartments, as well as the number of rooms, and records the results into selected Revit parameters.

Functionality
  Data Collection from Rooms:
  Processes rooms based on the following parameters:
   ADSK_Номер квартиры (Apartment Number).
   ADSK_Этаж (Floor).
   ADSK_Тип помещения (Room Type).
   ADSK_Площадь (Area).

Data Calculation:
Computes:
   Number of living rooms.
   Total area with a coefficient.
   Living area.
   Total area.

Recording Data into Revit:
Saves the calculated values into Revit parameters
