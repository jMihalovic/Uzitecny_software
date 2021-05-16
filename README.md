# Užitečný Software
## Verze 1

Jakub Mihalovič <br/>
mihalovic.jakub.2018@skola.ssps.cz <br/>
16. 5. 2021

* Úvod
  * Tento dokument slouží k ustanovení funkcí programu
  * Kontakt
    * Jakub Mihalovič mihalovic.jakub.2018@skola.ssps.cz
* Celkový popis
  * Cílem je vytvořit program s jednoduchou filmovou databází. Lze do něj jednoduše přidávat a odebírat položky. Prvky bude také možné filtrovat a seřazovat.
  * Program může používat každý uživatel PC
* Požadavky na rozhraní
  * WPF
  * Windows
* Vlastnosti systému
  1. Vytvoření prvku
    * Vstup : Tlačítko pro přidání. Nové okno pro vyplnění parametrů
    * Akce : Vyplnění parametrů a potvrzení
    * Výstup : Přidaný prvek na seznam prvků
    * Výstup : Chybové hlášení při nesprávném zadání parametrů
  2. Editace prvku
    * Vstup : Tlačítko pro editaci. Nové okno pro změnu parametrů
    * Akce : Změna parametrů a potvrzení
    * Výstup : Změněný prvek na seznamu prvků
    * Výstup : Chybové hlášení při nesprávném zadání parametrů
  3. Smazání prvku
    * Vstup : Tlačítko pro Smazání
    * Akce : Potvrzení smazání
    * Výstup : Smazaný prvek
  4. Filtrování a seřazení prvků
    * Vstup : Tlačítko pro seřazení a filtraci.
    * Akce : Změna seřazení podle nabídky, filtrace podle parametrů
    * Výstup : Seřazené a vyfiltrované prvky
