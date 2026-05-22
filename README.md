# ✝ Theological Library

A curated digital library of primary sources in Christian theology — Scripture, Church Fathers, Ecumenical Councils, and Magisterial documents — built for deep theological study and reference.

This repository serves as the extended knowledge base for a Claude AI theological study project, and as a permanent personal reference library.

---

## Library Contents

### 📖 Current Documents (Core Library)

These documents are also stored in the Claude project knowledge for instant semantic search.

**Scripture**
- New American Standard Bible 2020 (NASB 2020)

**Apostolic Fathers** *(those who knew the Apostles personally)*
- The Didache (c. 50–120 AD)
- St. Clement of Rome — First Epistle to the Corinthians (c. 96 AD)
- St. Ignatius of Antioch — Seven Letters (c. 107 AD)
- St. Polycarp of Smyrna — Epistle to the Philippians (c. 110–140 AD)
- The Martyrdom of Polycarp (c. 155–156 AD)

**Early Apologists**
- Justin Martyr — First Apology (c. 155 AD)
- Justin Martyr — Second Apology (c. 155–161 AD)

**Church Fathers**
- St. Athanasius of Alexandria — On the Incarnation (c. 318 AD)
- St. Augustine of Hippo — Confessions, Books I/VII/VIII/IX (397–400 AD)
- St. Leo the Great — Tome of Leo (449 AD)

**The Seven Ecumenical Councils**
- Nicaea I (325) — Divinity of Christ; Homoousios
- Constantinople I (381) — Divinity of the Holy Spirit; Creed
- Ephesus (431) — Mary as Theotokos; Against Nestorius
- Chalcedon (451) — Two natures, one person
- Constantinople II (553) — Against Three Chapters; Origenism
- Constantinople III (680–681) — Two wills; Against Monothelitism
- Nicaea II (787) — Veneration of icons

**Vatican I (1869–1870)**
- Dei Filius — On Faith and Reason
- Pastor Aeternus — Papal Infallibility

**Vatican II (1962–1965)**
- Lumen Gentium — On the Church
- Dei Verbum — On Divine Revelation

**Modern Magisterium**
- Fides et Ratio — John Paul II (1998)

**Catechism**
- Catechism of the Catholic Church (CCC)

---

### 📚 Extended Library (GitHub Only)

Fetched by Claude on demand. *Priority order for transcription:*

**🔴 Critical — Next to Add**
1. Irenaeus — Against Heresies (c. 180 AD)
2. Augustine — On the Trinity (399–419 AD)
3. Council of Trent (1545–1563)
4. Thomas Aquinas — Summa Theologica, Prima Pars (1265–1274)
5. Gaudium et Spes — Vatican II (1965)

**🟠 High Priority**
6. Gregory of Nazianzus — Five Theological Orations (c. 380 AD)
7. John of Damascus — On the Orthodox Faith (c. 730 AD)
8. Anselm of Canterbury — Cur Deus Homo (1098 AD)
9. Basil the Great — On the Holy Spirit (375 AD)
10. Veritatis Splendor — John Paul II (1993)

**🟡 Important**
11. Augustine — City of God (413–426 AD)
12. John Henry Newman — Essay on Development of Doctrine (1845)
13. Tertullian — Against Praxeas (c. 213 AD)
14. John Chrysostom — On the Priesthood (c. 390 AD)
15. Bernard of Clairvaux — On Loving God (c. 1135 AD)

**🟢 Mystics & Spirituality**
16. John of the Cross — Dark Night of the Soul (c. 1578 AD)
17. Teresa of Ávila — The Interior Castle (1577 AD)
18. Julian of Norwich — Revelations of Divine Love (c. 1395 AD)
19. Ignatius of Loyola — Spiritual Exercises (1548 AD)

**📜 Historical Witnesses**
20. Josephus — Antiquities (selections on John, James, Jesus)
21. Tacitus — Annals XV.44
22. Pliny the Younger — Letter X.96
23. Deuterocanonical Books (Sirach, Wisdom, Maccabees)

---

## Repository Structure

```
theological-library/
├── README.md                    ← This file
├── LIBRARY_INDEX.md             ← Claude's index (also in project knowledge)
├── current/                     ← Core library documents
│   ├── NASB2020.txt
│   ├── CCC_VERIFIED.md
│   ├── LUMEN_GENTIUM.md
│   └── ... (all 29 current documents)
├── patristics/                  ← Church Fathers
│   ├── IRENAEUS_AGAINST_HERESIES.md
│   ├── AUGUSTINE_ON_TRINITY.md
│   ├── GREGORY_NAZIANZUS_ORATIONS.md
│   └── ...
├── medieval/                    ← Medieval theology
│   ├── AQUINAS_SUMMA_PRIMA_PARS.md
│   ├── COUNCIL_TRENT.md
│   └── ...
├── mystics/                     ← Mystical theology
│   ├── JOHN_OF_THE_CROSS_DARK_NIGHT.md
│   ├── TERESA_INTERIOR_CASTLE.md
│   └── ...
├── modern/                      ← Modern Magisterium
│   ├── GAUDIUM_ET_SPES.md
│   ├── VERITATIS_SPLENDOR.md
│   └── ...
└── secondary/                   ← Historical witnesses & secondary sources
    ├── JOSEPHUS_ANTIQUITIES_SELECTIONS.md
    ├── TACITUS_ANNALS_15.md
    └── ...
```

---

## Sources & Translations

All documents use verified public domain translations from authoritative sources:

| Source | Used For |
|---|---|
| **New Advent** (newadvent.org) | Ante-Nicene Fathers, Nicene & Post-Nicene Fathers, Church Fathers |
| **Ante-Nicene Fathers (ANF)** Vol. 1–10 | Apostolic Fathers, Justin, Irenaeus, Tertullian, Origen |
| **Nicene & Post-Nicene Fathers (NPNF)** Series 1 & 2 | Augustine, Chrysostom, Basil, Gregory, Jerome, Athanasius |
| **Norman Tanner SJ** — *Decrees of the Ecumenical Councils* | All Seven Ecumenical Councils |
| **Vatican.va** | Vatican I, Vatican II, Papal Encyclicals |
| **USCCB / Libreria Editrice Vaticana** | Catechism of the Catholic Church |

---

## How Claude Uses This Library

1. **Project knowledge** holds the 29 core documents for instant semantic search
2. **This repository** holds the full extended library
3. A `LIBRARY_INDEX.md` in project knowledge lists every GitHub document with its raw URL
4. When a topic requires a document from GitHub, Claude fetches it via `web_fetch`
5. The full text is then available for that conversation

---

## Study Guidelines

This library is governed by a source hierarchy:
- **Tier 1:** Scripture + Apostolic Fathers
- **Tier 2:** Church Fathers + Ecumenical Councils
- **Tier 3:** Medieval Scholastics + Magisterial Documents
- **Tier 4:** Serious theological scholarship (all traditions)

*"The weight of a source is determined by its proximity to the original deposit of faith."*

---

*Built to the glory of God.*
*Blessed be our Lord and Savior Christ Jesus.*
