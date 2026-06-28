# ExamTaskConsole02

## Analiza liczb całkowitych w tablicy

Autor: **Mariusz Smółka**

---

## Opis projektu

`ExamTaskConsole02` to projekt konsolowy w języku C# przygotowany do nauki podstaw programowania oraz pracy z repozytorium Git i GitHub.

Projekt rozwija wcześniejszy projekt bazowy i wprowadza pracę z tablicą jednowymiarową.

---

## Cel zadania

Celem programu jest wczytanie liczb całkowitych do tablicy, a następnie wykonanie podstawowych obliczeń na jej elementach.

Program powinien:

1. zapytać użytkownika, ile liczb chce wprowadzić,
2. utworzyć tablicę `int[]` o podanym rozmiarze,
3. wczytać liczby całkowite do tablicy,
4. wyświetlić wszystkie elementy tablicy,
5. obliczyć sumę elementów,
6. obliczyć średnią arytmetyczną,
7. znaleźć najmniejszą liczbę,
8. znaleźć największą liczbę,
9. policzyć liczby parzyste,
10. policzyć liczby nieparzyste.

---

## Zakres materiału

Projekt ćwiczy:

- `Console.WriteLine`,
- `Console.ReadLine`,
- `int.Parse` lub `int.TryParse`,
- zmienne typu `int`,
- zmienne typu `double`,
- instrukcję `if`,
- pętlę `for`,
- tablicę `int[]`,
- odwołanie do elementów tablicy przez indeks,
- właściwość `Length`,
- obliczanie sumy,
- obliczanie średniej,
- znajdowanie minimum i maksimum,
- sprawdzanie parzystości liczby.

---

## Przykładowa struktura projektu

    ExamTaskConsole02/
    │
    ├── ExamTaskConsole02.sln
    ├── README.md
    ├── .gitignore
    │
    └── ExamTaskConsole02/
        ├── ExamTaskConsole02.csproj
        └── Program.cs

---

## Uruchomienie projektu

Projekt można uruchomić w Visual Studio.

1. Otwórz plik `ExamTaskConsole02.sln`.
2. Upewnij się, że wybrany jest projekt `ExamTaskConsole02`.
3. Uruchom program skrótem `Ctrl + F5`.

---

## Przykładowe działanie programu

Dane wejściowe:

    Podaj liczbę elementów: 5
    Podaj liczbę 1: 1
    Podaj liczbę 2: 2
    Podaj liczbę 3: 3
    Podaj liczbę 4: 4
    Podaj liczbę 5: 5

Oczekiwany wynik:

    Wprowadzone liczby: 1 2 3 4 5
    Suma: 15
    Średnia: 3,00
    Minimum: 1
    Maksimum: 5
    Liczby parzyste: 2
    Liczby nieparzyste: 3

---

## Przykładowy kod startowy

    using System;

    namespace ExamTaskConsole02
    {
        internal class Program
        {
            static void Main(string[] args)
            {
                Console.WriteLine("ExamTaskConsole02 - analiza liczb całkowitych w tablicy - 2026/2027");
            }
        }
    }

---

## Etapy wykonania zadania

Zadanie można realizować etapami:

1. wyświetlenie komunikatu startowego,
2. wczytanie liczby elementów tablicy,
3. utworzenie tablicy `int[]`,
4. wczytanie liczb do tablicy,
5. wyświetlenie elementów tablicy,
6. obliczenie sumy,
7. obliczenie średniej,
8. znalezienie minimum i maksimum,
9. policzenie liczb parzystych i nieparzystych,
10. dodanie prostej walidacji danych.

---

## Przykładowe commity

Dobre komunikaty commitów:

- Initial console project
- Rename project to ExamTaskConsole02
- Update README for array task
- Add array size input
- Add numbers input to array
- Display array elements
- Calculate sum and average
- Find min and max
- Count even and odd numbers
- Add input validation

---

## Kryteria wykonania

Projekt jest wykonany poprawnie, jeżeli:

- program uruchamia się w Visual Studio,
- użytkownik może podać liczbę elementów,
- program tworzy tablicę o podanym rozmiarze,
- program wczytuje liczby do tablicy,
- program wyświetla elementy tablicy,
- program poprawnie oblicza sumę,
- program poprawnie oblicza średnią,
- program poprawnie znajduje minimum i maksimum,
- program poprawnie liczy liczby parzyste i nieparzyste,
- zmiany są zapisane w repozytorium Git,
- projekt został wypchnięty do GitHub.

---

## Minimalny słownik pojęć

tablica - struktura przechowująca wiele wartości tego samego typu  
indeks - numer pozycji elementu w tablicy  
element tablicy - pojedyncza wartość przechowywana w tablicy  
Length - liczba elementów tablicy  
commit - zapisany etap pracy w repozytorium Git  
push - wysłanie zmian do GitHub  
repository - repozytorium projektu  

---

## Uwagi

W tym projekcie używamy klasycznej tablicy:

    int[] liczby = new int[n];

Nie używamy jeszcze kolekcji:

    List<int>

Kolekcje dynamiczne zostaną omówione w późniejszych projektach.

Celem tego zadania jest utrwalenie podstaw pracy z tablicami, pętlą `for` i prostymi algorytmami.