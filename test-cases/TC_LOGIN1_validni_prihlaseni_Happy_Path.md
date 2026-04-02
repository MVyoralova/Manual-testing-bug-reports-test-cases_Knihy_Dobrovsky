**Název:**  
Ověření přihlášení s platnými údaji  
**Priorita:**
High  
**Preconditions:**  
-Uživatel je registrován a provedl aktivaci účtu prostřednictvím potvrzovacího e-mailu  
-Má platné přihlašovací údaje  
-webová stránka pro přihlášení https://www.knihydobrovsky.cz/  
**Test data:**  
Email: martinavyoralova725@gmail.com  
Heslo: *******  
**Poznámka:**  
Během testování byly použity reálné přihlašovací údaje z důvodu absence testovacího účtu.
Z bezpečnostních důvodů nejsou tyto údaje v dokumentaci uvedeny.
V reálném testovacím prostředí by byly použity testovací účty.  
| Step | Akce | Expected Result |
|------|------|----------------|
| 1    | Otevři stránku pro přihlášení [https://www.knihydobrovsky.cz/](https://www.knihydobrovsky.cz/) | Stránka se načetla. Jsou zde viditelné pole pro zadání loginu a hesla. |
| 2    | Vyplň pole Email, Heslo a klikni na tlačítko Přihlásit se. | Uživatel je úspěšně přihlášen a přesměrován na domovskou stránku. |  

**Exekuce:**  
Passed
