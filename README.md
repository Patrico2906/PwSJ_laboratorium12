# Programowanie w językach skryptowych, Python
Laboratorium 11
Zadanie 1. Przygotuj plik szablonu `.html` renderujący: stronę główną (index.html), stronę
`omnie.html`, oraz `informacje.html`. Szablon może wykorzystywać Bootstrap’a. Możesz skorzystać z
szablonu udostępnionego w temacie 10. Napisz aplikację Flask, która zawiera trzy podstrony: stronę
`główną`, stronę `informacje` oraz stronę `o mnie`.
Zadanie 2. Uzupełnij szablony w aplikacji z zadania 1 tak, aby z poziomu kodu aplikacji Flask można
było generować tytuł strony oraz treść strony. Zajrzyj do wykładu, tam zawarty jest podobny
przykład.
Zadanie 3. Stwórz jeden szablon o nazwie kontent.html. Szablon ma zawierać warunki, które będą
wyświetlały tytuł oraz treść główną strony tylko wtedy, gdy nie jest to strona główna. Przyjmij, że
jeżeli jest to strona główna, to ani tytuł ani treść nie są podawane (tak najprościej skonstruować
warunek). Znajdź podobny przykład w wykładzie.
Zadanie 4. Uzupełnij szablon `informacje.html` o możliwość drukowania informacji (podobnie jak w
blogu): autor – treść. W szablonie powinna zostać użyta pętla, która odczytuje informacje autor-treść
ze słownika utworzonego w odpowiedniej funkcji aplikacji Flask.
Zadanie 5. Wykorzystaj mechanizm dziedziczenia szablonów (omówiony w wykładzie) do utworzenia
szablonu bazowego `baza.html`, który definiuje pełną szatę graficzną strony, oprócz treści. Przyjmij,
że treści będą wstrzykiwane z poziomu innych szablonów, np. `informacje.html` może zawierać tylko
pętlę, natomiast całą oprawę graficzną może dziedziczyć po `baza.html` a przykładowo ` index.html`
ma zawierać tylko znacznik nagłówkowy oraz akapit (<h1> oraz <p>). Wykorzystaj szablon bazowy do
konstrukcji każdej podstrony.
