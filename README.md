# Matapan · Πάγια

Εφαρμογή καταγραφής παγίων και εξοπλισμού του εστιατορίου Matapan.

- **Front end:** `index.html` (GitHub Pages)
- **Βάση, λογαριασμοί, φωτογραφίες:** Supabase project `matapan-assets`
- **AI (ανάγνωση ταμπέλας, αναζήτηση στοιχείων):** Supabase Edge Function `assets-ai` → DeepSeek (`deepseek-flash`) + Tavily

Τα κλειδιά API μένουν μόνο στα Secrets του Supabase. Το αρχείο περιέχει μόνο το δημόσιο (publishable) κλειδί του Supabase· τα δεδομένα προστατεύονται με σύνδεση χρήστη και Row Level Security.
