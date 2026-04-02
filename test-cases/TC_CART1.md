**Název:**  
Ověření funkčnosti košíku (přidání a odebrání produktu)  
**Priorita:**  
Medium  
**Preconditions:**  
-Uživatel je na webu Knihy Dobrovský  
-Existují produkty odpovídající testovacím datům  

**Test data:**  
| ID  | Název produktu | Autor               | Vazba | Cena  |
|-----|----------------|-------------------|-------|-------|
| 1   | Pomocnice      | Freida McFadden   | Pevná | 357,- |
| 2   | Les v domě     | Alena Mornštajnová | Měkká | 219,- |  

**Test steps:**  
| Step | Akce | Expected Result |
|------|------|----------------|
| 1    | Vyhledej produkt [Název produktu] z test data a otevři jeho stránku | Produktová stránka se načte, zobrazují se hlavní prvky: název, cena, tlačítko „Přidat do košíku“. |
| 2    | Klikni na tlačítko „Přidat do košíku“ | Produkt se úspěšně přidá do košíku. |
| 3    | Klikni na tlačítko „Pokračovat do košíku“ | Košík zobrazuje správně přidaný produkt, jeho cenu a množství. |
| 4    | Odeber produkt z košíku | Produkt je odstraněn, košík se aktualizuje, případně se zobrazí hláška „Košík je prázdný“. |

**Exekuce:**  
Passed
