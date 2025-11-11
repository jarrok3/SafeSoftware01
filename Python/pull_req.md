## Zadanie 2.1
Weryfikowano występowanie podatności XSS w aplikajci symulującej bibliotekę. W tym celu użyto przykładowego kodu JavaScript w postaci
```
<script>alert('kapibarka')</script>
```
Dzięki zastosowaniu kodu możliwe było wykrycie podatności poprzez wklejanie do pól oczekujących wartości od użytkownika. 