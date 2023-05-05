# Teil 1: AI Text Classifier austricksen
**ACHTUNG! Du musst mindestens 13 Jahre alt sein, um die Dienste von OpenAI zu nutzen. Bitte die Erlaubnis Deiner Eltern holen** (wenn du älter als 13 Jahre bist, aber noch unter 18 Jahre alt)**, um die Dienste von OpenAI zu nutzen.**

## Was Du brauchst
OpenAI-Konto

Dafür benötigt man:
1. Handynummer
2. e-Mail Konto 

**!!! WICHTIG!!!** 
Laut der OpenAI FAQ ist es momentan nicht möglich die Verknüpfung Deiner Handynummer  mit dem Konto aufzuheben, siehe https://help.openai.com/en/articles/6613520-phone-verification.

## Erstellung OpenAI Konto
1. Geh zu dieser Webseite: https://platform.openai.com/ai-text-classifier
2. Klicke "Sign up", um ein Konto zu erstellen.
3. Gib Deine Email-Adresse ein und drücke auf „Continue“. (Alternativ kannst DU mit Deinem Google, Facebook, oder Microsoft-Konto anmelden.)
4. Gib ein valides Passwort ein und drücke auf „Continue“.
5. Verifiziere deine Email in dem du zu Deinem Email-Programm gehst und die Email von OpenAI öffnest. Drücke dort „Verify email address“.
6. Du wirst auf eine neue Seite weitergeleitet. Gib dort deinen Vor- und Nachnamen an und drücke auf „Continue“.
7. Gib deine Handynummer (lass die 0 am Anfang weg) an und drücke auf „Send code“.
8. Schau auf dein Handy und gib den 6-stelligen Code aus der SMS ein.
9. Direkt danach wirst du zu deinem OpenAI-Account weitergeleitet. 

## Derzeitige Beschränkungen des AI Text Classifiers (April 2023)
* Der AI Text Classifier benötigt einen Text mit mindestens 1.000 Zeichen (ca. 150 - 250 Wörter).
* Der Klassifikator ist so eingestellt, dass er einen Text nur dann als KI-generiert einstuft, wenn er sehr sicher ist. KI-generierter Text kann daher leicht bearbeitet werden, um den Klassifikator zu umgehen. Dennoch kann er einen von Menschen erstellten Text fälschlicherweise als KI-Text klassifizieren.
* Der Klassifikator wird wahrscheinlich von Kindern geschriebene Texte und nicht-englische Texte falsch klassifizieren, da er in erster Linie auf englische Inhalte trainiert wurde, die von Erwachsenen geschrieben wurden.

## Können wir herausfinden, wann die AI den Text falsch klassifiziert?
Was sind Eure Strategien, um die AI auszutricksen,
1. von Menschen geschriebene Texte als AI-generierte Text zu klassifizieren?
2. AI-generierte Text als von Menschen geschriebene Text zu klassifizieren?

## Ein Vorgehen, dass Du probieren kannst
### von Menschen geschriebene Texte als KI-generiert falsch klassifizieren
1. Nimm einen englischen Text, der von einem Menschen geschrieben wurde (z. B. Deinen englischen Aufsatz oder eine Passage aus einem englischen Buch). Was ist das Ergebenis?
2. Verwende Google Translate oder DeepL, um den Text in eine andere Sprache (z. B. Deutsch) und dann wieder zurück ins Englische zu übersetzen. Bewertet der Klassifikator den Text anders?

### KI-generierte Texte als von Menschen geschrieben falsch klassifiziert
1. Lass ChatGPT einen englischen Aufsatz über ein Thema schreiben. Wie bewertet der AI-Text Classifier?
2. Lass ChatGPT den Aufsatz in der Stil eines Kinds umschreiben. Ändert sich die Bewertung?
3. Versuch mal mit den Text, der anhand Google Translate oder DeepL vom Englischen ins Nicht-Englische übersetzt wurde.
4. Was passiert, wenn wir Teile des Aufsatz selber umschreiben?
5. Was passiert, wenn wir grammatikalische Fehler hinzufügen?
6. Lass ChatGPT einen Aufsatz auf Deutsch schreiben.
7. Lass ChatGPT eine Gedichte (Deutsch oder Englisch) schreiben.

## Überlegst mal ...
1. Was sind die Gefahr, Deine Schulaufgabe immer an ChatGPT zu verlassen?
2. Magst Du die Antwort von ChatGPT? Warum? Warum nicht?
2. Was sind die Gefahr, wenn die AI Text Classifier falsch entscheidet?

## Halluzination von ChatGPT
Manchmal antwortet ChatGPT, als ob es absolut sicher ist. Allerdings sind die Antwort völlig falsch. Dies betrifft insbesondere auf sehr spezifishce Themen.
Probiere diese Anfrage:

```
Can you use Stable Diffusion for Fraud Detection?
```

ChatGPT wird sehr überzeugend antworten. Frage ihm nach die Quelle:

```
Please give me the sources or research papers on this idea.
```

Suche in Search Engine wie Google, DuckDuckGo, oder Bing nach dieser Quellen. Einige davon existieren gar nicht.

<img
  src="Teil1_AITextClassifier\images\can_you_use_stable_diffusion_for_fraud_detection.jpg"
  alt="ChatGPT_NeueIdeen"
  title="Möglicherweise hat ChatGPT Stable Distribution mit Stable Diffusion verwechselt.">


<img
  src="Teil1_AITextClassifier\images\sources.png"
  alt="ChatGPT_Halluzination"
  title="Einige Quelle existieren gar nicht.">


