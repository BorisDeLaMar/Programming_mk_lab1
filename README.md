# Programming_mk_lab1
STM32CubeMX:
Чип STM32L152RBT6, PB7 - LD3, PA0 - кнопка USER. В clock config HSI 16 (16 МГц). В project manager: Toolchain/IDE - MDK-ARM, чтобы через Keil uVision прогать, а не STMCube IDE. Далее generate code
Keil uVision5: Flash - Configure flash tools - Debug. Здесь, при подключенном контроллере, где Use:ST-Link Debugger, + зайди в Settings. В SWDIO дожно быть Device name контроллера + во вкладке Flash Downloads галочку у Reset and Run.
Если компилится с ошибкой, то чек Flash - Configure flash tools - Target - ARM Compiler (если Missing, то Use default compiler version 6 выбери, если есть, конечно).
Компиляция - F7, загрузка на мк - F8.
