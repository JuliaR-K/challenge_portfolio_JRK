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
SELECT * FROM [Customers] ORDER BY City

## *Subtask 3*
1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

SELECT * FROM `actors` ORDER BY surname

![aktorzy](https://user-images.githubusercontent.com/122525944/218711481-ea0397db-96c1-49da-b233-78e43456a803.png)

2. Wyświetl film, który powstał w 2019 roku.

SELECT * FROM `movies` WHERE year_of_production = 2019

![film2019](https://user-images.githubusercontent.com/122525944/218865697-68454b0a-0096-45b2-bcf7-55bb8f9502cd.png)

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem. 

SELECT * FROM `movies` WHERE year_of_production BETWEEN 1900 and 1999

![between](https://user-images.githubusercontent.com/122525944/218866346-47702cd3-43f3-488e-b40a-ab2d667422e3.png)

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$  

SELECT title, price FROM `movies` WHERE price <7

![titleprice](https://user-images.githubusercontent.com/122525944/218867702-85168ecf-e5cc-4306-819c-e39e0db45e92.png)

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

SELECT * FROM `actors` WHERE actor_id >=4 AND actor_id <=7

![aktorzy](https://user-images.githubusercontent.com/122525944/218872457-3052758c-43c0-47c4-abb2-0cc77825149d.png)


6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

SELECT * FROM `customers` WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6

![customerid](https://user-images.githubusercontent.com/122525944/218871622-ff99d69a-ee41-47e5-be0c-599862a7fbc6.png)

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

SELECT * FROM `customers` WHERE customer_id IN(1,3,5)

![135](https://user-images.githubusercontent.com/122525944/218873306-4aca5983-6500-4cbe-89bd-c7be36a64b98.png)


8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

SELECT * FROM `actors`WHERE name LIKE 'An%'

![an](https://user-images.githubusercontent.com/122525944/218873986-fadca1b6-2649-4a70-a84c-a1feb884e818.png)


9. Wyświetl dane klienta, który nie ma podanego adresu email.

SELECT * FROM `customers` WHERE email IS null

![null](https://user-images.githubusercontent.com/122525944/218874296-154dc783-1f11-4b02-8889-5accedf53829.png)


10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

SELECT * FROM `movies` WHERE price > 9 AND movie_id BETWEEN 2 AND 8

![filmbetween](https://user-images.githubusercontent.com/122525944/218875082-e2535314-d2ce-4157-a217-6a718a8b7a76.png)

# **TASK 6**
## *Subtask 1*

11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈
UPDATE customers SET surname='Muler' WHERE name='Ania';

![miler](https://user-images.githubusercontent.com/122525944/220317246-56529db9-c4c1-4a03-90e3-3d0a53272486.png)

12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.

SELECT * FROM `sale` INNER JOIN customers ON sale.customer_id=customers.customer_id WHERE movie_id = 4

![join](https://user-images.githubusercontent.com/122525944/220463403-9daff4c3-709e-48f3-a29b-a2b1d558d840.png)

13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com

UPDATE customers SET email = 'pati@mail.com' WHERE email IS NULL

![email](https://user-images.githubusercontent.com/122525944/220473445-32f612c1-3b1a-4a40-a952-b10ba271652d.png)


14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).

SELECT name, surname, title FROM `sale` INNER JOIN customers ON sale.customer_id=customers.customer_id INNER JOIN movies ON sale.movie_id=movies.movie_id;

![movie](https://user-images.githubusercontent.com/122525944/220464693-31486fc3-c1bd-470d-940e-3e8a0bc174a0.png)

15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

ALTER TABLE `customers` ADD `pseudonym` VARCHAR(200) NOT NULL 
UPDATE customers SET pseudonym = concat (LEFT(name, 2), RIGHT(surname, 1))

![concat](https://user-images.githubusercontent.com/122525944/220468390-a06cb31a-366f-4b10-a771-3c92176efd29.png)


16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

SELECT DISTINCT title FROM `sale` INNER JOIN movies ON sale.movie_id=movies.movie_id

![distinct](https://user-images.githubusercontent.com/122525944/220468993-2aeea8fd-d254-432e-811a-5c2a69ef976b.png)

17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)

SELECT name FROM customers UNION SELECT name FROM actors ORDER BY name ASC

![asc](https://user-images.githubusercontent.com/122525944/220469920-bced4068-0870-494d-aeb2-e23691c3eaac.png)

18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5 $ (Pamiętaj, że dolar to domyślna jednostka- nie używaj jej nigdzie).

UPDATE movies SET price = price+2.5 WHERE year_of_production > 2000

![price2,5](https://user-images.githubusercontent.com/122525944/220470676-65bc1312-9f76-48db-b687-54a3d12f7025.png)


19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał

SELECT name, surname, title FROM cast INNER JOIN actors ON cast.actor_id=actors.actor_id INNER JOIN movies ON cast.movie_id=movies.movie_id WHERE actors.actor_id =4

![id4](https://user-images.githubusercontent.com/122525944/220471931-e98c76cc-d2ce-4a9c-88ec-939c2a2ae56a.png)

20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa

INSERT INTO customers (customer_id, email, name,pseudonym, surname) VALUES (7, 'honia@mail.com', 'Honia', 'Hoa', 'Stuczka-Kucharska')

![honia](https://user-images.githubusercontent.com/122525944/220472830-faed9532-e144-4e97-9e9c-e09ec8b2af06.png)



# challenge_portfolio_JRK
