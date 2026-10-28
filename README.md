# De Puntenkampioenen ⭐

Mobielvriendelijke React/Vite-app voor Thobin en Emilie. Positief puntensysteem met beloningen, ouderpincode, geschiedenis en lokale persistente opslag.

## Starten

```bash
npm install
npm run dev
```

## Publiceren

Deploy op Vercel of Netlify als Vite-project (`npm run build`, output `dist`).

## Opslag en veiligheid

De app bewaart gegevens in `localStorage` van één browser. Dit synchroniseert **niet** tussen telefoons of apparaten. De viercijferige pincode is een eenvoudige gebruiksbarrière, **geen veilige authenticatie**; de app is niet geschikt voor gevoelige gegevens. Voor gedeeld gebruik op meerdere telefoons is een backend met authenticatie en database nodig. Download een JSON-back-up vanuit Ouderbeheer.
