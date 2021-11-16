# Situationsbeschreibung 

Cross-Selling bezeichnet Produkte oder Dienstleistungen, die zusätzliche, ergänzende Bedürfnisse des Kunden befriedigen, die durch das ursprüngliche Produkt, das ein Kunde besitzt, nicht hinreichend befriedigt werden. So könnte beispielsweise eine Maus an einen Kunden, der eine Tastatur kauft, weiterverkauft werden. Häufig werden Kunden durch Cross-Selling auf Produkte hingewiesen, die sie ohnehin gekauft hätten; indem man sie zum richtigen Zeitpunkt „vorstellt“, stellt man sicher, dass der Verkauf zustande kommt.
Cross-Selling ist in verschiedenen Bereichen und Branchen weit verbreitet, auch bei Banken. So werden beispielsweise Kreditkarten an Personen verkauft, die ein Sparkonto eröffnen. Im E-Commerce wird Cross-Selling häufig auf Produktseiten, während des Bestellvorgangs und in Lifecycle-Kampagnen eingesetzt. Es ist eine sehr effektive Taktik, um Wiederholungskäufe zu generieren und den Kunden die Breite eines Katalogs zu demonstrieren. Cross-Selling kann Nutzer auf Produkte aufmerksam machen, von denen sie vorher nicht wussten, dass diese angeboten werden und so ihr Vertrauen als der beste Händler für ein bestimmtes Bedürfnis gewinnen.
Als Forschungsteam ProInsurance bestehend aus max. drei Teilnehmer*innen der Hochschule Trier wurden Sie ausgewählt, dass Projekt Cross-Selling-Prediction für den Kunden NextGen Insurance durchzuführen.


![Alt-Text](nextgen_logo.png)

Der Kunde wünscht die Durchführung des Projektes innerhalb eines knapp kalkulierten Zeitraums, da baldige Veränderungen im Jahre 2022 anstehen. Innerhalb eines zugesicherten Abkommens zwischen der Hochschule Trier und NextGen Insurance wurde folgende Projektzeit festgelegt: 

                                    22 November 2021 bis 24 Januar 2022

Das Vorstandsmitglied Fabian Roth, B.Sc. wünscht ein Deployment im Anschluss des Projektzeitraums in Form einer Präsentation, in der die erzielten Ergebnisse vorgestellt werden. Es sollen sowohl technische, als auch ökonomische Aspekte des Projektes beleuchtet werden. Der Zeitpunkt zur Präsentation der Ergebnisse muss noch zur Abstimmung kommen.


# Weiterführende Informationen zur NextGen Insurance

Ihr Kunde ist eine Versicherungsgesellschaft, die ihren Kunden eine Krankenversicherung angeboten hat und nun Ihre Hilfe bei der Erstellung eines Modells benötigt, mit dem sich vorhersagen lässt, ob die Versicherungsnehmer (Kunden) des letzten Jahres auch an einer von der Gesellschaft angebotenen Kfz-Versicherung interessiert sein werden.
Eine Versicherungspolice ist eine Vereinbarung, mit der sich ein Unternehmen verpflichtet, gegen Zahlung einer bestimmten Prämie eine Entschädigung für einen bestimmten Verlust, Schaden, eine Krankheit oder einen Todesfall zu garantieren. Eine Prämie ist ein Geldbetrag, den der Kunde regelmäßig an eine Versicherungsgesellschaft für diese Garantie zahlen muss.
Zum Beispiel können Sie jedes Jahr eine Prämie von 5000 Rs. für eine Krankenversicherung von 200.000 Rs zahlen, so dass die Versicherungsgesellschaft die Kosten für den Krankenhausaufenthalt usw. bis zu einer Höhe von 200.000 Rs übernimmt, falls Sie, Gott behüte, in diesem Jahr krank werden und ins Krankenhaus müssen. Wenn Sie sich nun fragen, wie die Gesellschaft so hohe Krankenhauskosten tragen kann, wenn sie eine Prämie von nur 5000 Rs erhebt, dann kommt hier das Konzept der Wahrscheinlichkeiten ins Spiel. Zum Beispiel gibt es vielleicht 100 Kunden, die jedes Jahr eine Prämie von 5000 Rs zahlen, aber nur ein paar von ihnen (sagen wir 2-3) werden in diesem Jahr ins Krankenhaus eingeliefert und nicht alle. Auf diese Weise teilen sich alle das Risiko der anderen.
Genau wie bei der Krankenversicherung muss der Kunde auch bei der Kfz-Versicherung jedes Jahr eine bestimmte Prämie an die Versicherungsgesellschaft zahlen, damit diese im Falle eines unglücklichen Unfalls mit dem Fahrzeug eine Entschädigung (die so genannte "Versicherungssumme") an den Kunden zahlt.
Die Erstellung eines Modells zur Vorhersage, ob ein Kunde an einer Kfz-Versicherung interessiert ist, ist für das Unternehmen äußerst hilfreich, da es dann seine Kommunikationsstrategie entsprechend planen kann, um diese Kunden zu erreichen und sein Geschäftsmodell und seine Einnahmen zu optimieren.
Um vorherzusagen, ob ein Kunde an einer Kfz-Versicherung interessiert ist, benötigt man Informationen über demografische Daten (Geschlecht, Alter, Regionalcode), Fahrzeuge (Fahrzeugalter, Schäden), Policen (Prämie, Vertriebskanal) usw.


Der Kunde NextGen Insurance hat dem Forschungsteam ProInsurance ein Data Dictionary zur Verfügung gestellt: 

| Variable             |  Definition |
|----------------------|---|
| id                   |  Unique ID for the customer |
| gender               | Gender of the customer  |
| age                  |  Age of the customer |
| driving_license      |  0 : Customer doesn't have DL, 1 : Customer has DL |
| region_code          |  Unique code for the region of the customer |
| previously_insured   |  0 : Customer doesn't have Vehicle Insurance, 1 : Customer has Vehicle Insurance |
| vehicle_age          |  Age of the Vehicle |
| vehicle_damage      |  1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past. |
| annual_premium       |  The amount customer needs to pay as premium in the year for Health insurance |
| policy_sales_channel |  Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc. |
| vintage              |  Number of Days customer has been associated with the company |
| response             |  1 : Customer is interested, 0 : Customer is not interested |

