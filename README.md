# В папке содержатся файлы для заливки в Ардуино Leonardo или PRO MICRO
оснащенных USB HOST SHIELD. При подключении к USB HOST SHIELD дополнительной клавиатуры, в коде 
numpad2.ino можно запрограммировать комбинации клавиш для выполнения макросов. В данный момент там запрограммированы коды для большого нумпада для работы в 1с

numpad.ino - код мини нумпада

numpad2withscreen1602.ino - с экраном 16*2. SCL - D3, SDA - D2 на USB HOST SHIELD. Тест выводится на русском. 
Для русского текста требуется библиотека LCD_1602_RUS-master.

numpad2_ws2812_indikator.ino - подключен индикатор раскладки (русский,английский) на планке с диодами ws2812 - 8 шт и
возможностью включения статичных цветов(зеленый, синий, красный, фмолетовый, аква, желтый) комбинацией клавиш CTRL+1,2,3,4,5,6
Режим работает в независимости от ПК.

корпус для печати на зд принтере: https://www.thingiverse.com/thing:5842612

# The folder contains files for uploading to Arduino Leonardo or PRO MICRO
equipped with USB HOST SHIELD. When you connect an additional keyboard to the USB HOST SHIELD, you can program key combinations in the numpad2.ino code to execute macros. At the moment there are codes programmed there for a large numpad to work in 1c

numpad.ino - mini numpad code

numpad2withscreen1602.ino - with a 16*2 screen. SCL - D3, SDA - D2 on USB HOST SHIELD. The test is displayed in Russian. For Russian text, the LCD_1602_RUS-master library is required.

numpad2_ws2812_indikator.ino - connected layout indicator (Russian, English) on a strip with ws2812 diodes - 8 pcs and the ability to turn on static colors (green, blue, red, yellow, aqua, yellow) using the key combination CTRL+1,2,3,4, 5.6 The mode works regardless of the PC.

housing for printing on a 3D printer: https://www.thingiverse.com/thing:5842612

![macropad1](https://github.com/bakuma64/Arduino/assets/46646555/dffac224-8f60-476e-a5fe-c4ca1eed608b)

![macropad2](https://github.com/bakuma64/Arduino/assets/46646555/aa6faa43-4b5e-433d-91d4-d480e88d7eee)

![macropad3](https://github.com/bakuma64/Arduino/assets/46646555/c0b6fb6f-0085-4c7d-98f8-acf445b48d89)

![macropad4](https://github.com/bakuma64/Arduino/assets/46646555/f4fe4442-1b8b-4608-a9bf-ea01a48412e9)

![IMG_20230627_174342 1](https://github.com/bakuma64/Arduino-macropad/assets/46646555/788d2ca5-c2c2-4910-94a0-7ceaf1860ac7)
