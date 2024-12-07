# GitHub-przypominajka

Łączenie się z repozytorium GitHub (2 spodoby):

### 1. Skopiowanie repozytorium na dysk lokalnym

__Inicjacja__

- Tworzenie repozytorium na dysku lokalnym 
```
git clone <link do repozytorium>
```

- Przejście do folder repozytorium 

```
cd nazwa_Foldera
```
__Edytowania i zapisywanie zmian__

- Dodawanie zmian
```
git add .
```

- Dodawanie wiadomości
```
git commit -m "wiadomości / opis zmian"
```

- Przesyłanie zmian do repozytorium na GitHub
```
git push
```

### 2. Inicjowanie repozytorium z poziomu terminala (Visual Studio Code)

- Znajdując się w folderze projektu
```
git init
```

- Dodawanie zmian 

```
git add .
```

- Dodawanie wiadomości commit 
```
git commit -m "Wiadomość"
```

- Tworzymy połączenie lokalnego repozytorium z GitHub
```
git remote add origin <link do repozytorium>
```

- Przełączamy się na głowny branch (gałąź)
```
git branch -m main
```
- Zatwierdzamy zmiany wysyłając do GitHub
```
git push origin main
```
- I po tym jak zrobisz jakie kolwiek zmiany wystarczy:
```
git add .
git commit -m "Opis zmian"
git push
```
