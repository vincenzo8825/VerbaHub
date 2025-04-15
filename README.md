# 📰 VerbaHub – 

**Verbahub** è una piattaforma web progettata per la gestione e la pubblicazione di articoli giornalistici, completa di un sistema di ruoli e flussi di approvazione.

---

## 🎨 Analisi dei Colori

### 🔵 #214252 – Blu Scuro
Trasmette professionalità, affidabilità e serietà. Favorisce la fiducia dei lettori e una lettura rilassata anche di fronte a notizie complesse.

### ⚪ #848d92 – Grigio Medio
Colore neutro che garantisce equilibrio e sobrietà. Ottimo per sfondi, testi secondari ed elementi di interfaccia, migliorando la leggibilità.

### 🟣 #4d4c7d – Viola Scuro
Aggiunge un tocco di autorità, raffinatezza e originalità al design. Perfetto per dare carattere al sito senza compromettere la chiarezza.

---

## 🔄 Flusso di Lavoro

1. L’utente si registra sulla piattaforma  
2. Richiede un ruolo tramite la sezione **"Lavora con noi"**  
3. L’amministratore riceve la richiesta e può approvarla o rifiutarla  
4. Se approvato come **Scrittore**, l’utente può creare articoli  
5. I **Revisori** esaminano gli articoli e decidono se pubblicarli  
6. Gli articoli approvati vengono mostrati nella homepage e nelle sezioni appropriate  

---

## ✅ Funzionalità Implementate

### 🛡 Sistema di Ruoli

- **Utente Base**: può registrarsi, accedere e leggere gli articoli pubblicati  
- **Scrittore (Writer)**: può creare nuovi articoli da inviare in revisione  
- **Revisore (Revisor)**: può accettare, rifiutare o rimettere in revisione gli articoli  
- **Amministratore (Admin)**: gestisce le richieste di ruolo e assegna ruoli agli utenti  

### 📝 Gestione Articoli

- Creazione articoli con: titolo, sottotitolo, corpo, immagine e categoria  
- Revisione obbligatoria prima della pubblicazione  
- Visualizzazione per categoria o autore  
- Dashboard personalizzate per ogni ruolo  

### 📩 Sistema di Richieste di Ruolo

- Gli utenti possono candidarsi per diventare Writer, Revisor o Admin  
- Le richieste vengono notificate via email all'amministratore  
- L'amministratore può gestirle direttamente dalla dashboard  

### 🧭 Dashboard Utente

- **Writer**: visualizza i propri articoli e lo stato di revisione  
- **Revisor**: gestisce e modera gli articoli da pubblicare  
- **Admin**: gestisce le richieste di ruolo degli utenti  

---


---

## 📦 Tecnologie Utilizzate

- **Laravel** – Backend e gestione ruoli  
- **Laravel Breeze** – Autenticazione  
- **MySQL** – Database  
- **Bootstrap** – UI e responsive layout  
- **Blade** – Template engine  
- **Mailtrap** – Simulazione invio email

---

## 📁 Istruzioni per l’Installazione

```bash
git clone https://github.com/tuo-utente/the-aulab-post.git
cd the-aulab-post
composer install
npm install && npm run dev
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
