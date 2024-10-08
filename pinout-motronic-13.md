# Распиновка ЭБУ Motronic 1.3

[Motronic 1.3](https://www.e30zone.net/e30wiki/index.php?title=Motronic_1.3) uses the same [engine loom](https://www.e30zone.net/e30wiki/index.php?title=Engine_Loom) as Motronic 1.1, and therefore the 55-pin plug remains the same. However, the small differences that crept into production during the lifetime of Motronic 1.3 mean that a few extra wires are in place, to control features such as [ABS](https://www.e30zone.net/e30wiki/index.php?title=ABS).

| №  | Тип |     | Цвет | Описание |   |
|:--:|:---:|:---:|:-----:|:---------|:-:|
| 1  |  -  |  -  |   BK   | Катушка зажигания (Timing Control - to [coil](https://www.e30zone.net/e30wiki/index.php?title=Ignition#Coil) and [O2 sensor](https://www.e30zone.net/e30wiki/index.php?title=Intake#Lambda)) |  -  |
| 2  |  -  | GND |  BR  | Земля |  -  | 
| 3  |  -  |  -  | BR/GN | Реле топливного насоса ([Fuel pump](https://www.e30zone.net/e30wiki/index.php?title=Fuel#Fuel_Pump) relay control) |  -  |
| 4  |  -  |  -  | WT/YL | Регулятор ХХ (Idle speed control) |  -  |
| 5  |  -  | GND | BR | Клапан продувки адсорбера ([Evaporative purge](https://www.e30zone.net/e30wiki/index.php?title=Fuel#Carbon_Canister) valve) |  -  |
| 6  |  -  |  -  | BK | [Тахометр](https://www.e30zone.net/e30wiki/index.php?title=Instruments#Tachometer) |  -  |
| 7  |  -  |  -  | GY/YL | Измеритель расхода воздуха ([AFM](https://www.e30zone.net/e30wiki/index.php?title=Intake#AFM) input - pin 2) |  -  |
| 8  |  -  |  -  | BL | Датчик углового положения коленвала ([Cylinder ID sensor](https://www.e30zone.net/e30wiki/index.php?title=CID) input) |  -  |
| 9  |  -  |  -  |  -  |  -  |  -  |
| 10 |  -  |  -  | YL | Лямбда-зонд ([O2 sensor ground](https://www.e30zone.net/e30wiki/index.php?title=Intake#Lambda)) |  -  |
| 11 |  -  |  -  |  -  | Датчик детонации |  -  |
| 12 |  -  |  -  | GY/WT | Измеритель расхода воздуха ([AFM](https://www.e30zone.net/e30wiki/index.php?title=Intake#AFM) reference output - pin 3) |  -  |
| 13 |  -  |  -  | WT/YL | Диагностический разъём (RXO - [diagnostic plug](https://www.e30zone.net/e30wiki/index.php?title=Diagnostic_Plug)) |  -  |
| 14 |  -  | GND | BR | Земля форсунок ([Injector](https://www.e30zone.net/e30wiki/index.php?title=Fuel#Injectors) Ground) |  -  |
| 15 |  -  |  -  | GY | [Check engine light to cluster](https://www.e30zone.net/e30wiki/index.php?title=Instruments#Check_Light) |  -  |
| 16 |  -  | GND | BR/WT | [Форсунки](https://www.e30zone.net/e30wiki/index.php?title=Fuel#Injectors) 1-3-5 (2 4) |  -  |
| 17 |  -  | GND | BR/YL | [Форсунки](https://www.e30zone.net/e30wiki/index.php?title=Fuel#Injectors) 2-4-6 (1 3) |  -  |
| 18 | вход | +12 | RD | Constant 12V from [Battery](https://www.e30zone.net/e30wiki/index.php?title=Battery) |  -  |
| 19 |  -  | GND | BR/OR | Земля (Main Ground) |  -  |
| 20 |  -  |  -  |  -  |  -  |  -  |
| 21 |  -  |  -  |  -  |  -  |  -  |
| 22 |  -  |  -  | WT/GN | Регулятор ХХ ([Idle speed](https://www.e30zone.net/e30wiki/index.php?title=Intake#ICV) Close control) |  -  |
| 23 |  -  |  -  | BR/GR | Реле подогрева Лямбда-зонда ([O2 sensor heater](https://www.e30zone.net/e30wiki/index.php?title=Intake#Lambda)) |  -  |
| 24 |  -  | GND | BR | Земля (Ground) |  -  |
| 25 |  -  |  -  |  -  |  -  |  -  |
| 26 |  -  |  -  | GY/BU | Измеритель расхода воздуха ([AFM](https://www.e30zone.net/e30wiki/index.php?title=Intake#AFM) common- ground pin 4) |  -  |
| 27 |  -  |  -  | GN | Выключатель зажигания (Start input- to ignition switch and [coil](https://www.e30zone.net/e30wiki/index.php?title=Ignition#Coil) from [OBC](https://www.e30zone.net/e30wiki/index.php?title=On-board_Computer)) |  -  |
| 28 |  -  |  -  | BK | Лямбда-зонд ([O2](https://www.e30zone.net/e30wiki/index.php?title=Intake#Lambda) input) |  -  |
| 29 |  -  |  -  | BK/WT | Vehicle Speed input from [instrument cluster](https://www.e30zone.net/e30wiki/index.php?title=Instruments#Dash_Cluster) |  -  |
| 30 |  -  |  -  |  -  |  -  |  -  |
| 31 |  -  |  -  | YL | Датчик определения цилиндра ([Cylinder ID sensor](https://www.e30zone.net/e30wiki/index.php?title=CID) input) |  -  |
| 32 |  -  |  -  | WT/BL | [Econometer](https://www.e30zone.net/e30wiki/index.php?title=Instruments#Econometer) |  -  |
| 33 |  -  |  -  |  -  |  -  |  -  |
| 34 |  -  |  -  |  -  |  -  |  -  |
| 35 |  -  |  -  |  -  |  -  |  -  |
| 36 | выход | GND | BR | Реле потребителей ([Main relay](https://www.e30zone.net/e30wiki/index.php?title=DME) output) |  -  |
| 37 | вход |  -  | RD/BU | Реле потребителей (Switched power from [main relay](https://www.e30zone.net/e30wiki/index.php?title=DME)) |  -  |
| 38 |  -  |  -  |  -  | Противоугонная система, маршрутный компьютер ([ABS](https://www.e30zone.net/e30wiki/index.php?title=ABS) and [OBC](https://www.e30zone.net/e30wiki/index.php?title=On-board_Computer) cutoff for [Injectors](https://www.e30zone.net/e30wiki/index.php?title=Fuel#Injectors)) |  -  |
| 39 |  -  |  -  | GN/BU | Диагностический разъём (Programming voltage - [Diagnostic Plug](https://www.e30zone.net/e30wiki/index.php?title=Diagnostic_Plug)) |  -  |
| 40 |  -  |  -  | BK/GY | Датчик давления кондиционера ([A/C](https://www.e30zone.net/e30wiki/index.php?title=Aircon) low pressure cutoff) |  -  |
| 41 |  -  |  -  | VI/GY | Реле кондиционера ([A/C](https://www.e30zone.net/e30wiki/index.php?title=Aircon) On input) |  -  |
| 42 |  -  |  -  | RD/BU | Датчик положения селектора АКПП (Park/neutral input (auto only)) |  -  |
| 43 |  -  |  -  |  -  | Измеритель расхода воздуха |  -  |
| 44 |  -  |  -  | GY/VI | Датчик температуры всасываемого воздуха ([AFM](https://www.e30zone.net/e30wiki/index.php?title=Intake#AFM) air inlet temp- pin 1) |  -  |
| 45 |  -  |  -  | BR/RD | Датчик температуры ОЖ ([Coolant Temp input](https://www.e30zone.net/e30wiki/index.php?title=Blue_Temp_Sensor)) |  -  |
| 46 |  -  |  -  |  -  |  -  |  -  |
| 47 |  -  |  -  | BL | ДПКВ ([Engine speed](https://www.e30zone.net/e30wiki/index.php?title=Crank_Position_Sensor) input) |  -  |
| 48 |  -  |  -  | YL | ДПКВ ([Engine speed](https://www.e30zone.net/e30wiki/index.php?title=Crank_Position_Sensor) input) |  -  |
| 49 |  -  |  -  |  -  |  -  |  -  |
| 50 |  -  |  -  |  -  | [ABS](https://www.e30zone.net/e30wiki/index.php?title=ABS) Deceleration Fuel Cut-Off Overide |  -  |
| 51 |  -  |  -  |  -  | Auto Kick-Down Switch input |  -  |
| 52 |  вход  | GND | BR/BL | ДПДЗ полностью закрыта (Closed throttle input - pin 1) | |
| 53 |  вход  | GND | BR/BL | ДПДЗ полностью открыта ([WOT input](https://www.e30zone.net/e30wiki/index.php?title=Intake#Throttle_Position_Switch) - pin 3) | ДЗ приоткрыта - 52 и 53 в "воздухе" <br>  Note: TPS pin 2 is ground |
| 54 |  -  |  -  |  -  | Automatic Transmission Torque Converter Lock-up Switch |  -  |
| 55 |  -  |  -  | WT/VI | Диагностический разъём (TXD - [diagnostic plug](https://www.e30zone.net/e30wiki/index.php?title=Diagnostic_Plug)) |  -  |
