# **TASK 1**  
## *Subtask 1*  
8 pkt.  
## *Subtask 3*
Chciałam nauczyć się testowania, rozwinąć się w ciekawej i ciągle zmienijącej się branży. Moim celem jest ciągła nauka i stworzenie swojego pierwszego projektu.
## *Subtask 4*
Aplikacja zbiera dane o graczach futbolowych, umożliwia przegladanie ich danych o grze w piłkę.

Można zalogować się do systemu, dodać gracza, zmienić język aplikacji na angielski, wyszukać konkretnego gracza, wygenerować raport o meczu.
Interfejs jest przejrzysty, dodawanie raportów jest nieintuicyjne. Opcji gry na boisku jest niezrozumiała.

Zauważam błędy takie jak możliwość dodania daty z przyszłości, nierealnego wieku, imion i nazwisk, które nie istnieją. 

W wersji po polsku występują przyciski po angielsku np. submit, clear. 

# **TASK 2**
## *Subtask 1*
https://docs.google.com/spreadsheets/d/1xmuUivpb1CxYluTaV8hQ23VvhtQe_3pr/edit?usp=sharing&ouid=100748264363169360641&rtpof=true&sd=true
## *Subtask 2*
https://docs.google.com/spreadsheets/d/11N6KIfQtU_Y2j-Wq7jPyHXGv1Y-ZqHuz/edit?usp=sharing&ouid=100748264363169360641&rtpof=true&sd=true
## *Subtask 3*
Przypadki testowe piszemy, żeby uporządkować i zaplanować to, co chcemy przetestować. 
Przypadki testowe mogą być źródłem informacji o oprogramowaniu.  
## *Subtask 4*
https://docs.google.com/spreadsheets/d/1cr_ioh8iUvYWmNYQo77L6eGbzr386clr/edit?usp=sharing&ouid=100748264363169360641&rtpof=true&sd=true

# **TASK 3**
## *Subtask 2*
https://drive.google.com/file/d/1Z0HsTUWQV1RnylwBaahxZp68JU2UqGcF/view?usp=sharing
## *Subtask 3*
https://drive.google.com/file/d/1E9-NAJIQ7IBDhv-wwf8SkJRPWuPXFdcf/view?usp=sharing

# **TASK 4**
## *Subtask 2*
https://drive.google.com/file/d/18AJwvSqexeTWcPJyaWWqEmOxhTPxxgJ1/view?usp=share_link
## *Subtask 3*
Aplikacja olx służy do zamieszczania ogłoszeń sprzedaży rzeczy i usług, a także ogłoszeń o pracę oraz do kupowania rzeczy i usług.
Użytkownikiem końcowym aplikacji jest kupujący produkt lub sprzedający i umieszczający ogłoszenie.
Według mnie aplikacja jest przyjazna dla użytkownika, działa sprawnie, zamieszczanie ogłoszeń i kupowanie jest intuicyjne.
Można by dodać opcję wysyłania powiadomień o interesujących nas ogłoszeniach w określonej okolicy np. ogłoszeniach o pracę.

Testowanie aplikacji internetowej to testowanie strony internetowej uruchamianej z wykorzystaniej przeglądarki internetowej, a testowanie aplikacji natywnej to testowanie aplikacji moblinej stworzonej na dany system mobliny np. iOS, Android. 
Do testowanie aplikacji natywnej jest potrzebna duża ilość urządzeń lub emulatorów na których należy przetestować aplikację, a do testowania aplikacji internetowej potrzebne są różne przeglądarki. 
## *Subtask 4*
https://dare-it-2023-man-test.atlassian.net/jira/software/projects/CPP2/boards/1
# **TASK 5**
## *Subtask 1*
Zapytania/operatory, które przećwiczyłam:
SELECT * FROM 
SELECT FROM
SELECT Country FROM Customers WHERE Country = 'Poland'
SELECT * FROM [Products] WHERE SupplierID BETWEEN 2 AND 6
SELECT * FROM [Customers]
ORDER BY City
## *Subtask 3*
1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.
SELECT * FROM `actors` 
ORDER BY surname
![aktorzy](https://user-images.githubusercontent.com/122525944/218711481-ea0397db-96c1-49da-b233-78e43456a803.png)
2. Wyświetl film, który powstał w 2019 roku.
SELECT * FROM `movies` WHERE year_of_production = 2019
![film2019](https://user-images.githubusercontent.com/122525944/218865697-68454b0a-0096-45b2-bcf7-55bb8f9502cd.png)

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem. 
SELECT * FROM `movies` WHERE year_of_production BETWEEN 1900 and 1999
![between](https://user-images.githubusercontent.com/122525944/218866346-47702cd3-43f3-488e-b40a-ab2d667422e3.png)

5. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$
6. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
7. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.
8. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.
9. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
10. Wyświetl dane klienta, który nie ma podanego adresu email.
11. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

# challenge_portfolio_JRK
