# Kravmatrise – mal

Én rad per krav. Kolonner:

| Kolonne | Innhold |
|---|---|
| ID | Løpenummer, f.eks. K-01, M-01, T-01 (prefiks = type) |
| Type | K, M, T, D, F eller O (se SKILL.md) |
| Kravtekst | Ordrett sitat fra grunnlaget |
| Kilde | Dokument, side, punkt |
| Absolutt | Ja / Nei / Uklart |
| Dokumentasjon som kreves | Hva tilbyderen må legge ved |
| Svar i tilbudet | Fylles ut senere: hvor i tilbudet kravet besvares |
| Status | Ikke startet / Under arbeid / Besvart / Kontrollert |
| Ansvarlig | Fylles ut av brukeren |
| Merknad | Uklarheter, risiko, kobling til tildelingskriterium |

## Eksempel

| ID | Type | Kravtekst | Kilde | Absolutt | Dokumentasjon som kreves | Svar i tilbudet | Status | Ansvarlig | Merknad |
|---|---|---|---|---|---|---|---|---|---|
| K-01 | K | «Leverandøren skal ha en årlig omsetning på minimum 5 MNOK de to siste regnskapsårene.» | Konkurransegrunnlag s. 7, pkt. 4.3 | Ja | Årsregnskap 2024 og 2025 | | Ikke startet | | Sjekk at 2025-regnskap er godkjent før frist |
| M-01 | M | «Responstid ved kritisk feil skal være maksimalt 2 timer.» | Bilag 1 s. 4, pkt. 2.1.3 | Ja | Bekreftelse i løsningsbeskrivelse | | Ikke startet | | Avvik = vesentlig avvik |
| F-01 | F | «Tilbudet skal leveres elektronisk via Mercell.» | Konkurransegrunnlag s. 3, pkt. 1.6 | Ja | – | | Ikke startet | | |

## Regneark

Ved .xlsx: frys første rad, autofilter på alle kolonner, rullegardin på Type, Absolutt og Status, og et eget ark «Tildelingskriterier» og «Frister».
