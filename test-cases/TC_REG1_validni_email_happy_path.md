**Validní registrace (Happy Path)**  
**Název:**
Registrace nového uživatele s validním emailem  
**Priorita:**
High  
**Preconditions:**  
-Uživatel není přihlášen.  
-Uživatel má unikátní e-mail, který ještě není v systému registrován.  
-Uživatel se nachází na homepage webu (https://www.knihydobrovsky.cz/muj-ucet/login#tab=nova-registr
ace)  
**Test Data**
**Email:** martinavyoralova725@gmail.com  
**Heslo:** **************  
**Poznámka:**  
Během testování byly použity reálné přihlašovací údaje z důvodu absence testovacího účtu.  
Z bezpečnostních důvodů nejsou tyto údaje v dokumentaci uvedeny.  
V reálném testovacím prostředí by byly použity testovací účty.  
**Test steps:**  
| Step | Akce | Expected Result |
|------|------|----------------|
| 1 | Otevři webovou stránku https://www.knihydobrovsky.cz/muj-ucet/login#tab=nova-registrace | Stránka se úspěšně načte. Je vidět homepage s registrací. |
| 2 | Vyplň políčka email a heslo. | Email a heslo vyplněno dle pravidel systému. |
| 3 | Vyplň políčko pro kontrolu hesla. | Hesla se shodují. |
| 4 | Klikni na tlačítko Založit účet. | Registrace proběhla úspěšně. Na email přijde potvrzovací email, že registrace proběhla v pořádku. |

**Exekuce:**  
Passed
