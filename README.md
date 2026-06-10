# 📅 Piattaforma di Prenotazione Appuntamenti Universale (Template SaaS)

Un sistema di prenotazione appuntamenti scalabile, pronto per la produzione e multipiattaforma (Web, iOS, Android). Questo progetto è architettato come una **soluzione multi-tenant**, rendendolo istantaneamente adattabile a qualsiasi attività basata su servizi (barbieri, centri estetici, studi medici, centri sportivi) senza dover modificare la logica di business centrale.

Questa repository nasce come portfolio professionale per mostrare l'applicazione di una **Clean Architecture**, di un database progettato per prevenire le race condition e delle moderne pratiche di ingegneria del software full-stack.

---

## 🚀 Stack Tecnologico

- **Frontend & Mobile:** [Flutter](https://flutter.dev) (Unica codebase in Dart che compila in un'interfaccia Web responsive e app native per iOS e Android).
- **Gestione dello Stato:** Riverpod / Flutter BLoC (con flusso di dati unidirezionale rigoroso).
- **Backend & Database:** [Supabase](https://supabase.com) (PostgreSQL) con utilizzo delle Row Level Security (RLS) per l'isolamento sicuro dei dati dei vari tenant (attività).
- **Pagamenti:** Integrazione con Stripe (Infrastruttura per la gestione di caparre e pagamenti ai professionisti).
- **DevOps & Sviluppo Locale:** Docker + Supabase CLI per la gestione automatizzata delle migrazioni del database.
