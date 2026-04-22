# infinitas-website

Statisk webbplats för **Odd Fellow Logen 171 Infinitas** (www.infinitas.se).

## Hosting

- **DNS:** Cloudflare
- **Hosting:** Cloudflare Pages (GitHub-driven deploy)
- **SSL:** Cloudflare Universal SSL (Let's Encrypt, auto-förnyas var 60:e dag)
- **Tidigare hosting:** Telia webbhotell (avvecklas 2026-06-01)

## Innehåll

Minimal Bootstrap 4-landningssida med länkar till:

- Logens sida på oddfellow.se
- Internt SharePoint-intranät

## Lokal utveckling

Ingen build-process behövs. Öppna `index.html` direkt i webbläsaren eller kör en enkel HTTP-server:

```bash
python3 -m http.server 8000
```

## Deploy

Pushes till `main`-branchen deployeras automatiskt till Cloudflare Pages inom ~1 minut.

## Historik

Webbplatsen migrerades från Telia webbhotell till Cloudflare Pages i april 2026.
Se `SECURITY-INCIDENT-2026-04-23.md` (i Drätselnämndens arkiv) för
detaljer kring incident som upptäcktes och åtgärdades under migrationen.

## Licens

MIT License – se [LICENSE](LICENSE).
