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
| BR1 | [Titill á viðskiptakröfu] | [#12](../../issues/12) |
| BR2 | [Titill á viðskiptakröfu] | [#13](../../issues/13) |

### 3.2 Kerfiskrafa
| ID  | Titill | Issue |
|-----|--------|-------|
| SR1 | [Titill á kerfiskröfu] | [#14](../../issues/14) |

### 3.3 Fídusar (Features)
| ID  | Titill | Issue |
|-----|--------|-------|
| F1  | Samvinnuskjöl (Office/OneDrive) | [#36](../../issues/36) |
| F2  | Comment frá kennara | [#28](../../issues/28) |
| F3  | [Titill á fídusi] | [#17](../../issues/17) |

### 3.4 Notendakröfur
| ID  | Titill | Fídus | Issue |
|-----|--------|-------|-------|
| UR1 | breyta comments | F1 | [#43](../../issues/43) |
| UR2 | Opt out | F1 | [#29](../../issues/29) |
| UR3 | [Notendakrafa 3] | F2 | [#20](../../issues/20) |
| UR4 | [Notendakrafa 4] | F2 | [#21](../../issues/21) |
| UR5 | [Notendakrafa 5] | F3 | [#22](../../issues/22) |
| UR6 | [Notendakrafa 6] | F3 | [#23](../../issues/23) |

### 3.5 Virknikröfur
| ID  | Titill | Notendakrafa | Issue |
|-----|--------|--------------|-------|
| FR1 | edit timestamp | UR1 | [#46](../../issues/46) |
| FR2 | delete takki | UR1 | [#45](../../issues/45) |
| FR3 | edit takki | UR1 | [#44](../../issues/44) |
| FR4 | Deiling skjala | UR2 | [#42](../../issues/42) |
| FR5 | Auðkenning notenda | UR2 | [#41](../../issues/41) |
| FR6 | Sýnilegar breytingar | UR2 | [#40](../../issues/40) |
| FR7 | Sjá virka nemendur í skjölum | UR3 | [#39](../../issues/39) |
| FR8 | Vistun skjala | UR3 | [#38](../../issues/38) |
| FR9 | Vinna samtímis | UR3 | [#37](../../issues/37) |
| FR10 | hópsmeðlimir geta ennþá séð | UR4 | [#33](../../issues/33) |
| FR11 | opt in takki | UR4 | [#31](../../issues/31) |
| FR12 | opt out takki | UR4 | [#35](../../issues/35) |
| FR14 | ein deiling í einu | UR5 | [#26](../../issues/26) |
| FR15 | hætta skjádeilingu takki | UR5 | [#25](../../issues/25) |
| FR16 | deila skjá hnappur | UR6 | [#24](../../issues/24) |
| FR17 | 100 notendur | UR6 | [#23](../../issues/40) |
| FR18 | hópsímtal notification | UR6 | [#22](../../issues/22) |

### 3.6 Viðskiptareglur
| ID  | Titill | Issue |
|-----|--------|-------|
| BRG1 | [Viðskiptaregla] | [#42](../../issues/42) |
| BRG2 | [Viðskiptaregla] | [#43](../../issues/43) |


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
