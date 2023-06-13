# Advanced-ML-Project Semester 6

## Deadlines
13.06.2023 Vorstellung des Themas und ggf- möglichen Vorgehensweise und Techniken <br>
[wepik-sprachgesteuerte-zukunft-wie-wir-iot-gerate-mit-unserer-stimme-kontrollieren-20230612180548DyTB.pdf](https://github.com/Chengyi-Hua/Advanced-ML-Project/files/11731847/wepik-sprachgesteuerte-zukunft-wie-wir-iot-gerate-mit-unserer-stimme-kontrollieren-20230612180548DyTB.pdf)
<br>
<br>
27.6.: Präsentation des Zwischenstands:<br>
<br>
23.07.2023 Abgabe Dokumentation etc. <br>
<br>
26.07.2023 Präsentation

<img width="574" alt="image" src="https://github.com/Chengyi-Hua/Advanced-ML-Project/assets/96745479/97a7f7d6-13d9-4c5e-98d5-651d3b6ba9e8">

## Thema: Die Steuerung von IoT-Geräten mittels Spracherkennung (LLM)
Kombiniert die Konzepte der Spracherkennung und der IoT-Geräteverwaltung. Hierbei ermöglicht es eine Sprachsteuerung, IoT-Geräte über gesprochene Befehle zu steuern und zu kontrollieren. Dies eröffnet Benutzern die Möglichkeit, ihre IoT-Geräte intuitiv und ohne manuelle Eingriffe zu bedienen. Die Implementierung einer solchen Lösung erfordert die Integration von Spracherkennungstechnologie, NLP-Funktionalität und IoT-Geräteverwaltungskomponenten. <br>

- Spracherkennung: Ein Spracherkennungssystem, das die gesprochenen Worte des Benutzers in Text umwandelt. Dies kann durch APIs oder Spracherkennungsbibliotheken wie Google Cloud Speech-to-Text, Mozilla DeepSpeech oder CMU Sphinx erfolgen.

- NLP: Eine NLP-Komponente zur Verarbeitung und Interpretation des vom Benutzer gesprochenen Texts. Diese Komponente analysiert die Benutzereingabe, extrahiert die beabsichtigte Bedeutung und übersetzt sie in Befehle oder Anweisungen für die IoT-Geräte. NLP-Frameworks wie spaCy, NLTK oder Hugging Face Transformers können hier eingesetzt werden.

- IoT-Geräteverwaltung: Eine Plattform oder ein Framework zur Verwaltung der IoT-Geräte und ihrer Funktionen. Dies umfasst die Geräteidentifizierung, die Konnektivität, die Kommunikation mit den Geräten, die Bereitstellung von Firmware-Updates und die Durchführung von Aktionen basierend auf den Sprachbefehlen. Beliebte IoT-Geräteverwaltungsplattformen sind beispielsweise AWS IoT, Google Cloud IoT oder Microsoft Azure IoT Hub.

- Integration und Backend: Ein Backend-System, das die Spracherkennung, NLP-Verarbeitung und IoT-Geräteverwaltung integriert. Dieses System übernimmt die Verarbeitung der Benutzereingabe, generiert die entsprechenden IoT-Befehle und steuert die Kommunikation mit den Geräten. Die Integration kann in einer serverbasierten Umgebung erfolgen, entweder lokal oder in der Cloud.

- Hardware: Die Hardware besteht aus den IoT-Geräten, die gesteuert werden sollen. Der Raspberry Pi 3, äußerst vielseitiger und leistungsfähiger Einplatinencomputer, der sich ideal für die Integration und Steuerung von IoT-Geräten eignet, wird für die Kommunikation zu IoT Geräten verwendet. Mit seinen zahlreichen GPIO-Pins, drahtlosen Konnektivitätsoptionen und der Fähigkeit, verschiedene Betriebssysteme auszuführen, bietet der Raspberry Pi 3 eine solide Grundlage für die Umsetzung eines IoT-Projekts.


## Use Case
Max ist ein leidenschaftlicher Bastler und Technikliebhaber, der sein Zuhause in ein intelligentes Smart Home verwandeln möchte. Er entscheidet sich für die Implementierung einer sprachgesteuerten IoT-Geräteverwaltung, um seine Lampen und einen Temperatursensor bequem per Sprachbefehl zu steuern. Als Teil seines Projekts baut Max ein Modell aus Pappe, um das System zu visualisieren und zu testen.

### In-scope
- Die Verbindung und Steuerung von IoT-Geräten wird mithilfe eines Raspberry Pi 3 erreicht
- Das System nutzt eine Spracherkennungstechnologie, um die Spracheingabe von Max zu erfassen und in Text umzuwandeln. 
- Max gibt Sprachbefehle wie "Schalte das Wohnzimmerlicht ein" oder "Was ist die aktuelle Raumtemperatur?" ab.
- Die NLP-Komponente analysiert den erfassten Text und erkennt die beabsichtigte Aktion sowie die betroffenen Geräte.
- Basierend auf der Interpretation der Benutzereingabe generiert das System die entsprechenden Steuerbefehle für die IoT-Geräte in Max' Smart Home-Modell.
- Die Lampen im Modellhaus werden ein- oder ausgeschaltet, und der Temperatursensor zeigt die aktuelle Raumtemperatur an.

### Kann
- Das System kann auch Feedback geben, indem es zum Beispiel die Sprachausgabe verwendet, um Max die aktuelle Temperatur mitzuteilen.

### Out-scope
- Keine Speicherung von Daten in Datenbanken

Motivation des Projektes:
- Intuitive Steuerung: Max kann seine IoT-Geräte in seinem Smart Home-Modell einfach per Sprachbefehl steuern, indem er den Namen der Geräte und die gewünschte Aktion nennt.
- Visualisierung und Fehlerbehebung: Das Modell ermöglicht es Max, den aktuellen Status der Lampen und den Temperatursensor auf einen Blick zu überprüfen und Fehler im System zu erkennen.

Interaktive Erfahrung: Das Modellhaus aus Pappe bietet eine interaktive und greifbare Darstellung des Smart Home-Systems, das Max entwickelt hat.
Prototyping und Testing: Durch den Aufbau des Modells aus Pappe kann Max das System vor der tatsächlichen Implementierung im realen Zuhause testen und mögliche Probleme frühzeitig identifizieren.

## To Do´s 
- Defining Project in-scope and out-scopes
- Gathering of needed requirements and develope a implementation plan
- Assigning workload
