# PONAVLJANJE – C# ulaz/izlaz i tipovi podataka 

------------------------------------------------------------------------------------

## LINK NA MATERIJALE

[LINK NA MATERIJALE ZA RJEŠAVANJE ZADATAKA](https://drive.google.com/drive/folders/1IQLyg9t88PuaVTo6S0clQQ7wCdfEaHVs)


---------------------------------------------------------------------------------------


✅ Svaki zadatak je u svom folderu (svaki folder je poseban .NET konzolni projekt).

✅ Tekst zadatka je napisan u komentarima u Program.cs.

## Kako pokrenuti zadatak
1) Otvori repozitorij u VS Code
2) Uđi u folder zadatka, npr.:
```charp
   cd OCJENA_A
```
4) Pokreni:
```charp
   dotnet run
```

## OSNOVNE NAREDBE

1) Provjeri gdje se nalaziš
```charp
   pwd
```
3) Prikaži sadržaj repozitorija
```charp
   ls
```
5) Uđi u folder zadatka (primjer)
```charp
   cd VJEZBA_Z1
```
7) Pokreni program
```charp
   dotnet run
```
9) Povratak u glavni folder
```charp
    cd ..
```
   
## 📤 Predaja zadatka (GitHub Classroom)
Dodaj promjene
```bash
git add .
```
Spremi promjene
```bash
git commit -m "Rješenje zadatka"
```
Pošalji na GitHub
```bash
git push
```

## ⚠️ Važne napomene

Svaki zadatak pokreće se iz svog foldera

Ako nisi u folderu s .csproj datotekom, dotnet run neće raditi

Ne briši .csproj datoteke

Rješavaj zadatke samostalno

----------------------------------------------------------------------------------
----------------------------------------------------------------------------------

## CHECKLISTA ZA UČENIKE – PREDAJA ZADATKA (GitHub Classroom)

### 1. Napisao sam rješenje
- Kod je napisan u Program.cs
- Rješenje je u točnom folderu zadatka (OCJENA_A, OCJENA_B, ...)
- Program se pokreće bez greške (dotnet run)

### 2. Provjerio sam promjene
U terminalu: git status
- Program.cs se prikazuje kao izmijenjen

### 3. Dodao sam datoteku u staging
U terminalu: git add Program.cs ili git add .
- Datoteka je dodana u staging

### 4. Napravio sam commit
U terminalu: git commit -m "Rješenje zadatka"
- Commit je uspješno napravljen
- Poruka commita ima smisla

### 5. Poslao sam rad na GitHub
U terminalu: git push
- Push je uspješno završen
- Nema error poruka

### 6. Završna provjera
- Otvorio sam svoj repozitorij na GitHubu
- Vidim svoje promjene u Program.cs
- Vidim novi commit

**VAŽNO: Ako NE napraviš git push, nastavnik NE vidi tvoj rad.**
