# Fundamentele Git

Git este un sistem de control al versiunilor care vă permite să urmăriți modificările și să colaborați eficient la proiecte. Iată comenzile esențiale Git pentru a începe:

## 1. Inițializați un depozit Git

Pentru a începe utilizarea Git într-un proiect, navigați în directorul rădăcină al proiectului în terminalul dvs. sau în promptul de comandă și executați următoarea comandă:

`git init`

Aceasta creează un nou depozit Git în folderul proiectului.

## 2. Adăugați și comiteți modificările

Pentru a urmări modificările din proiectul dvs., trebuie să adăugați fișiere în zona de staging și apoi să le comiteți. Utilizați următoarele comenzi:

`git add <file> # Adaugă un fișier specific în zona de staging`

`git add . # Adaugă toate modificările din directorul curent în zona de staging`

`git commit -m "Mesajul commit-ului dumneavoastră"`

Mesajul commit-ului ar trebui să descrie succint modificările pe care le-ați făcut.

## 3. Verificați starea depozitului

Pentru a vedea starea curentă a depozitului dvs., utilizați următoarea comandă:

`git status`

Aceasta arată ce fișiere au fost modificate, adăugate în zona de staging sau comise.

## 4. Vizualizați istoricul commit-urilor

Pentru a vizualiza istoricul commit-urilor și a vedea o listă cu commit-urile anterioare, rulați:

`git log`

Aceasta afișează o listă cronologică a commit-urilor, cu identificatoarele lor de commit, datele și mesajele de commit.

## 5. Creați și schimbați ramuri (branch-uri)

Ramurile (branch-urile) vă permit să lucrați la noi caracteristici sau reparații fără a afecta codul principal. Pentru a crea o ramură nouă și a trece la ea, utilizați:

`git checkout -b <nume-ramură>`

Înlocuiți `<nume-ramură>` cu numele noii ramuri.

## 6. Unificarea (merge) ramurilor

După ce ați terminat lucrul la o caracteristică sau reparație într-o ramură, o puteți unifica înapoi în ramura principală (de obicei numită `master` sau `main`). Mai întâi, treceți la ramura principală:

`git checkout <nume-ramură-principală>`

Apoi, unificați ramura dvs. de caracteristică în ramura principală:

`git merge <nume-ramură>`

Acest lucru combină modificările din ramura specificată în ramura principală.

## 7. Încărcați în depozitul de pe serverul remote

Pentru a partaja modificările cu alții sau pentru a vă face backup la cod, puteți încărca depozitul local pe un depozit remote (cum ar fi GitHub sau GitLab). Mai întâi, adăugați URL-ul depozitului remote:

`git remote add origin <url-remote>`

Apoi, încărcați modificările:

`git push -u origin <nume-ramură>`

Înlocuiți `<url-remote>` cu URL-ul depozitului remote și `<nume-ramură>` cu numele ramurii pe care doriți să o încărcați.

Acestea sunt comenzile fundamentale Git pentru a începe. Git oferă multe alte funcționalități pentru colaborare și gestionare a codului, dar cu aceste noțiuni de bază, puteți urmări eficient modificările, puteți crea ramuri și puteți colabora la proiectele dvs.