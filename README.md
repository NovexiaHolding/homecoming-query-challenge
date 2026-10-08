# homecoming-query-challenge
Perheäly / Novexia Holding – ICT Student Recruitment Challenge v1.0
# 🚦 Challenge 1: Homecoming Query API v1.0

### Tehtävänanto
Toteuta puhdas ja modulaarinen koodinpätkä (n. 30–80 riviä), joka aktivoituu kotiverkon Wi-Fi-kytkeytymisestä ja kysyy käyttäjän kotiintulotilan 5-portaisella liikennevaloasteikolla.

### Kotiintulotilat (Status Enum):
- 🟩 `GREEN` (Akut ladattu / Avoin)
- 🟨🟩 `LIME` (Latautuu / Normaali arki)
- 🟨 `YELLOW` (Aivoille 15 min aikalisä)
- 🟧 `ORANGE` (Matala toleranssi / Oma rauha)
- 🟥 `RED` (Hälytystila / Täysi lepo)

### Vaatimukset:
1. **Triggeri:** Tunnista kotiverkkoon kytkeytyminen (tai tarjoa simulaatio/mock testausta varten).
2. **Kysely:** Esitä käyttäjälle kotiintulotilan valinta.
3. **Clean Output:** Palauta käyttäjän valinta standardissa JSON-muodossa (esim. Event, Status, Timestamp).

### Arviointikriteerit:
- Selkeä ja puhdas koodi (Clean Code).
- Mukana helppo tapa simuloida kytkeytymistä ilman fyysistä verkkovaihtoa.
