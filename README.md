# Anbudsskriver – norske Claude-skills for offentlige anbud

Skills for leverandører som skriver tilbud på offentlige anskaffelser i Norge. Laget for norsk regelverk (anskaffelsesloven og anskaffelsesforskriften, oppdatert etter endringene 1. juli 2026), norske kontraktsstandarder (SSA, NS 8405/8406/8407) og norske innleveringsportaler.

## Gratis: anbud-kontroll

| Skill | Hva den gjør |
|---|---|
| `konkurransegrunnlag-analyse` | Leser konkurransegrunnlaget med vedlegg og lager kravmatrise, frister, tildelingskriterier med vekting, avvisningsfeller og forslag til avklaringsspørsmål. Alle krav siteres ordrett med side og punkt. |
| `avvisningssjekk` | Kontrollerer tilbudet mot grunnlaget før innlevering: manglende vedlegg, avvik fra absolutte krav, skjulte forbehold, signatur, format, pris og konsistens. |

## Pro: anbud-pro

Åtte skills til for hele tilbudsprosessen, koblet til bedriftens eget tilbudsbibliotek:

| Skill | Hva den gjør |
|---|---|
| `go-no-go` | Vurderer om dere bør by, med stopp-kriterier, vinnersjanse og innsatsanslag |
| `kvalifikasjonspakke` | ESPD/egenerklæring, attester, referanser og sertifikater med gyldighetskontroll |
| `losningsbeskrivelse` | Skriver svar på tildelingskriteriene etter vektingen, fra egne vunne tilbud |
| `cv-og-referanser` | Velger og tilpasser CV-er og referanseprosjekter mot kravene |
| `prisskjema-kontroll` | Finner formelfeil, overskrevne formler, tekst i priskolonner, skjulte ark og strukturendringer (med skript) |
| `kontraktssjekk` | Risiko i SSA/NS-kontrakten og skjulte forbehold i tilbudet |
| `avklaringssporsmal` | Spørsmål til oppdragsgiver som ikke avslører egen løsning |
| `etter-tildeling` | Frister, kontroll av evalueringen, innsyn, klage og lærdom til neste tilbud |

Pro leveres med oppsett av tilbudsbiblioteket og oppdateringer når regelverket endres. Kontakt: Namsvatn Markonsult – eanamsvatn@gmail.com.

## Installering

### Claude Code og Claude-appen (plugins)

```
/plugin marketplace add Sporg-no/anbudsskriver
/plugin install anbud-kontroll@anbudsskriver
```

### claude.ai (enkeltskills)

Last ned zip-filen for hver skill fra *Releases* og last den opp som skill i Claude-innstillingene. Hver zip er selvstendig og inneholder regelverksgrunnlaget.

## Bruk

Last opp konkurransegrunnlaget (PDF/Word/Excel) og skriv for eksempel:

- «Analyser dette konkurransegrunnlaget.»
- «Sjekk om tilbudet vårt kan bli avvist.» (last opp både grunnlag og tilbud)

## Viktig

Skillene er beslutningsstøtte, ikke juridisk rådgivning. Kontroller alltid mot originaldokumentene og gjeldende regelverk på lovdata.no før innlevering. Regelverksgrunnlaget er sist verifisert 22.10.2026.

## Lisens

`anbud-kontroll`: MIT. `anbud-pro`: proprietær, se plugin-mappen.
