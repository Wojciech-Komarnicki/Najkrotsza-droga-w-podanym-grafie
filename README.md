# 📉 Dijkstra – Najkrótsza Droga (Zadanie 3)

No dobra, to jest wrzucony kod do algorytmu **Dijkstry**. Zadanie polegało na znalezieniu najkrótszej ścieżki z wierzchołka **1** do **8** w tym popapranym grafie z ćwiczeń.

---

## 🚀 Co to robi?

W skrócie: program bierze ten nasz graf i wypluwa najkrótszą drogę. Standardowo, używa do tego modułów Pythona, żeby nie pisać wszystkiego od zera.

### Kluczowe Elementy

* **`graf`**: Definicja grafu w Pythonie. Zrobione na słowniku, bo tak najwygodniej, z wagami krawędzi (te małe numerki przy liniach).
* **`znajdz_najkrotsza_sciezke`**: Główne mięso, czyli sama funkcja Dijkstry. Używa **`PriorityQueue`** (tej kolejki priorytetowej), żeby nie marnować czasu na sprawdzanie gorszych ścieżek.
* **`poprzednik`**: Magiczny słownik, który pozwala mi odtworzyć ścieżkę z powrotem. Bez niego by się nie dało pokazać trasy, tylko sam dystans.

---

## 🛠️ Jak to uruchomić?

W zasadzie wystarczy mieć Pythona 3.x i odpalić skrypt. Żadne dziwne biblioteki nie są potrzebne.

```bash
python nazwa_pliku_z_kodem.py
