# 1541-rebuild
Ersetzt den Analogteil einer Floppy 1541 II durch ein µC der Disk Images per SD Karte lesen kann. Mit dieser Hardware ist es möglich ein Board wo der Analogteil defekt ist, durch diese wieder zum laufen zu bringen. Das schreiben ist derzeit noch nicht eingebaut. Es wird lediglich die 1541II Platine, diese Hardware und ein 5VDC Netzteil benötigt. An der 1541 II Platine müssen einige Änderungen vorgenommen werden (VIA2 (DC) sockeln, 1 PIN vom Gate Arry trennen ...).
Derzeit ist es möglich aus einem Root Verzeichnis einer SD Karte, D64 sowie G64 Images auszuwählen. Diese werden dann wie eine eingelgte Diskette erkannt und der C64 kann diese lesen. Als Anzeige kommt ein 4-Zeiliges LCD (20x4) zum Einsatz.

![Screenshot](/hardware/1541-rebuild.png)

###Kleines Video 1541-rebuild in Aktion
https://youtu.be/EGB8lYKcW-g


###Verwendete Libs<br \>
LCD Ansteuerung von Mikrokontroller.net <br \>
http://www.mikrocontroller.net/articles/AVR-GCC-Tutorial/LCD-Ansteuerung

SD/FAT System von Roland Riegel<br \>
http://www.roland-riegel.de/sd-reader/
