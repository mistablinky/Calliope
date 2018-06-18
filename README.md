# Calliope Ambulance
Erste Schritte mit Calliope mini

Der Calliope mini ist ein Entwicklungsboard für den einfachen Einstieg in die digitale Welt und in die Programmierung. Der Einstieg ist möglich ohne weitere Vorkenntnisse. Weitere Informationen unter https://calliope.cc/.

Dieses Respository enthält Codebeispiele für die Microsoft MakeCode Entwicklungsumgebung unter https://makecode.calliope.cc/. Die Beispiele führen Schritt für Schritt vom automatisch erzeugten Beispielcode beim Erstellen eines neuen Projektes bis zu einer Ambulance-Simulation mit Blaulicht und Sirene. Dabei wird der Zugriff auf Sensoren (Buttons) und Aktoren (LED-Matrix, RGB-LED, Speaker) eingeführt sowie die Verwendung von Schleifen, Logikbausteinen, Zeitgliedern und Variablen. Nach dem Öffnen der .hex-Dateien können die Beispiele sowohl in der Blockansicht, als auch in der JavaScript Ansicht editiert werden.

Um die Codebeispiele in der MakeCode Entwicklungsumgebung zu bearbeiten, sind die folgenden Schritte erforderlich:
1. Zum Download sämtlicher Codebeispiele auf der Startseite des Repositories (https://github.com/mistablinky/Calliope-Ambulance) auf den grünen "Clone or download" Button klicken und anschließend "Download ZIP" auswählen. Im Downloadordner des verwendeten Browsers (z.B. C:\Users\myName\Downloads) wir ein ZIP-Archiv abgelegt, welches dann an eine beliebeige Stelle entpackt werden muss. HowTo-Screenshot: https://github.com/mistablinky/Calliope-Ambulance/blob/master/HowTo/download-from-github.png
2. Zum Öffnen einer .hex-Datei in der MakeCode Entwicklungsumgebung auf "Projekte" am oberen Bildschirmrand und anschließend auf "Datei importieren..." klicken. Danach über "Choose File" die .hex-Datei zum Öffnen auswählen. Dann auf "Los geht's" klicken. Das Codebeispiel wird nun in der Blockansicht angezeigt und kann editiert werden. HowTo-Screenshot: https://github.com/mistablinky/Calliope-Ambulance/blob/master/HowTo/open-in-makecode.png
3. Zum Speichern der Änderungen im MakeCode Editor am unteren Bildschirmrand auf das Diskettensymbol rechts neben dem Projektnamen klicken. Ggf. vor dem Speichern den Projektnamen anpassen. Im Downloadordner des verwendeten Browsers erscheint eine neue .hex-Datei mit der jeweiligen Projektbezeichnung. Bei mehrmaligem Speichern werden die Dateien im Dateinamen in Klammern durchnummeriert, z.B. "mini-myProject (13).hex". HowTo-Screenshot: https://github.com/mistablinky/Calliope-Ambulance/blob/master/HowTo/download-from-makecode.png

Um die Codebeispiele auf den Calliope mini zu übertragen und dort zu starten, sind unter Microsoft Windows die folgenden Schritte erforderlich:
1. Calliope mini per micro-USB Kabel mit dem Comouter verbinden. Im Windows Explorer wird ein zusätzliches Laufwerk mit der Bezeichnung "MINI" angezeigt.
2. .hex-Datei auswählen, mit der Maus auf das MINI-Laufwerkssymbol ziehen und dort loslassen. Die Übertragung auf den Calliope mini startet automatisch und ist am schnellen Blinken der gelben LED auf dem Calliope mini Board zu erkennen. Nach erfolgreicher Übertragung hört die gelbe LED auf zu blinken und leuchtet dauerhaft. Das Programm startet automatisch. HowTo-Screenshot: https://github.com/mistablinky/Calliope-Ambulance/blob/master/HowTo/transfer-to-calliope.png

Die folgenden Codebeispiele sind im Repository enthalten. Die gleichnamigen .png-Grafikdateien zeigen das jeweilige Programm in der Blockansicht:
1. mini-01_Ambulance-1.hex - Neues Projekt: blinkender Smily
2. mini-01_Ambulance-2.hex - Blinkende RGB-LED (Rot/Grün)
3. mini-01_Ambulance-3.hex - Blinkfrequenz steuern duch pausieren
4. mini-01_Ambulance-4.hex - Sound hinzufügen zum Blinkrhythmus
5. mini-01_Ambulance-5.hex - Farben (Rot/Blau) und Sound (Tonhöhe) anpassen für Ambulance Simulation
6. mini-01_Ambulance-6.hex - Einschaltbedingung hinzufügen (wenn Button gedrückt)
7. mini-01_Ambulance-7.hex - Ausschaltbedingung hinzufügen (wenn Button NICHT gedrückt)
8. mini-01_Ambulance-8.hex - 2-Button-Lösung zum dauerhaften Ein-/Ausschalten realisieren
