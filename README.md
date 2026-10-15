# Mellem Linjerne — prototype

En responsiv Astro-prototype til et dansksproget litteraturmagasin. Indeholder forside, kategorifiltre, lokal søgning, artikelsider og en om-side.

## Kør lokalt

```bash
npm install
npm run dev
```

Åbn adressen, der vises i terminalen (typisk http://localhost:4321).

## Byg til udgivelse

```bash
npm run build
```

Den statiske side genereres i `dist/`. Projektet kan deployes til Vercel via et Git-repository med framework preset Astro.

## Rediger artikler

Indholdet ligger foreløbig i `src/data/articles.js`. De seks artikler er korte, **redaktionelle demotekster**, ikke færdige anmeldelser. Erstat dem inden lancering.

## Næste fase: Sanity

Sanity er valgt som planlagt CMS, men er **ikke tilsluttet endnu**. Opret først et Sanity-projekt, indholdsmodeller for artikler, forfattere og kategorier, og tilføj derefter en Astro-integration med sikre miljøvariabler. Intet domæne er registreret, og webstedet er ikke publiceret.

## Billeder

Prototypebilleder hentes fra Unsplash. Udskift dem med billeder, I har rettigheder til, før lancering. Billeder kræver netadgang.
