# 📄 Software Requirements Specification (SRS)

## 1. Inngangur
### 1.1 Tilgangur
Viðmót fyrir nemendur og kennara, til að tala saman og gera verkefni

### 1.2 Umfang
Nemendur geta gert verkefni án þriðja aðilla forrita, kennarar geta gefið endurgjöf. Nemendur geta talað við aðra í sömu kúrsum

### 1.3 Skilgreiningar
| Hugtak | Skýring |
|--------|---------|
| SRS | Software Requirements Specification |
| Issue | Umræða/atriði í GitHub sem tengist ákveðinni kröfu |

### 1.4 Tilvísanir
- ISO/IEC/IEEE International Standard - Systems and software engineering -- Life cycle processes -- Requirements engineering," in ISO/IEC/IEEE 29148:2018(E) , vol., no., pp.1-104, 30 Nov. 2018, doi: 10.1109/IEEESTD.2018.8559686.ISO/IEC/IEEE 29

---

## 2. Almenn lýsing
### 2.1 Notendahópar
- Nemendur
- Kennarar
- Tæknideild

### 2.2 Viðskiptaávinningur
- Léttara fyrir nemendur að vinna saman, og að gera verkefni
- Léttara fyrir kennara að gefa út verkefni og fara yfir þau

---

## 3. Kröfur fyrir kerfið

### 3.1 Viðskiptakröfur
| ID  | Titill | Issue |
|-----|--------|-------|
| BR1 | Gera léttara að gera hópavinnu saman | [#6](../../issues/6) |
| BR2 | Auðvelda samskipti | [#2](../../issues/2) |

### 3.2 Kerfiskrafa
| ID  | Titill | Issue |
|-----|--------|-------|
| SR1 | Ský og Microsoft Office | [#3](../../issues/3) |

### 3.3 Fídusar (Features)
| ID  | Titill | Issue |
|-----|--------|-------|
| F1  | Samvinnuskjöl (Office/OneDrive) | [#36](../../issues/36) |
| F2  | Comment frá kennara | [#28](../../issues/28) |
| F3  | Hópsímtöl | [#15](../../issues/15) |

### 3.4 Notendakröfur
| ID  | Titill | Fídus | Issue |
|-----|--------|-------|-------|
| UR1 | breyta comments | [Comment frá kennara](../../issues/28) | [#43](../../issues/43) |
| UR2 | Opt out | [Comment frá kennara](../../issues/28) | [#29](../../issues/29) |
| UR3 | Vinna samtímis | [Samvinnuskjöl (Office/OneDrive)](../../issues/36) | [#37](../../issues/37) |
| UR4 | Deila skjá | [Hópsímtöl](../../issues/15) | [#18](../../issues/18) |
| UR5 | Notandi hópsímtal | [Hópsímtöl](../../issues/15) | [#17](../../issues/17) |
| UR6 | Engin ytri forrit | [Samvinnuskjöl (Office/OneDrive)](../../issues/36) | [#5](../../issues/5) |

### 3.5 Virknikröfur
| ID  | Titill | Notendakrafa | Issue |
|-----|--------|--------------|-------|
| FR1 | edit timestamp | [breyta comments](../../issues/43) | [#46](../../issues/46) |
| FR2 | delete takki | [breyta comments](../../issues/43) | [#45](../../issues/45) |
| FR3 | edit takki | [breyta comments](../../issues/43) | [#44](../../issues/44) |
| FR4 | Deiling skjala | [Engin ytri forrit](../../issues/5) | [#42](../../issues/42) |
| FR5 | Auðkenning notenda | [Vinna samtímis](../../issues/37) | [#41](../../issues/41) |
| FR6 | Sýnilegar breytingar | [Vinna samtímis](../../issues/37) | [#40](../../issues/40) |
| FR7 | Sjá virka nemendur í skjölum | [Vinna samtímis](../../issues/37) | [#39](../../issues/39) |
| FR8 | Vistun skjala | [Engin ytri forrit](../../issues/5) | [#38](../../issues/38) |
| FR9 | hefja símtal takki | [Notandi hópsímtal](../../issues/17) | [#21](../../issues/21) |
| FR10 | hópsmeðlimir geta ennþá séð | [Opt out](../../issues/29)  | [#33](../../issues/33) |
| FR11 | opt in takki | [Opt out](../../issues/29) | [#31](../../issues/31) |
| FR12 | opt out takki | [Opt out](../../issues/29) | [#35](../../issues/35) |
| FR13 | Nýtt verkefni innan kerfisins | [Engin ytri forrit](../../issues/5) | [#4](../../issues/4) |
| FR14 | ein deiling í einu | [Deila skjá](../../issues/18) | [#26](../../issues/26) |
| FR15 | hætta skjádeilingu takki | [Deila skjá](../../issues/18) | [#25](../../issues/25) |
| FR16 | deila skjá hnappur | [Deila skjá](../../issues/18) | [#24](../../issues/24) |
| FR17 | 100 notendur | [Notandi hópsímtal](../../issues/17) | [#23](../../issues/40) |
| FR18 | hópsímtal notification | [Notandi hópsímtal](../../issues/17) | [#22](../../issues/22) |

### 3.6 Viðskiptareglur
| ID  | Titill | Issue |
|-----|--------|-------|
| BRG1 | Nemendur geta ekki messagað hvern sem er í HÍ | [#52](../../issues/52) |
| BRG2 | Aðeins notendur með Uglu aðgang | [#51](../../issues/51) |


### 3.7 Gæðaeiginleikar
| ID  | Titill | Issue |
|-----|--------|-------|
| QR1 | gott syncing, erfitt að eyða annarra manna vinnu | [#50](../../issues/50) |
| QR2 | Létt að bæta við nýjum docker | [#47](../../issues/47) |

### 3.8 Takmarkanir
| ID  | Titill | Issue |
|-----|--------|-------|
| C1 | íslenska og enska | [#34](../../issues/34) |
| C2 | innan Uglu | [#32](../../issues/32) |

### 3.9 Ytri skil (Interfaces)
| ID  | Titill | Issue |
|-----|--------|-------|
| IF1 | Office 365 | [#49](../../issues/49) |
| IF2 | Ugla | [#48](../../issues/48) |

---

## 4. Viðaukar
### 4.1 Orðalisti
- Skilgreina lykilhugtök.

### 4.2 Samþykktir
- Kennari: ____________________  
- Nemandi: ____________________
