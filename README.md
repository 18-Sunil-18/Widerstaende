# Widerstaende
Vorwiderstände für LEDs herausfinden


Mit LEDs kann man sehr schnell die Ergebnisse eines Projekts testen. Daher sind sie für nahezu alle Arduino-Projekte nützlich. Über LEDs kann man vieles im Netz nachlesen. Hier nur die wichtigsten Infos.

•	Der Strom kann nur in einer Richtung durch die LED fließen. Daher muss sie richtig angeschlossen werden. Eine LED hat einen längeren und einen kürzeren Kontakt. Der längere Kontakt ist „+“ und der kürzere ist „-“.

•	Eine LED ist für eine bestimmte Spannung und Stromstärke ausgelegt. Wird diese Spannung oder Stromstärke unterschritten, leuchtet die LED weniger hell oder sie bleibt aus. Wird die Spannung oder Stromstärke jedoch überschritten brennt die LED sehr schnell durch und wird an den Kontakten sehr heiß (Achtung, Verbrennungsgefahr!).


Die Spannung an den Digitalen Ports des Boards beträgt 5V. Beim direkten Anschluss an diese Ports gibt jede LED recht schnell den Geist auf. Daher muss ein Widerstand mit in den Stromkreis geschaltet werden. Im Internet gibt es unter dem Suchbegriff „Widerstandsrechner LED“ sehr gute Hilfen dazu, um den passenden Widerstand zu finden.


LED-Vorwiderstandsrechner: https://www.elektronik-kompendium.de/sites/bau/1109111.htm
Widerstandsfarbcode-Tabelle (Widerstandscode / Farbcode): https://www.elektronik-kompendium.de/sites/bau/1109051.htm
