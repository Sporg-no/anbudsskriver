---
name: avvisningssjekk
description: Kontroller et ferdig eller nesten ferdig tilbud på et norsk offentlig anbud mot konkurransegrunnlaget før innlevering, og finn alt som kan føre til avvisning – manglende vedlegg, forbehold, avvik fra absolutte krav, signatur, format og frister. Bruk når brukeren sier «sjekk tilbudet», «kan dette bli avvist», «klar til innlevering» eller laster opp både grunnlag og tilbud.
---

# Avvisningssjekk før innlevering

Finn alt i tilbudet som kan gi avvisning eller poengtrekk, før det leveres. Oppgaven er å lete etter feil, ikke å bekrefte at tilbudet er bra.

## Input

- Konkurransegrunnlaget med alle vedlegg, rettelser og publiserte svar på spørsmål.
- Tilbudet slik det skal leveres: tilbudsbrev, besvarelser, prisskjema, ESPD/egenerklæringer, CV-er, referanser, attester.
- Kravmatrisen fra skillen `konkurransegrunnlag-analyse` hvis den finnes. Hvis ikke: lag kravlisten selv først (punkt 4–7 i den skillen).

Mangler grunnlaget eller tilbudet, stopp og be om det. Sjekken kan ikke gjøres på bare den ene delen.

## Fremgangsmåte

Gå gjennom sjekklisten i `references/sjekkliste.md` punkt for punkt. For hvert punkt:

1. Finn kravet i grunnlaget (med kilde).
2. Finn hvor tilbudet svarer på det (med kilde).
3. Vurder: **OK**, **Mangler**, **Avvik** eller **Uklart**.

Deretter:

4. **Let etter skjulte forbehold.** Les hele tilbudet etter formuleringer som kan tolkes som forbehold eller avvik:
   - «forutsetter», «under forutsetning av», «med forbehold om», «normalt», «ca.», «etter avtale», «så langt det er mulig», «inntil videre», «tilstreber», «vil søke å»
   - henvisning til egne leveringsbetingelser, standardvilkår, prislister eller vedlagte salgsbetingelser
   - andre tidsfrister, mengder, kapasiteter eller ansvarsgrenser enn i grunnlaget
   - alternative løsninger som ikke er tillatt
   Hver funn: siter setningen, vis kravet den kan stride mot, og foreslå ny ordlyd som ikke er et forbehold.
5. **Vurder vesentlighet** for hvert avvik etter `references/regelverk-2026.md`. Avvik fra krav merket «skal», minstekrav eller kjerneelementer i anskaffelsen = **høy risiko**.
6. **Sjekk konsistens** mellom dokumentene: samme priser, mengder, navn på nøkkelpersoner, organisasjonsnummer, datoer og versjonsnummer overalt.
7. **Sjekk formalia**: riktig skjema og versjon, alle felt utfylt, signatur av person med fullmakt, filformat, språk, innleveringsportal, frist.

## Output

1. **Konklusjon** på én linje: «Klar for innlevering», «Klar etter rettelser» eller «Ikke klar».
2. **Høy risiko – må rettes** (kan gi avvisning): tabell med funn, kilde i tilbudet, kravet det gjelder (med kilde), anbefalt rettelse.
3. **Middels risiko – bør rettes** (kan gi poengtrekk eller avvisning etter skjønn).
4. **Lav risiko – kosmetisk**.
5. **Skjulte forbehold**: sitat, krav, ny ordlyd.
6. **Dokumentliste**: alt grunnlaget krever, med status levert / mangler.
7. **Sjekkliste** med status for hvert punkt.

## Absolutte regler

- **Ingen «OK» uten kilde i både grunnlag og tilbud.** Finner du ikke svaret i tilbudet, er status «Mangler».
- **Ved tvil: rapporter.** Det er billigere å vurdere et falskt funn enn å bli avvist.
- Skriv ikke om tilbudet i denne skillen. Foreslå rettelser punktvis; brukeren bestemmer.
- Gi aldri garanti for at tilbudet ikke blir avvist. Avslutt med: «Beslutningsstøtte. Endelig kontroll og signatur er tilbyderens ansvar.»
