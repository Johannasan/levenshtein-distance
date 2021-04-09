# Arbetsprov
Genom att tillämpa testdriven utveckling (TDD), skriv en metod som returnerar Levenshteinavståndet mellan två godtyckliga strängar.

Levenshteinavståndet beräknas som summan av det antal raderingar, infogningar och substitueringar av tecken som krävs för att transformera den ena strängen till den andra.

## Utförande
För att underlätta arbetsprovet har vi skapat ett projekt konfigurerat för Maven. Det innehåller beroenden vi ofta använder vid TDD.

Gör en fork av detta projekt där ni utför ert arbetsprov och meddela kontaktperson en länk till er fork när ni är färdig med er lösning.

## Exempel på levenshteinavstånd
| Originaltext | Önskad text | Levenshteinavstånd |
|--------------|-------------|--------------------|
| a            | a           | 0                  |
| a            | A           | 1                  |
| Kalle        | Carlsson    | 6                  |
| Alice        | Bob         | 5                  |
| Catharina    | Katrin      | 4                  |

## Mer detaljerad information om Levenshteinavstånd

* [Engelska Wikipedia](https://en.wikipedia.org/wiki/Levenshtein_distance)
* [Svenska Wikipedia](https://sv.wikipedia.org/wiki/Levenshteinavst%C3%A5nd)
* [Understanding the Levenshtein Distance Equation for Beginners](https://medium.com/@ethannam/understanding-the-levenshtein-distance-equation-for-beginners-c4285a5604f0)
* [The Levenshtein Algorithm](https://www.cuelogic.com/blog/the-levenshtein-algorithm)
* [Online-kalkylator](https://planetcalc.com/1721/) för att beräkna Levenshteinavstånd
* [How to Calculate Levenshtein Distance in Java?](https://www.baeldung.com/java-levenshtein-distance)
