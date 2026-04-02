**Název:**  
Ověření zobrazení a funkčnosti produktové stránky  
**Priorita:**  
Medium  
**Preconditions:**  
-Uživatel je na webu Knihy Dobrovský  
-Existují produkty odpovídající testovacím datům  
**Test data:**  
| ID  | Název produktu | Autor               | Vazba | Cena  | Popis                       |
|-----|----------------|-------------------|-------|-------|-----------------------------|
| 1   | Pomocnice      | Freida McFadden   | Pevná | 357,- | Obsahuje krátký popis produktu |
| 2   | Les v domě     | Alena Mornštajnová | Měkká | 219,- | Obsahuje krátký popis produktu |  

**Test steps:**  
| Step | Akce | Expected Result |
|------|------|----------------|
| 1    | Na hlavní stránce použij vyhledávání a zadej název produktu z test data, poté otevři stránku produktu | Stránka produktu se načte úspěšně, zobrazí se hlavní prvky: obrázky, název, autor, vazba, cena, popis. |
| 2    | Ověř zobrazení všech obrázků produktu | Obrázky jsou zobrazeny správně, odpovídají produktu, galerie/zoom funguje. |
| 3    | Ověř zobrazení popisu produktu | Název, autor, vazba, cena a popis odpovídají test data. |  


**Exekuce:**  
Passed
