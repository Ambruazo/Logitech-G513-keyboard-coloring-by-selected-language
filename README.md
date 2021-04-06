# Logitech-G513-keyboard-coloring-by-selected-language

This windows program makes Logitech G513 (or maybe others) RGB keyboard light differently in accordance with the chosen keyboard layout. 
The color is even if the English language is chosen, and the function keys change color if keyboard switch to Russian. 
Besides there's a possibility to move the computer to sleep mode by long pressing the pause button (approx. 2 sec.)
This program requires .NET Core library installed (I recon it should offer such installation when started) and also (unfortunately) the Logitech G HUB.
The progran does not save no settings and always starts minimized to tray.
Sometimes the program fails to light up the keyboard (it stays dark) after some sleeps and awakes and this may be fixed by restarting the G HUB.

Проект написан на C# и работает в среде windows (10).
Данная программа позволяет настроить подсветку клавиатуры в зависимости от выбранного языка ввода. При выборе английского языка все клавиши имеют один цвет.
При выборе русского функциональные клавиши меняют цвет. Также меняют цвет клавиши CAPS и NUM в зависимости от своего состояния.
Присутствует функция перевода компьютера в спящий режим с помощью длинного нажатия на клавишу PAUSE.
Требуется установка библиотек .NET Core и пакета Logitech G HUB. 
Настройки программы не сохраняются, программа стартует свернутой в системный трей.
Иногда при пробуждении компьютера клавиатура остается темной, в этом случае требуется перезапуск Logitech G HUB.
