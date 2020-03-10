# ZarzadzanieNotatkami
Aplikacja do zarzadzania notatkami

This application manages notes and segregates them by users who created them.
It uses ASP.NET Core MVC.

You have to run **update-database** im Package Manager Console to generate Database for this program to use.

If you want to create first note you have to create User first.

### How application works:

If you only want to update "importants" of notes you can click "Update importants"

You can sort notes by clicking sort ascending and sort descending.

Application uses cookies to preserve state of chosen user.

You can manage Users by clicking responsible for it button.

You can create notes and users. For both of them there are implemented CRUD operations.
