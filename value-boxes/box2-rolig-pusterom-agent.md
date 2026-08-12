# VALUE BOX 2 — Rolig-Pusterom Agent Layer
[VERDI-SCORE: 9.1 | TOKEN-KOST: Medium setup | ROI: Høy (direkte forlengelse av fototerapi) | COPY-PASTE READY]

## Formål
Eksisterende mini-app (rolig-pusterom-miniapp) får en agent-layer som gjør den til et levende verktøy mot isolasjon.

## Ny arkitektur (4 eksisterende sider + 1 agent-side)

### Side 5: Agent-Pusterom
- Shadow-check: Brukeren skriver 1-2 setninger om hvordan de har det → agent kjører cognitive-warfare på det indre narrativet og returnerer en rå, ærlig speiling + ett konkret 90-sekunders grep.
- Vibe-injection: Last opp eget bilde / historie → agent genererer personlig "break isolation"-prompt og bilde-prompt.
- Daglig protokoll: 90 sekunder – puste + ett spørsmål fra agenten + ett lite handlingssvar.

## Agent System Prompt (klar til OpenClaw / Base44)

```
Du er Pusterom-Agenten til Alexander Nordmann.
Du er ikke snill. Du er ærlig, rå, og på brukerens side.
Kjerne: Break isolation. Fototerapi-blod.

Når bruker skriver:
1. Speil det indre narrativet med cognitive-warfare (finn løgnen/skammen).
2. Gi ett konkret, 90-sekunders grep som kan gjøres NÅ.
3. Hvis bilde lastes opp: generer personlig vibe-prompt + caption.

Språk: Rått, kort, bergensk-tinget når det passer. Null terapyspråk. Null "det er greit å føle".
```

## Implementasjon
- Pure HTML/JS + localStorage (matcher eksisterende repo)
- Eller Base44 med agent-kall
- Legg til i eksisterende GitHub: fotoblinkskudd2-create/rolig-pusterom-miniapp

## REGNE
Lav teknisk terskel. Høy emosjonell switching-cost. Direkte forlengelse av ditt "why".
