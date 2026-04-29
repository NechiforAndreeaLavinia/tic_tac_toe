1. Descriere generală
Tic Tac Toe este un joc clasic pentru doi jucători (X și O) care se joacă pe o tablă 3×3. Scopul este ca un jucător să obțină trei simboluri consecutive pe o linie, coloană sau diagonală.

Acest proiect implementează jocul în Python, rulând în consolă.

2. Reguli de joc
Jocul se desfășoară pe o matrice 3×3.

Jucătorul X începe primul.

Jucătorii mută alternativ.

O mutare este validă doar dacă poziția este liberă.

Jocul se termină când:

Un jucător are trei simboluri consecutive (victorie)

Toate pozițiile sunt ocupate (egalitate)

3. Structura fișierului main.py
Programul conține următoarele componente:

✔ Reprezentarea tablei
O listă 3×3 sau o listă de 9 elemente.

Pozițiile goale sunt marcate cu " ".

✔ Funcții principale
display_board() – afișează tabla în consolă.

player_move(player) – citește și validează mutarea jucătorului.

check_win(player) – verifică dacă jucătorul a câștigat.

check_draw() – verifică dacă tabla este plină.

main() – bucla principală a jocului.

✔ Fluxul programului
Inițializează tabla.

Rulează un ciclu în care:

Afișează tabla.

Cere mutarea jucătorului curent.

Verifică victoria sau egalitatea.

Schimbă jucătorul.

Afișează rezultatul final.

4. Exemple de utilizare
Rulare în terminal:

Code
python main.py
Exemplu de afișare:

Code

 X | O |  
-----------
   | X |  
-----------
 O |   | X
 
5. Posibile îmbunătățiri
Implementarea unui AI (minimax).

Interfață grafică (Tkinter / Pygame).

Salvarea scorurilor.

Mod online multiplayer.
