# Come utilizzare GitHub
Per prima cosa bisogna distinguere **git** da **github**

### Git
È il gestore di versione

### GitHub
È il server che ospita i nostri *git*

## Operazioni da eseguire
```
PS: Questa è la procedura più comoda
```
- Creare il *repository* da [**GitHub**]('https://github.com/' "Home page di GitHub")

- Clonare il *repository*
    ```
    git clone **link del _repo_ appena creato**
    ```

- **MODIFICARE IL _REPOSITORY_**

- Aggiungere i file aggiornati
    ```
    git add .
    ```
- Confermare l'aggiornamento
    ```
    git commit -m "TITOLO" -m "DESCRIZIONE"
    ```
- Caricare la modifica su *GitHub*
    ```
    git push
    ```

Una scorciatoia per __add__ and __commit__ è
```
git committ -am "TITOLO" -m "DESCRIZIONE"
```
*ATTENZIONE:* non aggiunge i file appena creati


È possibile verificare lo stato di modifica con
```
git status
```

---

## Installare **Git** si Windows
Seguire la guida su https://www.atlassian.com/git/tutorials/install-git#windows
