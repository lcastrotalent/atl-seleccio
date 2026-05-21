# Generador de Pack de Difusió · ATL Selecció

Eina interna per a l'àrea de Selecció d'ATL (Ens d'Abastament d'Aigua Ter Llobregat).

Genera automàticament el pack complet de difusió d'una oferta de treball a partir de la DPT o convocatòria ATRI.

---

## Accés a l'eina

👉 **[Obrir l'eina](https://lcastrotalent.github.io/atl-seleccio/)**

---

## Com utilitzar-la

### Primera vegada

1. Obre l'eina a l'enllaç de dalt
2. A l'apartat **Clau d'API**, enganxa la clau que et faciliti el responsable de l'equip
3. Clica **Desar** — la clau es guarda al teu navegador i no caldrà tornar-la a introduir mai més

### Cada vegada que generis un pack

1. **Nom del lloc** — escriu el títol exacte del lloc de treball
2. **Codi d'oferta** — introdueix el codi de la convocatòria (ex: ATL001-26)
3. **Tipus de perfil** — selecciona el perfil que millor s'ajusta al lloc
4. **Document** — adjunta la DPT o oferta ATRI en format `.docx`, `.pdf` o `.txt`
   - També pots enganxar el text directament al camp de text si no tens el fitxer a mà
5. Clica **Generar pack de difusió**
6. Espera uns 30-60 segons mentre es generen els 6 apartats
7. Quan acabi, clica el botó **Obrir PDF per desar**
8. S'obrirà una nova pestanya amb el document complet
9. A la nova pestanya, prem **Ctrl+P** (Windows) o **Cmd+P** (Mac)
10. A l'apartat **Destinació**, selecciona **Desar com a PDF**
11. Clica **Desar** — el fitxer es dirà automàticament `CODI - Nom del lloc.pdf`

---

## Contingut del pack generat

| Apartat | Contingut |
|---------|-----------|
| **A. Fitxa executiva** | Taula resum per a Selecció: canals, missatge d'atracció, requisits, CTA, advertències jurídiques |
| **B. Versió ATRI** | Text institucional complet llest per a la convocatòria formal |
| **C. LinkedIn** | Post complet, versió breu i hashtags |
| **D. Portals de feina** | Anunci complet per a InfoJobs, Indeed, Feina.cat (13 apartats) |
| **E. Pack FP** | Email al centre, text per a borsa, missatge per a tutor/a i per a alumnat |
| **F. Pla de canals** | Targetes operatives per canal amb prioritat, moment, acció i indicadors |

---

## Notes importants

- Els textos generats estan **llestos per publicar** — reviseu-los però no haureu de reescriure'ls
- El canal d'inscripció sempre és **www.atl.cat**
- No es modifiquen requisits legals, terminis ni condicions formals
- No s'inventen salaris, beneficis ni condicions no publicades
- El cost per pack generat és aproximadament **0,08-0,12 €**
- La clau d'API es guarda **només al vostre navegador** — ningú extern hi té accés

---

## Problemes freqüents

**No es carrega el fitxer .docx o .pdf** → Copieu el text del document i enganxeu-lo al camp de text manual que apareix a sota de la zona de pujada.

**Error de clau d'API** → Comproveu que la clau comença per `sk-ant-` i que heu clicat **Desar** després d'introduir-la.

**No es generen tots els apartats** → Torneu a intentar-ho. Si el problema persisteix, contacteu amb el responsable de l'eina.

**El botó "Obrir PDF per desar" no fa res** → Comproveu que el navegador permet finestres emergents per a aquest lloc. A Chrome: icona de bloqueig a la barra d'adreces → Permet finestres emergents.

**El PDF no té el nom correcte** → Assegureu-vos d'haver introduït el codi i el nom del lloc abans de generar.

---

*Eina desenvolupada per a ús intern de l'àrea de Selecció d'ATL. Document confidencial.*
