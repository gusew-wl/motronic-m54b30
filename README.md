# motronic-m54b30

* [Распиновка ЭБУ Motronic 1.3](/pinout-motronic-13.md)
* [Инструкция и распиновка MS2H4](/pinout-ms2h4.md)
* [Проводка (цвета)](/wire.md)
* [Компоненты](/components.md)
* [Распиновка платы расширения MS2H4 - Motronic 1.3](pinout-ms2h4-motronic.md)

### Дополнительная информация

* [Версии ECU](/ecu-versioning.md)

### Статьи
* [Электромагнитный клапан управления Vanos](https://www.drive2.ru/l/451448205444426227/)

### Дополнительная информация (источники)

* [E30 Zone Wiki](https://www.e30zone.net/e30wiki/index.php?title=Main_Page)
* [ECU Pinouts E30 Wiki](https://www.e30zone.net/e30wiki/index.php/ECU_Pinouts)
* [ECU Siemens MS43 Pinout](https://www.ms4x.net/index.php?title=Siemens_MS43_Pinout)
* [Схема электрооборудования E34](https://www.drive2.ru/l/602621433536844026/)
* https://www.drive2.ru/l/3647151/


#### X60003
| № | Тип | Название | Сечение | Цвет | Описание | Компонент |
|:-:|:---:|:--------:|:-------:|:----:|:---------|:----------|
|  7 | Output | U_DKG | 0.50 | BR/WS | [+5V] Voltage Supply Electric Throttle Body | Electric Throttle Body |
| 10 | Input | A_DKG2 | 0.50 | BR/BL | [0-5V] Signal Electric Throttle Body Potentiometer 2 | Electric Throttle Body |
| 19 | Input | A_DKG1 | 0.50 | BR/VI | [0-5V] Signal Electric Throttle Body Potentiometer 1 | Electric Throttle Body |
| 20 | Ground | M_DKG | 0.50 | BR/GR | Electric Throttle Body | Electric Throttle Body |
| 43 | Output | T_MDK1 | 0.75 | GR/WS | [H-Bridge] Electric Throttle Body Actuator 1 | Electric Throttle Body |
| 44 | Output | T_MDK2 | 0.75 | BR/SW | [H-Bridge] Electric Throttle Body Actuator 2 | Electric Throttle Body |
| 46 | Output | T_LLFSS | 0.50 | WS/GN | [H-Bridge] Idle Speed Actuator Closing Coil | Idle Speed Actuator |
| 47 | Output | T_LLFSO | 0.50 | WS/GE | [H-Bridge] Idle Speed Actuator Opening Coil | Idle Speed Actuator |

#### X60004
| № | Тип | Название | Сечение | Цвет | Описание | Компонент |
|:-:|:---:|:--------:|:-------:|:----:|:---------|:----------|
| 7 | Ground | M_FWG1 | 0.35 | BR/GN | Pedal Value Sensor | Accelerator Pedal |
| 8 | Input | A_FWG1 | 0.35 | WS | [0-5V] Signal Pedal Value Sensor 1 | Accelerator Pedal |
| 9 | Output | U_FWG1 | 0.35 | GE | [+5V] Supply Voltage 1 Pedal Value Sensor | Accelerator Pedal |
| 12 | Ground | M_FWG2 | 0.35 | BR | Pedal Value Sensor | Accelerator Pedal |
| 13 | Input | A_FWG2 | 0.35 | WS/GN | [0-5V] Signal Pedal Value Sensor 2 | Accelerator Pedal |
| 14 | Output | U_FWG2 | 0.35 | GE/GN | [+5V] Supply Voltage 2 Pedal Value Sensor | Accelerator Pedal|
