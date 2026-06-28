# Testy ręczne - ExamTaskConsole02

## Cel testów

Celem testów jest sprawdzenie, czy program poprawnie analizuje liczby całkowite zapisane w tablicy.

Program powinien poprawnie wyświetlić:

- wprowadzone liczby,
- sumę,
- średnią,
- minimum,
- maksimum,
- liczbę wartości parzystych,
- liczbę wartości nieparzystych.

---

## Test 1 - liczby dodatnie

### Dane wejściowe

```text
5
1
2
3
4
5
```

### Oczekiwany wynik

```text
Wprowadzone liczby: 1 2 3 4 5
Suma: 15
Średnia: 3,00
Minimum: 1
Maksimum: 5
Liczby parzyste: 2
Liczby nieparzyste: 3
```

---

## Test 2 - liczby dodatnie, ujemne i zero

### Dane wejściowe

```text
4
10
-2
7
0
```

### Oczekiwany wynik

```text
Wprowadzone liczby: 10 -2 7 0
Suma: 15
Średnia: 3,75
Minimum: -2
Maksimum: 10
Liczby parzyste: 3
Liczby nieparzyste: 1
```

---

## Test 3 - jeden element

### Dane wejściowe

```text
1
8
```

### Oczekiwany wynik

```text
Wprowadzone liczby: 8
Suma: 8
Średnia: 8,00
Minimum: 8
Maksimum: 8
Liczby parzyste: 1
Liczby nieparzyste: 0
```

---

## Test 4 - same liczby ujemne

### Dane wejściowe

```text
3
-5
-10
-2
```

### Oczekiwany wynik

```text
Wprowadzone liczby: -5 -10 -2
Suma: -17
Średnia: -5,67
Minimum: -10
Maksimum: -2
Liczby parzyste: 2
Liczby nieparzyste: 1
```

---

## Test 5 - same liczby parzyste

### Dane wejściowe

```text
4
2
4
6
8
```

### Oczekiwany wynik

```text
Wprowadzone liczby: 2 4 6 8
Suma: 20
Średnia: 5,00
Minimum: 2
Maksimum: 8
Liczby parzyste: 4
Liczby nieparzyste: 0
```

---

## Test 6 - same liczby nieparzyste

### Dane wejściowe

```text
4
1
3
5
7
```

### Oczekiwany wynik

```text
Wprowadzone liczby: 1 3 5 7
Suma: 16
Średnia: 4,00
Minimum: 1
Maksimum: 7
Liczby parzyste: 0
Liczby nieparzyste: 4
```

---

## Zasada zaliczenia testów

Program uznajemy za poprawny, jeżeli dla każdego testu:

1. przyjmuje dane wejściowe,
2. wykonuje obliczenia,
3. wyświetla wynik zgodny z oczekiwanym,
4. nie kończy działania błędem.

---

## Uwagi

Na tym etapie wszystkie testy wykonujemy ręcznie.

Uczeń uruchamia program, wpisuje dane wejściowe i porównuje wynik programu z wynikiem oczekiwanym.

Testowanie automatyczne będzie omówione w późniejszych projektach.