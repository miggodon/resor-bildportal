# Resor Bildportal

Public static image dashboard for the private `miggodon/resor` project.

Portal: https://miggodon.github.io/resor-bildportal/

## Uppdatera hub (sid-status, media, portfölj)

Kör i privat `resor`-repo (INTe export_public_portal.py):

```text
python bilder/export_portfolio_hub.py
```

## Skapa nya bilder

Upload PNG to `bilder/inbox/` in the private repo. GitHub Actions converts to JPG.
