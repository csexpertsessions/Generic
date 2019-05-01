# Generic

1. Lav en ny Console App (.NET Framework)
2. Udskriv en liste med alle værdier mellem 1 og 150
```c#
Console.WriteLine(værdi);
```
3. Hvis værdien er delbar med 3, så skal du skrive `Fizz` i stedet
4. Hvis værdien er delbar med 5, så skal du skrive `Buzz` i stedet
5. Hvis værdien er delbar med både 3 og 5 så skal du skrive både `Fizz` og `Buzz`
6. For hver værdi må du kun udskrive 1.linie
7. Lav liste

## Hvad hvis du skal teste for modulus for flere værdier?
7. Opret en generisk collection over værdier som skal testes for
8. Denne liste skal indeholde værdien som `int` og den tilhørende tekst som `string` (Key/Value pair...)
9. I collectionen skal der ud over 3 og 5 også være 7 med teksten `Jazz`
10. Refactor din kode til at gennemløbe alle tal fra 1 til 150 og for hver værdi testes mod collectionen
