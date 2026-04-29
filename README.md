🎮 Tic Tac Toe – Python Console Game

Un proiect simplu și educativ care implementează jocul clasic Tic Tac Toe (X și O) în Python, rulând în terminal. Este ideal pentru începători care vor să învețe despre structuri de date, funcții, validarea inputului și logica de joc.



📌 Caracteristici

Joc pentru doi jucători (X și O)



Afișare clară a tablei în consolă



Validarea mutărilor



Detectarea automată a:



Victoriei



Egalității



Cod simplu, ușor de înțeles și modificat



🧩 Reguli de joc

Tabla este 3×3.



Jucătorul X începe primul.



Jucătorii mută alternativ.



O mutare este validă doar dacă poziția este liberă.



Jocul se termină când:



Un jucător are trei simboluri consecutive (linie, coloană, diagonală)



Sau toate pozițiile sunt ocupate (egalitate)



📂 Structura proiectului

Code

tic-tac-toe/

│

├── main.py        # Codul principal al jocului

└── README.md      # Documentația proiectului

▶️ Cum rulezi jocul

Asigură-te că ai Python instalat, apoi rulează:



Code

python main.py

🧠 Cum funcționează codul

Funcții principale

display\_board(board) – afișează tabla în format 3×3



player\_move(player, board) – citește și validează mutarea jucătorului



check\_win(player, board) – verifică dacă jucătorul a câștigat



check\_draw(board) – verifică dacă tabla este plină



main() – bucla principală a jocului



Reprezentarea tablei

Tabla este o listă cu 9 elemente:



python

board = \[" " for \_ in range(9)]

🖼 Exemplu de afișare

Code

&#x20;X | O |  

\-----------

&#x20;  | X |  

\-----------

&#x20;O |   | X

🚀 Îmbunătățiri posibile

Adăugarea unui AI (algoritm Minimax)



Interfață grafică (Tkinter / Pygame)



Mod multiplayer online



Evidențierea combinației câștigătoare



Sistem de scoruri



📜 Licență

Acest proiect este liber de utilizat și modificat în scop educațional.



