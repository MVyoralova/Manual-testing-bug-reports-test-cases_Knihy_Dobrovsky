**Název:**  
Ověření funkčnosti filtrů  
**Priorita:**  
Medium  
**Preconditions:**  
-Uživatel je na webu Knihy Dobrovský  
-Funkce vyhledávání je dostupná  
-Existují produkty odpovídající hledanému výrazu  

**Test data:**  
| ID  | Filtr       | Hodnota                       | Popis                                                                 |
|-----|------------|-------------------------------|----------------------------------------------------------------------|
| 1   | Autor       | Rebeca Yarros                 | Zobrazené produkty odpovídají zadaným filtrům                        |
| 2   | Autor       | Neexistující autor             | Zobrazí se prázdný seznam výsledků nebo odpovídající hláška (např. ‚Nebyly nalezeny žádné produkty‘) |
| 3   | Vazba       | Pevná                         | Zobrazené produkty odpovídají zadaným filtrům                        |
| 4   | Vazba       | Měkká                         | Zobrazené produkty odpovídají zadaným filtrům                        |
| 5   | Vazba       | Leporelo                       | Zobrazené produkty odpovídají zadaným filtrům                        |
| 6   | Kombinace   | Autor (Rebeca Yarros) + pevná vazba | Zobrazené produkty odpovídají zadaným filtrům                        |
| 7   | Kombinace   | Autor (Rebeca Yarros) + měkká vazba | Zobrazené produkty odpovídají zadaným filtrům                        |
| 8   | Kombinace   | Autor (Rebeca Yarros) + leporelo | Zobrazí se prázdný seznam výsledků nebo odpovídající hláška (např. ‚Nebyly nalezeny žádné produkty‘) |

**Test steps:**  
| Step | Akce | Expected Result |
|------|------|----------------|
| 1    | Jdi na webovou stránku knihy Dobrovský [https://www.knihydobrovsky.cz/](https://www.knihydobrovsky.cz/) | Domovská stránka se úspěšně načte a zobrazí se její hlavní prvky (např. menu, vyhledávací pole, nabídka produktů). |
| 2    | Klikni v menu na Knihy | Načte se stránka s možností použít filtry. Filtr se nachází v levé části webové stránky. |
| 3    | Najdi ve filtru vyhledávání dle “viz test data” | Filtr umožňuje vyhledávání podle zadaných testovacích dat. |

**Exekuce:**  
Passed
