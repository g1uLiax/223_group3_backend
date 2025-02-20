# 223_group3_blogProject_backend

## Allgemein

#### Timeline:
19.02.25 - 26.02.25

#### Mitarbeiter:
Giulia, Naima, Andrin

#### Projekt Dokumentation: 

## Beschreibung:
Dieses Projekt wurde von Giulia, Naima und Andrin im Rahmen vom üK 223 Multiuser Fullstack Application ersrellt. Das Projekt ist eine Blog Seite mit der Individuellen Entity "Groups". <br>
Ausgangslage vom Projekt war ein Template welches mit Security, der Gruppenspezifischen Aufgabe, testing, multiuserfähigkeit, CRUD Operationen etc. erweitert wurde.
In diesem Repository befindet sich unser backend code mit der Datenbank für unsere Application. Siehe Set Up Teil für das Aufsetzen vom Projekt

## Set Up:
1. Clone Repository local  <br>
  Enter the following command in the terminal to clone the repo:
```
   git clone https://github.com/naica922/223_group3_blogProject_backend.git
```

2. Docker <br>
   Download docker desktop and run this command in your terminal:  <br>

```
docker run --name postgres_db -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres
```

3. Open the Project in IntelliJ Ultimate and use gradle to build and then bootRun the application. 

