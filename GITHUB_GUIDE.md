# Guida all'Esportazione su GitHub

Ecco come caricare il tuo progetto su GitHub.

## Prerequisiti
1.  Un account su [GitHub](https://github.com/).
2.  **Git** installato sul tuo computer (se hai VS Code, probabilmente c'è già).

## Procedura Passo-Passo

### 1. Crea un Nuovo Repository su GitHub
1.  Vai su [github.com/new](https://github.com/new).
2.  Nome Repository: `safety-coordinator` (o quello che preferisci).
3.  Visibilità: **Public** (o Private se preferisci).
4.  **Non** inizializzare con README, .gitignore o licenza (li aggiungeremo noi).
5.  Clicca su **Create repository**.

### 2. Inizializza Git nel Tuo Progetto
Apri il terminale in VS Code (Ctrl+ò) e scrivi questi comandi uno alla volta:

```bash
# Inizializza git
git init

# Aggiungi tutti i file
git add .

# Crea il primo "commit" (salvataggio)
git commit -m "Primo commit: Sito completo con sicurezza e privacy"

# Rinomina il ramo principale in 'main'
git branch -M main

# Collega il tuo progetto a GitHub (SOSTITUISCI CON IL TUO LINK!)
# Il link lo trovi nella pagina che hai appena creato su GitHub
git remote add origin https://github.com/TUO_USERNAME/safety-coordinator.git

# Carica tutto online
git push -u origin main
```

### 3. Verifica
Ricarica la pagina di GitHub. Dovresti vedere tutti i tuoi file!

## Note Utili
- **Aggiornamenti futuri:** Se modifichi qualcosa, ti basterà fare:
  ```bash
  git add .
  git commit -m "Descrizione modifica"
  git push
  ```
