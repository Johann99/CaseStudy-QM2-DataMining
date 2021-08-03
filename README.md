# Fraud-Detection-on-Selfcheckout-Registers

Kontext
Fallstudie zur Vorlesung Data Mining Betrugserkennung an Selbstzahlerkassen im Einzelhandel
Prof. Dr. Michael Bücker, Lutz Dapper 05.11.2020
Die Supermarktkette “Frischwerk” sieht sich steigendem Druck durch die expandierende Konkurrenz aus- gesetzt. Zur Senkung der Personalkosten bei gleichzeitiger Erhöhung der Servicequalität setzt Frischwerk seit geraumer Zeit auf Self-Checkout-Stationen. An diesen Stationen können Kundinnen und Kunden ihre Produkte selbst scannen und direkt bezahlen. Das Angebot der Self-Checkout-Stationen hilft, lange Schlangen zu vermeiden und beschleunigt den Zahlungsprozess für einzelne Personen. Allerdings bietet es auch die Möglichkeit beim Scannen der Produkte zu betrügen.
Um betrügerisches Handeln zu identifizieren ohne unschuldige Kundinnen und Kunden durch Kontrollen zu verärgern, hat das Unternehmen Sie und Ihr Team als externe Beratung beauftragt, ein Modell zu entwickeln, welches die Betrugswahrscheinlichkeit bei Self-Checkout Einkäufen ermittelt. Ihr Auftrag ist nun, mit Hilfe von erhobenen Daten ein performantes Modell für die Vorhersage bzw. Erkennung von Betrügereien zu entwickeln und die Treiber für den Betrug zu ermitteln.
Bei der Erstellung des Klassifikationsmodells sollen folgende Kosten & Erträge berücksichtigt werden:
Wahrheit(Kein Betrug) & Vorhersage(Kein Betrug): 0EUR 
Wahrheit(Kein Betrug) & Vorhersage(Betrug): 25EUR 
Wahrheit(Betrug) & Vorhersage(Kein Betrug): -5EUR 
Wahrheit(Betrug) & Vorhersage(Betrug): 5EUR 


Die Tabelle zeigt, dass jeder korrekt identifizierte Betrugsversuch durchschnittlich einen zusätzlichen Ertrag von 5 EUR einbringt. Jeder nicht aufgedeckte Betrugsversuch verursacht hingegen 5 EUR Kosten für Frischwerk. Kundinnen und Kunden, die fälschlicherweise des Betrugs beschuldigt werden, kehren möglicherweise nicht mehr zu Frischwerk zurück, was einen Verlust von durchschnittlich 25 EUR für den Supermarkt bedeutet. Korrekt identifizierte ehrliche Kundinnen und Kunden bedeuten für Frischwerk weder Gewinn noch Verlust.
