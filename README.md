ETF-Vorsorgerechner - 
Ein präzises, browserbasiertes Werkzeug zur instationären Simulation des Kapitalaufbaus und der anschließenden Entnahmephase unter Berücksichtigung deutscher Steuer- und Inflationsparameter.

Übersicht

Dieser Rechner wurde entwickelt, um Vorsorgelücken mit der Genauigkeit einer technischen Simulation zu ermitteln. Im Gegensatz zu einfachen Online-Rechnern berücksichtigt dieses Tool die deutsche Investmentbesteuerung und ermöglicht komplexe Entnahmeszenarien.

Funktionsumfang

Instationäre Simulation: Jährliche Berechnung des Kapitalstocks unter Berücksichtigung von Rendite, Dynamik und Steuern.

Steuerliche Präzision: Integration der Vorabpauschale (InvStG 2018) und der 30%igen Teilfreistellung für Aktien-ETFs.

Phasen-Entnahmemodell: Abbildung sinkender Mittelbedarfe im hohen Alter (Aktivitäts- vs. Passivitätsphase).

Strategiewahl: Umschaltbar zwischen realem Kapitalerhalt (Ewige Rente) und vollständigem Kapitalverzehr (Depletion).

Sensitivitätsanalyse: Wärmekarte zur Visualisierung des nominalen Bedarfs und des notwendigen Kapitals in Abhängigkeit von Inflation und Lebensalter.

Zielwertsuche: Automatisierte Ermittlung der notwendigen Sparrate oder Rendite zur Deckung der kalkulierten Lücke.

Mathematische Grundlagen

Akkumulation

Die Simulation erfolgt diskret in Jahresschritten, wobei die monatlichen Sparraten verzinst und die steuerlichen Belastungen (Vorabpauschale) jährlich vom Bestand subtrahiert werden.

Entnahme

Das erforderliche Zielkapital wird über das Barwertverfahren ermittelt:

Erhalt: $K = \frac{R}{r_{real}}$ (Ewige Rente unter Berücksichtigung der Steuerbelastung auf die Entnahme).

Verzehr: Rentenbarwertformel über einen endlichen Zeithorizont.

Nutzung

Die Anwendung ist als Single-File-App konzipiert. Es ist keine Installation oder Backend-Infrastruktur erforderlich.

Datei vorsorgerechner.html herunterladen.

In einem aktuellen Webbrowser öffnen.

Sämtliche Berechnungen finden lokal im Browser statt (Datenschutz durch lokale Ausführung).

Technische Details

Frontend: HTML5, Tailwind CSS

Icons: Lucide Icons

Lizenz: MIT

Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert - siehe den Header in der vorsorgerechner.html für Details.
