**Název:**  
Při registraci nového uživatele není v poli Heslo splněn požadavek na minimální počet číslici  
**Priorita:**    
Medium  
**Preconditions:**  
-Uživatel není přihlášen.  
-Uživatel má unikátní e-mail, který ještě není v systému registrován.  
-Uživatel se nachází na homepage webu (https://www.knihydobrovsky.cz/muj-ucet/login#tab=nova-registrace)  
**Test Data:**  
Email: martatest@seznam.cz  
Heslo: Marantakuku  

| Step | Akce | Expected Result |
|------|------|----------------|
| 1    | Otevři webovou stránku [https://www.knihydobrovsky.cz/muj-ucet/login?userAction=nova-registrace&_fid=jh2h#tab=nova-registrace](https://www.knihydobrovsky.cz/muj-ucet/login?userAction=nova-registrace&_fid=jh2h#tab=nova-registrace) | Stránka se úspěšně načte. Je vidět homepage s registrací. |
| 2    | Vyplň email z Test data. | Email lze vyplnit do kolonky. |
| 3    | Vyplň do kolonky Heslo - heslo. | Objeví se chybová hláška. |

**Exekuce:**   
Passed  
Pokud to není v požadavcích (dokumentaci), že by heslo bylo blíže specifikováno, jak má vypadat a co vše má obsahovat, je to jen návrh na  zlepšení a otázka na PO. 
Běžný standard je, že heslo má obsahovat číslo,velké písmeno a případně speciální znak.  
Systém nevyžaduje číslici v hesle. Není jasné, zda se jedná o záměr, nebo chybějící požadavek. Doporučeno doplnit specifikaci nebo zvážit zpřísnění validačních pravidel.
