# Python-библиотеки и программные средства

## Python-библиотеки для машинного обучения и анализа данных

| Библиотека                                | Назначение                                          | Связанные КИМ             | Доступ / ссылка                                                  | Лицензия / условия                                    |
|-------------------------------------------|-----------------------------------------------------|---------------------------|------------------------------------------------------------------|-------------------------------------------------------|
| **TensorFlow 2.x / Keras**                | Обучение и создание нейросетевых моделей            | R4.1, R4.2, R5.1          | pip install tensorflow                                           | **Apache 2.0**                                        |
| **TensorFlow Lite Converter**             | Конвертация моделей в .tflite для микроконтроллеров | R4.1, R4.2                | Входит в состав TensorFlow                                       | **Apache 2.0**                                        |
| **TensorFlow Model Optimization Toolkit** | Квантование, pruning, кластеризация моделей         | R4.2                      | pip install tensorflow-model-optimization                        | **Apache 2.0**                                        |
| **TensorFlow Lite Micro**                 | Выполнение инференса на микроконтроллерах (C++)     | R3.1, R4.1, R5.1          | [GitHub](https://github.com/tensorflow/tflite-micro)             | **Apache 2.0**                                        |
| **RKNN-Toolkit2**                         | Конвертация и симуляция моделей для NPU Rockchip    | R5.2                      | [GitHub AIRockchip](https://github.com/airockchip/rknn-toolkit2) | **Собственная (Rockchip)** — бесплатно для разработки |
| **ONNX Runtime**                          | Верификация ONNX-моделей на ПК                      | R5.2                      | pip install onnxruntime                                          | **MIT License**                                       |
| **PyTorch**                               | Обучение моделей, экспорт в ONNX                    | R5.2                      | pip install torch                                                | **BSD-style License**                                 |
| **Edge Impulse SDK**                      | Разработка и развертывание ML-моделей для Edge      | R5.1                      | pip install edgeimpulse                                          | **Apache 2.0** — бесплатно для образования            |
| **emlearn**                               | Обучение моделей с экспортом в C99 для MCU          | Альтернатива TFLite Micro | pip install emlearn                                              | **MIT License**                                       |

## Python-библиотеки для работы с данными и визуализации

| Библиотека     | Назначение                                   | Связанные КИМ    | Доступ / ссылка        | Лицензия / условия    |
|----------------|----------------------------------------------|------------------|------------------------|-----------------------|
| **NumPy**      | Работа с многомерными массивами              | R4.1, R4.2       | pip install numpy      | **BSD 3-Clause**      |
| **Pandas**     | Обработка и анализ табличных данных          | R4.2             | pip install pandas     | **BSD 3-Clause**      |
| **Matplotlib** | Построение графиков и визуализация           | R4.1, R4.2, R2.2 | pip install matplotlib | **BSD-style License** |
| **Seaborn**    | Статистическая визуализация (тепловые карты) | R4.2             | pip install seaborn    | **BSD 3-Clause**      |
| **psutil**     | Мониторинг системных ресурсов ПК             | R4.2             | pip install psutil     | **BSD 3-Clause**      |

## Python-библиотеки для коммуникации и автоматизации

| Библиотека    | Назначение                                | Связанные КИМ | Доступ / ссылка       | Лицензия / условия              |
|---------------|-------------------------------------------|---------------|-----------------------|---------------------------------|
| **pyserial**  | Управление последовательным портом (UART) | R4.2, R5.2    | pip install pyserial  | **BSD 3-Clause**                |
| **paho-mqtt** | MQTT-клиент для приема/передачи данных    | R2.2          | pip install paho-mqtt | **Eclipse Public License v2.0** |
| **requests**  | HTTP-запросы для отправки логов на сервер | R3.2          | pip install requests  | **Apache 2.0**                  |

## Инструменты командной строки и системные утилиты

| Инструмент           | Назначение                                        | Связанные КИМ    | Доступ / ссылка                                                             | Лицензия / условия                          |
|----------------------|---------------------------------------------------|------------------|-----------------------------------------------------------------------------|---------------------------------------------|
| **PlatformIO**       | Среда разработки для встраиваемых систем          | R1.1, R3.1, R4.2 | platformio.org / расширение VSCode                                          | **GPL v3** (CLI), бесплатно для образования |
| **ESP-IDF**          | Официальный фреймворк Espressif для ESP32         | R1.1             | [GitHub](https://github.com/espressif/esp-idf)                              | **Apache 2.0**                              |
| **STM32CubeMX**      | Настройка периферии и генерация кода для STM32    | R1.2             | [STMicroelectronics](https://www.st.com/stm32cubemx)                        | **Бесплатно** (требуется регистрация)       |
| **STM32Cube.AI**     | Генерация C-кода нейросетей для STM32             | R1.2             | [STMicroelectronics](https://www.st.com/stm32cubeai)                        | **Бесплатно** (требуется регистрация)       |
| **Edge Impulse CLI** | Командная строка для сбора данных и развертывания | R5.1             | npm install -g edge-impulse-cli                                             | **Apache 2.0** — бесплатно для образования  |
| **adb**              | Отладка Android-устройств (Rockchip)              | R5.2             | [Android Developers](https://developer.android.com/studio/command-line/adb) | **Apache 2.0**                              |
| **scp**              | Копирование файлов на удаленное устройство        | R5.2             | Предустановлен в Linux/macOS                                                | **OpenSSH License** (BSD-style)             |
| **esptool.py**       | Прошивка ESP32 через последовательный порт        | R4.2             | pip install esptool                                                         | **GPL v2**                                  |
| **xxd**              | Конвертация бинарных файлов в C-массивы           | R4.1, R4.2       | Предустановлен в Linux/macOS (часть vim)                                    | **Свободное использование**                 |
| **time**             | Замер времени выполнения скриптов                 | R4.2             | Предустановлен в Linux/macOS                                                | **Стандартная утилита GNU**                 |
| **tflite_convert**   | Конвертация моделей в TFLite                      | R4.2             | Входит в состав TensorFlow                                                  | **Apache 2.0**                              |
| **idf.py**           | Сборка проектов ESP-IDF                           | R4.2             | В составе ESP-IDF                                                           | **Apache 2.0**                              |
| **Git**              | Контроль версий и совместная разработка           | Все работы       | [git-scm.com](https://git-scm.com/)                                         | **GPL v2**                                  |

## Сторонние библиотеки для микроконтроллеров (C/C++)

| Библиотека                  | Назначение                                 | Связанные КИМ    | Доступ / ссылка                                          | Лицензия / условия   |
|-----------------------------|--------------------------------------------|------------------|----------------------------------------------------------|----------------------|
| **Wire.h**                  | Работа с шиной I2C на ESP32                | R1.1             | В составе Arduino/ESP32 Core                             | **LGPL 2.1**         |
| **WiFi.h**                  | Подключение к Wi-Fi                        | R2.2, R3.2       | В составе ESP32 Core                                     | **LGPL 2.1**         |
| **BLEDevice.h**             | Настройка BLE-периферии                    | R2.2             | В составе ESP32 Core                                     | **LGPL 2.1**         |
| **PubSubClient.h**          | MQTT-клиент для ESP32                      | R2.2             | [GitHub](https://github.com/knolleary/pubsubclient)      | **MIT License**      |
| **Update.h**                | OTA-обновления прошивки                    | R3.2             | В составе ESP32 Core                                     | **LGPL 2.1**         |
| **esp_sleep.h**             | Управление режимами сна                    | R6.1             | В составе ESP-IDF                                        | **Apache 2.0**       |
| **esp_pm.h**                | Управление питанием и тактированием (DFS)  | R6.1             | В составе ESP-IDF                                        | **Apache 2.0**       |
| **SPIFFS.h / LittleFS.h**   | Работа с файловой системой во Flash        | R3.2             | В составе ESP32 Core / ESP-IDF                           | **MIT / Apache 2.0** |
| **TensorFlowLite_ESP32**    | Порт TFLite Micro для ESP32                | R4.1             | [GitHub](https://github.com/espressif/esp-tflite-micro)  | **Apache 2.0**       |
| **EloquentTinyML**          | Альтернативная библиотека для TFLite Micro | R4.1             | [GitHub](https://github.com/eloquentarduino/tinyml)      | **MIT License**      |
| **DHT-sensor-library**      | Работа с датчиками DHT                     | R2.1             | [GitHub](https://github.com/adafruit/DHT-sensor-library) | **MIT License**      |
| **Adafruit Unified Sensor** | Единый интерфейс для сенсоров              | R2.1             | [GitHub](https://github.com/adafruit/Adafruit_Sensor)    | **MIT License**      |
| **ESP32 Servo Library**     | Управление сервоприводами                  | R2.1             | [GitHub](https://github.com/madhephaestus/ESP32Servo)    | **MIT License**      |
| **freertos/**\*             | Заголовочные файлы FreeRTOS                | R3.1             | В составе ESP-IDF                                        | **MIT License**      |
| **esp_timer**               | Высокоточные замеры времени                | R3.1, R4.1, R6.1 | В составе ESP-IDF                                        | **Apache 2.0**       |
| **esp_perf**                | Профилирование производительности          | R4.2             | В составе ESP-IDF                                        | **Apache 2.0**       |
