# Algorytm Dijkstry: Najkrótsza Ścieżka w Grafie 🧭

Ten projekt zawiera implementację **Algorytmu Dijkstry** (Dijkstra's Algorithm) w języku Python, służącą do znajdowania najkrótszej ścieżki w ważonym grafie nieskierowanym.

---

## 🎯 Cel Projektu

Celem jest rozwiązanie zadania z teorii grafów, polegającego na znalezieniu minimalnego kosztu ścieżki oraz jej rekonstrukcji, pomiędzy dwoma określonymi wierzchołkami w zadanym grafie.

---

## 🛠️ Użyte Technologie i Moduły

* **Język:** Python 3.x
* **Moduły:**
    * `collections` (do `defaultdict` i `deque`)
    * `queue` (do **`PriorityQueue`** – kolejki priorytetowej)

---

## ⚙️ Struktura Danych i Działanie

1.  **Graf:** Zdefiniowany jako słownik sąsiedztwa (lista sąsiedztwa), gdzie klucze to wierzchołki, a wartości to listy par `(sąsiad, waga_krawędzi)`.
2.  **Algorytm:** Wykorzystuje **Kolejkę Priorytetową** do efektywnego wybierania wierzchołka o najmniejszym dotychczasowym dystansie, zgodnie z logiką algorytmu Dijkstry.
3.  **Rekonstrukcja Ścieżki:** Używa słownika `poprzednik` do odtworzenia pełnej, najkrótszej ścieżki od końca do początku.

---

## 📊 Wynik dla Zadanego Grafu (1 do 8)

Program oblicza najkrótszą ścieżkę z wierzchołka **1** do **8** dla grafu podanego w zadaniu.

| Parametr | Wartość |
| :--- | :--- |
| Wierzchołek Startowy | 1 |
| Wierzchołek Końcowy | 8 |
| **Minimalna Długość** | **9.0** |
| **Najkrótsza Ścieżka** | `[1, 3, 4, 6, 5, 8]` |
