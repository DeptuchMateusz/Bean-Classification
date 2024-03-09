### Feadback od walidatorów:
1. Brak opisu projektu w pliku README.md
2. Brak wniosków o tym z jakich rozkładów mogą być zmienne, na przykład, że rozkład roundness jest podobny do rozkładu normalnego
3. Słaba hierarchia plików w projekcie, w późniejszym etapie projektu może to prowadzić do problemów z zarządzaniem plikami oraz ich zrozumieniem czy merge'owaniem branchy itp
4. Trzeba mieć świadomość, że w waszym projekcie dużo zmiennych ma znaczenie i tych zmiennych nie jest dużo, przez co ja bym nie usuwał za bardzo zmiennych, dopiero na późniejszym etapie przy tworzeniu modelu przetestował, usunięcie których co zmienia.
5. Jeśli już mamy coś usuwać to korelacje typu 0.9 są BARDZO dużymi kandydatami do usunięcia.
6. Wypada napisać, że fasolki typu "BOMBAY" są bardzo inne od reszty fasolek, więc nie będzie z nimi problemu.
7. Wypada po każdym wykresie pisać wnioski, co wnosi dany wykres do analizy, co można z niego wyciągnąć, co jest ciekawe, co jest nieciekawe, co jest zaskakujące, co jest oczywiste itp. (ta, wiem, sam tak nie robię, ale ja jestem wyjątkowy)
8. Jeśli macie macierze korelacji i nie ma 84 kolumn to wypada wyświetlić macierz korelacji z dokładnymi wartościami napisanymi na niej, a nie tylko kolory.
9. Polecam skorzystać z modelu, o którym była mowa na wykładzie, który sprawdza, które zmienne są jego zdaniem ważne w kontekście usuwania zmiennych itp.