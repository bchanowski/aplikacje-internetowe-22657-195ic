# Aplikacje internetowe 22657 195IC

<p><a href="#Lab1">Lab 1</a></p>
<p><a href="#Lab2">Lab 2</a></p>
<p><a href="#Lab3">Lab 3</a></p>
[Lab4](https://github.com/bchanowski/aplikacje-internetowe-22657-195IC/tree/main/lab4/myapi)  

<a id="Lab1"></a>
### Laboratorium nr. 1 - Blog uruchomiony na PaaS  
Blog stworzony z pomocą serwisu [heroku.com](https://www.heroku.com) oraz poradnika [djangogirls](https://tutorial.djangogirls.org/pl/)  
Przejdź do mojego blogu - [tutaj](https://blog-22657.herokuapp.com/)  
Stworzony blog pozwala zwykłemu uzytkownikowi zobaczyć dodane na stronie posty, osoby z funkcją admina mogą poza tym dodawać, edytować oraz usuwać posty  
  
#### Layout strony
Na samej górze widnieje tytuł strony, a pod nim można zobaczyć dodane posty, w prawym górnym rogu znajduję się plus, który przeniesie nas do dodawania postu.

![Layout strony](/assets/layout-strony.png "Layout strony")
  
#### Dodawanie postu  
Po kliknięciu plusa w prawym górnym rogu, pokażę się nam ekran dodawania postów, musimy tutaj wpisać tytuł oraz opis postu, aby móc go dodać

![Dodawanie postu](/assets/dodaj-post.png "Dodawania postu")

#### Detale postu

Po dodaniu się postu od razu zostaniemy przeniesieni do jego detali, tutaj możemy zuważyć dwa nowe przyciski - edycji (ołówek) i usunięcia (śmietnik), aby wrócić na stronę główną i zobaczyć wszytkie posty klikamy w główny nagłówek.

![Post detail](/assets/post-detail.png "Post detail")

![Lista postów](/assets/post-list.png "Lista postów")

Jak widać nasz post dodał się do naszej listy postów, wróćmy teraz do detali naszego nowego postu i kliknijmy przycisk edycji.

#### Edycja postów

Po kliknięciu przycisku edycji pojawi nam się tak sam ekran jak przy dodawaniu postu, tylko tym razem będzie już wypełniony, będzie jednak działał tak samo. Po kliknięciu save nasz post się edytuje.

![Edycja postu](/assets/post-edycja.png "Edycja postu")

![Post edytowany](/assets/post-edytowany.png "Post edytowany")


#### Usunięcie postu

Kliknijmy teraz przycisk usuwania, pojwi nam się pusty ekran strony, a po powrocie na stronę główną usunięty post nie będzie się pojawiał na naszej liście.

![Post usunięty](/assets/post-del.png "Post usunięty")

![Layout strony](/assets/layout-strony.png "Layout strony")  

<a id="Lab2"></a>
### Laboratorium nr. 2 - Rejestracja użytkowników  

W lab2 dodałem opcję rejestracji użytkownika, zmiany oraz resetu hasła i logowania.  Zmieniłem również system PaaS na heroku z powodu problemów z pythonanywhere przy próbach wysyłania maili z potwierdzeniem konta/resetem hasła.

![Strona główna](/assets/str-glw-no-user.png "Strona głowna")

Najpierw zatem zarejestrujmy użytkownika. Po rejestracji otrzymamy na maila wiadomość z linkiem do aktywacji konta.

![Rejestracja](/assets/signup.png "Rejestracja")

![Rejestracja](/assets/signup-done.png "Rejestracja")

![Rejestracja](/assets/signup-activate.png "Rejestracja")

![Rejestracja](/assets/signup-activate-done.png "Rejestracja")  

Po aktywacji konta jesteśmy od razu zalogowani, wyloguję się jednak żeby pokazać działanie logowania.

![Logowanie](/assets/login.png "Logowanie")

![Logowanie](/assets/login-done.png "Logowanie")  

Jak widać zniknęły nam opcje rejestracja, login oraz reset hasła, pojawiło się za to opcja zmiany hasła.  

![Zmiana hasła](/assets/chng-pass.png "Zmiana hasła")  

![Zmiana hasła](/assets/chng-pass-done.png "Zmiana hasła")  

Spróbujmy teraz zresetować hasło, znów musimy się wylogować.

![Reset hasła](/assets/reset-pass.png "Reset hasła")

![Reset hasła](/assets/reset-pass-done.png "Reset hasła")  

Po resecie hasła również otrzymamy maila z linkiem do resetu.

![Reset hasła](/assets/reset-pass-mail.png "Reset hasła")

![Reset hasła](/assets/reset-pass-mail-done.png "Reset hasła")  

Nowy użytkownik może tylko wyświetlać posty, nie dodawać czy edytować.  

<a id="Lab3"></a>
### Laboratorium nr. 3 - Różne sposoby uwierzytelniania  

W lab3 dodałem opcję uwierzytelniania za pomocą gmaila oraz discorda. Zdecydowałem się na tę dwie opcję gdyż gmail jest podstawową formę logowania na prawie każdej stronie, a z discorda korzystam w ramach naszych zajęć.  

![Logowanie](/assets/login-auth.png "Logowanie")  

## Gmail  

![Logowanie gmail](/assets/login-gmail.png "Logowanie gmail")  

![Logowanie gmail](/assets/login-gmail-done.png "Logowanie gmail")  

## Discord  

![Logowanie discord](/assets/login-discord.png "Logowanie discord")  

![Logowanie discord](/assets/login-discord-done.png "Logowanie discord")  


