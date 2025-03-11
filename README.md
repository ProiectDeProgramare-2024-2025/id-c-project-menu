# ID C Project / Menu - 10 Points
### EN
Based on your project description, create a .c app that implements a menu.
You can choose between implementing an interactive menu or a non-interactive one.

**Grading for interactive menu**
- (2p) Display the menu on the screen
- (2p) User can select options from the menu (via keyboard reading)
- (3p) When user enters a submenu, the previous one is cleared and the submenu has a header
- (3p) When user exits a submenu, the content gets cleared, the app doesn't end and the user is taken back to the previous menu

**Grading for non-interactive menu**
- Use the command line arguments for implementing the options:
  - (3p) existent options should output `Option <option-name> not implemented!`
  - (2p) non-existent options should output `Missing option! Too see all available commands, use help!`
- (3p) Display all the available commands when the app is ran without any arguments
- (2p) Implement the `help` option that also displays all the commands

! The non-interactive menu doesn't and will not support keyboard reading. Using `cin` or variations to read from keyboard is prohibited.

### RO
În funcție de descriere proiectului, creați o aplicație .c care va implementa meniul.
Puteți alege între implementarea unui meniu interactiv sau a unui meniu non-interactiv.

**Punctarea meniului interactiv**
- (2p) Afișarea opțiunilor meniului
- (2p) Utilizatorul poate selecta opțiuni din meniu (prin citirea de la tastatură)
- (3p) Când utilizatorul intră într-un submeniu, ce era pe ecran înainte se șterge. Submeniul are header astfel încât utilizatorul știe unde se află în momentul respectiv.
- (3p) Când utilizatorul iasă din submeniu, ce era pe ecran se șterge. Aplicația nu se oprește iar utilizatorul este adus înapoi la meniul anterior

**Punctarea meniului non-interactiv**
- Folosiți parametrii de pe linia de comanda pentru implementarea opțiunilor:
  - (3p) opțiunile existente afișează `Opțiunea <nume-opțiune> nu este implementată!`
  - (2p) opțiunile inexistente afișează `Opțiune lipsă! Pentru a vedea o listă cu toate comenzile accesibile folosiți opțiunea help!`
- (3p) Afișați toate comenzile / opțiunile accesibile când aplicația este rulată fără parametrii
- (2p) Implementați comanda `help` pentru a afișa toate opțiunile accesibile

! Meniul non-interactiv nu suportă și nu va suporta citirea de la tastatură. Folosirea `cin` sau a variațiilor pentru citirea de la tastatură este interzisă.
