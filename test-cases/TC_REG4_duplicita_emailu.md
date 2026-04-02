**Název:**  
Registrace nového uživatele s duplicitním emailem  
**Priorita:**    
Medium  
**Preconditions:**  
-Uživatel není přihlášen.  
-Uživatel má unikátní e-mail, který ještě není v systému registrován.  
-Uživatel se nachází na homepage webu (https://www.knihydobrovsky.cz/muj-ucet/login#tab=nova-registrace)  
**Test Data:**  
Email: martinavyoralova725@gmail.com  
Heslo: *******  
**Poznámka:**  
Během testování byly použity reálné přihlašovací údaje z důvodu absence testovacího účtu.
Z bezpečnostních důvodů nejsou tyto údaje v dokumentaci uvedeny.
V reálném testovacím prostředí by byly použity testovací účty.  
**Test steps:**  
| Step | Akce | Expected Result |
|------|------|----------------|
| 1    | Otevři webovou stránku [https://www.knihydobrovsky.cz/muj-ucet/login?userAction=nova-registrace&_fid=jh2h#tab=nova-registrace](https://www.knihydobrovsky.cz/muj-ucet/login?userAction=nova-registrace&_fid=jh2h#tab=nova-registrace) | Stránka se úspěšně načte. Je vidět homepage s registrací. |
| 2    | Vyplň email z Test Data. | Email lze vyplnit do kolonky. |
| 3    | Vyplň do kolonky Heslo a Heslo (pro kontrolu) hesla z Test Data. | Heslo a Heslo (pro kontrolu) jsou vyplněna a shodují se. |
| 4    | Klikni na tlačítko Založit účet. | Objeví se chybová hláška “Tento e-mail již používá jiný uživatel.” |

**Exekuce:**  
Passed

