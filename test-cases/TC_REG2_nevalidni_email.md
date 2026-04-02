**Název:**  
Registrace nového uživatele s nevalidním emailem   
**Priorita:**
High  
**Preconditions:**  
-Uživatel není přihlášen.  
-Uživatel má unikátní e-mail, který ještě není v systému registrován.  
-Uživatel se nachází na homepage webu (https://www.knihydobrovsky.cz/muj-ucet/login#tab=nova-registrace)  
**Test Data:**  
a)Email  
| ID | Scénář | Test Data | Výsledek |
|----|--------|-----------|----------|
| 1 | Chybí @ | test.cz | Zobrazí se chybová hláška |
| 2 | Prázdné pole | (prázdné) | Zobrazí se chybová hláška |
| 3 | Chybí doména | test@ | Zobrazí se chybová hláška |
| 4 | Chybí jméno | @seznam.cz | Zobrazí se chybová hláška |

b)Heslo:  
Test212345  

**Test steps:**  
| Step | Akce | Expected Result |
|------|------|----------------|
| 1 | Otevři webovou stránku https://www.knihydobrovsky.cz/muj-ucet/login?userAction=nova-registrace&_fid=jh2h#tab=nova-registrace | Stránka se úspěšně načte. Je vidět homepage s registrací. |
| 2 | Vyplň email z Test Data. Postupně vyzkoušej jednotlivé varianty (1–4). | Objeví se chybová hláška. |    


**Exekuce:**  
Passed
