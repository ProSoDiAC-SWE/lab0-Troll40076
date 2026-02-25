# 👥 OOP Contributors

Benvenuto nel repository del corso di **Programmazione ad Oggetti** @ UniME!

Il tuo obiettivo è aggiungere il tuo file di profilo tramite una **Pull Request** sulla repo che ti è stata assegnata.

---

## 🎯 Obiettivo

Contribuire al repository usando il flusso di lavoro collaborativo:
**Clone → Branch → Commit → Push → Pull Request → Merge**

---

## 📋 Istruzioni

### 1. Accetta l'invito
Accetta l'invito ricevuto via email o link. Ti verrà assegnata una repository personale all'interno dell'organizzazione:

```
https://github.com/ProSoDiAC-SWE/lab0-<tuousername>
```

### 2. Clona la tua repository

**Con HTTPS:**
```bash
git clone https://github.com/ProSoDiAC-SWE/lab0-<tuousername>.git
cd lab0-<tuousername>
```

**Con SSH** (se hai già configurato una chiave SSH su GitHub):
```bash
git clone git@github.com:ProSoDiAC-SWE/lab0-<tuousername>.git
cd lab0-<tuousername>
```

### 3. Crea un branch
```bash
git checkout -b add-contributor-TUONOME
```

### 4. Crea il tuo file di profilo
- Vai nella cartella `contributors/`
- Copia il file `template.md` e rinominalo con il formato `nome-cognome.md`
- Compila le tue informazioni seguendo il template

### 5. Commit e push
```bash
git add contributors/nome-cognome.md
git commit -m "Add contributor: Nome Cognome"
git push origin add-contributor-TUONOME
```

### 6. Apri la Pull Request
- Vai sulla tua repository su GitHub
- Clicca su **"Compare & pull request"**
- Scrivi un titolo descrittivo: `Add student: Nome Cognome`
- Clicca **"Create pull request"**

### 7. Mergia il codice
- Controlla che non ci siano conflitti
- Clicca **"Merge pull request"** → **"Confirm merge"**

---

## 📁 Struttura del repository

```
lab0-<tuousername>/
├── README.md
└── contributors/
    ├── template.md        ← Copia questo file
    └── mario-rossi.md     ← Esempio già compilato
```

---

## ❓ Problemi?

Apri una [Issue](../../issues) descrivendo il problema che stai riscontrando.
