# Calliope Ambulance
Erste Schritte mit Calliope mini

Der Calliope mini ist ein Entwicklungsboard für den einfachen Einstieg in die digitale Welt und in die Programmierung. Der Einstieg ist möglich ohne weitere Vorkenntnisse. Weitere Informationen unter https://calliope.cc/.

Dieses Respository enthält Codebeispiele für die Microsoft MakeCode Entwicklungsumgebung unter https://makecode.calliope.cc/. Die Beispiele führen Schritt für Schritt vom automatisch erzeugten Beispielcode beim Erstellen eines neuen Projektes bis zu einem "Ambulace" Blaulicht mit Sirene. Dabei wird der Zugriff auf Sensoren (Buttons) und Aktoren (LED-Matrix, RGB-LED, Speaker) eingeführt sowie die Verwendung von Schleifen, Logikbausteinen, Zeitgliedern und Variablen. Nach dem Öffnen der hex-Dateien können die Beispiele sowohl in der Blockansicht, als auch in der JavaScript Ansicht editiert werden.

Um die Codebeispiele auf den Calliope mini zu übertragen und dort zu starten, sind unter Microsoft Windows die folgenden Schritte erforderlich:
1. Calliope mini per micro-USB Kabel mit dem Comouter verbinden. Im Windows Explorer wird ein zusätzliches Laufwerk mit der Bezeichnung "MINI" angezeigt.
2. Im MakeCode Editor am unteren Bildschirmrand auf das Diskettensymbol rechts neben dem Projektnamen klicken. Ggf. vor dem Speichern den Projektnamen anpassen. Im Downloadordner des verwendeten Browsers (z.B. C:\Users\myName\Downloads) erscheint eine neue hex-Datei mit der jeweiligen Projektbezeichnung. Bei mehrmaligem Speichern werden die Dateien im Dateinamen in Klammern durchnumeriert (z.B. mini-myProject (13).hex).
3. Die hex-Datei mit der Maus auf das MINI-Laufwerkssymbol ziehen und dort loslassen. Die Übertragung auf den Calliope mini startet automatisch und ist am schnellen Blinken der gelben LED auf dem Calliope mini Board zu erkennen. Nach Beendigung der Übertragung hört die gelbe LED auf zu blinken und leuchtet dauerhaft. Das Programm startet automatisch.

Die folgenden Codebeispiele sind im Repository enthalten. Die gleichnamigen Grafikdateien mit der Endung "png" zeigen das jeweilige Programm in der Blockansicht:
1. mini-01_Ambulance-1.hex - Neues Projekt: blinkender Smily
2. mini-01_Ambulance-2.hex - Blinkende RGB-LED (Rot/Grün)
3. mini-01_Ambulance-3.hex - Blinkfrequenz steuern duch pausieren
4. mini-01_Ambulance-4.hex - Sound hinzufügen zum Blinkrhythmus
5. mini-01_Ambulance-5.hex - Farben und Sound anpassen für Ambulance Simulation
6. mini-01_Ambulance-6.hex - Einschaltbedungung hinzufügen (wenn Button gedrückt)
7. mini-01_Ambulance-7.hex - Ausschaltbedungung hinzufügen (wenn Button NICHT gedrückt)
8. mini-01_Ambulance-8.hex - 2-Button-Lösung zum Ein-/Ausschalten realisieren
