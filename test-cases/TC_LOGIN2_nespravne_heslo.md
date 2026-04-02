**Název:**  
Zadání nesprávného hesla  
**Priorita:**  
Medium  
**Preconditions:**  
-Uživatel je registrován a provedl aktivaci účtu prostřednictvím potvrzovacího e-mailu  
-Má platné přihlašovací údaje  
-Webová stránka pro přihlášení https://www.knihydobrovsky.cz/  
**Test data:**  
Email: martinavyoralova725@gmail.com  
Heslo: Test001  
**Test steps:**  
| Step | Akce | Expected Result |
|------|------|----------------|
| 1    | Otevři stránku pro přihlášení [https://www.knihydobrovsky.cz/](https://www.knihydobrovsky.cz/) | Stránka se načetla. Jsou zde viditelné pole pro zadání loginu a hesla. |
| 2    | Vyplň pole Email, Heslo a klikni na tlačítko Přihlásit se. | Objeví se chybová hláška, která upozorní na nesprávně vyplněné heslo. |


**Exekuce:**  
Passed
