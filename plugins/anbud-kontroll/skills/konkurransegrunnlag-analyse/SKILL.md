---
name: konkurransegrunnlag-analyse
description: Analyser et norsk konkurransegrunnlag fra et offentlig anbud (Doffin, Mercell, eu-supply) og lag kravmatrise, frister, tildelingskriterier med vekting og avvisningsfeller. Bruk når brukeren laster opp eller lenker til konkurransegrunnlag, kravspesifikasjon, tilbudsinvitasjon eller anbudsdokumenter og vil vite hva som kreves.
---

# Analyse av konkurransegrunnlag

Lag en fullstendig oversikt over hva tilbyderen må levere, hva som gir poeng og hva som kan føre til avvisning. Resultatet er grunnlaget for alle andre anbudsskills.

## Input

- Konkurransegrunnlaget med alle vedlegg (kravspesifikasjon, prisskjema, kontrakt, tilbudsbrev, ESPD/egenerklæringer).
- Eventuelle tilleggsopplysninger, rettelser og svar på spørsmål publisert av oppdragsgiver. Spør etter disse hvis de ikke er lastet opp; de endrer ofte kravene.

Hvis vedlegg det vises til mangler, list dem opp først og fortsett med det som finnes.

## Fremgangsmåte

1. **Les alt før du skriver.** Les hovedgrunnlaget og alle vedlegg fullt ut. Krav gjemmer seg ofte i kontrakten og prisskjemaet, ikke bare i kravspesifikasjonen.
2. **Identifiser rammene.** Oppdragsgiver, anskaffelsens navn og referansenummer, prosedyre (anbudskonkurranse, konkurranse med forhandling, åpen tilbudskonkurranse), del av FOA (II eller III), anslått verdi, kontraktstype og varighet, opsjoner, delkontrakter.
3. **Trekk ut frister.** Tilbudsfrist (dato og klokkeslett), frist for spørsmål, vedståelsesfrist, planlagt tildeling, oppstart. Oppgi tidssone hvis det ikke er norsk tid.
4. **Bygg kravmatrisen.** Gå gjennom dokumentene i rekkefølge. Hvert krav blir én rad. Bruk malen i `references/kravmatrise-mal.md`.
5. **Klassifiser hvert krav:**
   - **K** = kvalifikasjonskrav (krav til leverandøren)
   - **M** = minstekrav / absolutt krav («skal», «må», «minimum», «ufravikelig»)
   - **T** = gjelder tildelingskriterium (gir poeng)
   - **D** = dokumentasjonskrav (vedlegg som skal leveres)
   - **F** = formkrav (format, språk, filnavn, signatur, innleveringsmåte)
   - **O** = opplysning uten krav
6. **Kartlegg tildelingskriteriene.** Kriterium, vekt i prosent, underkriterier, hva som skal dokumenteres, og hvordan det evalueres (poengskala, prisformel). Noter om klima- og miljøhensyn er vektet, og hvor mye.
7. **Finn avvisningsfellene.** Se `references/regelverk-2026.md`. Typiske feller:
   - absolutte krav som er lette å overse
   - krav om at bestemte skjemaer brukes uendret
   - forbud mot forbehold, eller krav om at forbehold prises
   - signatur av person med fullmakt
   - krav til filformat, språk eller innleveringsportal
   - krav som står i kontrakten men ikke i kravspesifikasjonen
8. **Finn uklarheter og motstrid.** Krav som strider mot hverandre, uklare formuleringer, manglende informasjon. Hver uklarhet blir et forslag til avklaringsspørsmål.

## Output

Lever i denne rekkefølgen:

1. **Sammendrag** (maks 8 linjer): hva som anskaffes, verdi, prosedyre, tilbudsfrist, spørsmålsfrist, de tre viktigste tildelingskriteriene med vekt, og de tre største avvisningsrisikoene.
2. **Frister** som tabell.
3. **Tildelingskriterier** som tabell: kriterium, vekt, underkriterier, dokumentasjon, evalueringsmetode.
4. **Kravmatrise** som tabell eller regneark (.xlsx hvis over 40 krav eller hvis brukeren ber om det).
5. **Avvisningsfeller**: liste med henvisning og hvorfor det er en risiko.
6. **Uklarheter og foreslåtte avklaringsspørsmål**.
7. **Dokumentliste**: alt som skal leveres, med skjema/vedlegg og om det skal signeres.

## Absolutte regler

- **Hver rad og hver påstand skal ha kildehenvisning**: dokumentnavn, side og punkt. Ingen henvisning = ikke ta det med.
- **Siter kravteksten ordrett i kravmatrisen** (kolonnen «Kravtekst»). Ikke parafraser krav; omskrivning er der feiltolkninger oppstår.
- **Ikke fyll hull med antakelser.** Står det ikke i grunnlaget, skriv «Ikke angitt» og lag et avklaringsspørsmål.
- Nevn ikke paragrafnumre du ikke finner i grunnlaget eller i `references/regelverk-2026.md`.
- Avslutt med én linje: «Beslutningsstøtte. Kontroller mot originaldokumentene før innlevering.»
