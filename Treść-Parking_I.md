# Parking (I)
Parking składa się z 16 stanowisk postojowych. Czujniki monitorują zajętość miejsc i przesyłają do systemu informatycznego informację złożoną z 16-znakowego słowa złożonego z wielkich liter W - miejsce wolne lub Z - miejsce zajęte (bez odstępów). Taka informacja zajmuje 16 bajtów. Napisz program, który dokona jej kompresji do 2 bajtów, to znaczy zapisze ją w postaci 16-bitowej liczby całkowitej w kodzie U2 przy założeniu, że 1 oznacza miejsce zajęte, a 0 miejsce wolne.
## Wejście
Słowo złożone z 16 znaków (wielkich liter Z lub W).
## Wyjście
Liczba w systemie dziesiętnym oznaczająca informację na temat zajętości miejsc
## Przykład
### Wejście:
```
ZWZZWZWWWWZWZWWZ
```
### Wyjście:
```
-19415
```
Wyjaśnienie do przykładu: Zajęte i wolne stanowiska zapisane w postaci ciągu bitów 1011010000101001 odpowiadają liczbie -19415 zakodowanej w kodzie U2 na 16 bitach.
