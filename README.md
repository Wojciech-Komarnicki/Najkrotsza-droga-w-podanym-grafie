Algorytm Dijkstry: Najkrótsza Ścieżka w Grafie 🧭
Ten projekt zawiera implementację Algorytmu Dijkstry (Dijkstra's Algorithm) w języku Python, służącą do znajdowania najkrótszej ścieżki w ważonym grafie nieskierowanym.

Cel Projektu
Celem jest rozwiązanie zadania z teorii grafów, polegającego na znalezieniu minimalnego kosztu ścieżki oraz jej rekonstrukcji, pomiędzy dwoma określonymi wierzchołkami w zadanym grafie.

Użyte Technologie
Język: Python 3.x

Moduły:

collections (do defaultdict i deque)

queue (do PriorityQueue – kolejki priorytetowej)

Struktura Danych i Działanie
Graf: Zdefiniowany jako słownik sąsiedztwa, gdzie klucze to wierzchołki, a wartości to listy par (sąsiad, waga_krawędzi).

Algorytm: Wykorzystuje Kolejkę Priorytetową do efektywnego wybierania wierzchołka o najmniejszym dotychczasowym dystansie, zgodnie z logiką algorytmu Dijkstry.

Wynik: Program zwraca długość minimalnej ścieżki oraz listę wierzchołków składających się na tę ścieżkę.

Wynik dla zadania z pliku:
Program oblicza najkrótszą ścieżkę z wierzchołka 1 do 8.
