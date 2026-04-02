**Název:**  
Odhlášení uživatele  
**Priorita:**  
Medium  
**Preconditions:**  
-Uživatel je registrován a provedl aktivaci účtu prostřednictvím potvrzovacího e-mailu  
-Má platné přihlašovací údaje  
-Webová stránka pro přihlášení https://www.knihydobrovsky.cz/  
-Uživatel je přihlášen  
**Test data:**  
Email: martinavyoralova725@gmail.com  
Heslo: *******  
**Poznámka:**  
Během testování byly použity reálné přihlašovací údaje z důvodu absence testovacího účtu.
Z bezpečnostních důvodů nejsou tyto údaje v dokumentaci uvedeny.
V reálném testovacím prostředí by byly použity testovací účty.


**Test Steps:**

| Step | Akce | Expected Result |
|------|------|----------------|
| 1    | Najed v hlavičce na pravé straně na uživatelské jméno, bez interakce. | Rozbalí se možnosti jako Moje knihovna, Objednávky… a Odhlášení. |
| 2    | Klikni na možnost Odhlášení z rozbalovacího obsahu. | Uživatel je odhlášen. V pravé části obrazovky se místo uživatelského účtu zobrazuje možnost „Přihlášení“. |


**Exekuce:**  
Passed
