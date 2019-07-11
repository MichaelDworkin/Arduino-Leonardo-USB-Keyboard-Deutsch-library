# Arduino-Leonardo-USB-Keyboard-Deutsch-library
Arduino Leonardo USB Keyboard Deutsch ( german ) layout library
"Keyboard Library for Arduino" für das Verwenden mit deutscher Tastaturbelegung
Bibliothek für Arduino/Genuino Leonardo und Micro ( ATmega32U4 )

=== Anleitung ===

1. Kopiere den Ordner "KeyboardDE" in deinen .../Arduino/Libraries/ - Ordner.  
   
2. Jetzt kannst du den Beispiel Sketch "KeyboardDeutsch" im Untermenü Beispiele/ (Beispiele aus eigenen Bibliotheken) KeyboardDE öffnen.

== ACHTUNG ==

Die Umlaute werden nur durch das Keyboard.print() funktion ausgegeben.

Keyboard.press() und  Keyboard.release() müssen folgende konstanten übergeben werden
KEY_O_UMLAUT
KEY_A_UMLAUT

KEY_U_UMLAUT

KEY_ESZETT
