# Räkna med Robbi (Zain matte)

Mattespel för åk 1–4, byggt med TypeScript + Vite. Fungerar i webbläsaren på iPad, iPhone och dator.

## Kör
```
npm install
npm run dev      # utvecklingsserver, öppna länken (även från iPad på samma wifi)
npm run build    # bygger dist/index.html – en enda fil som kan öppnas direkt eller läggas upp på en webbserver
```

## Kod (src/)
- `main.ts` – start, profil, startsida, vuxensidan, navigering
- `round.ts` – omgångar, poäng, stjärnor, feedback
- `mul.ts`, `clock.ts`, `table.ts`, `column.ts` – övningstyperna
- `timer.ts` – 30 min matte låser upp 20 min spel
- `shop.ts`, `catalog.ts`, `room.ts` – butik och eget rum (dra och släpp)
- `game.ts` – belöningsspelet Stjärnfångaren
- `core.ts` – lagring, ljud, Robbi, hjälpfunktioner

Allt sparas i webbläsaren (localStorage).
