# Respo‑Rotation – Systemische Wirbel‑Rotation

Respo‑Rotation ist ein technisches Rotations‑System, das auf einem physikalischen Whirlpool‑Modell basiert.  
Es erzeugt **Rotation durch Sog**, nicht durch Animation.  
Damit ist Respo‑Rotation ein echtes **System‑Wirbel‑Modell**, das Daten, Reihenfolgen und Status‑Ketten umlaufen lässt.

---

## 🔹 Grundidee

Wenn Wasser durch eine kleine Öffnung abläuft, entsteht:

1. **Sog**  
2. **Wirbel**  
3. **Rotation**  
4. **Extra‑Speed (bis 720° vor 2 cm Abfall)**

Dieses physikalische Verhalten wird in Respo‑Rotation technisch nachgebildet.

---

## 🔹 System‑Rotation

Respo‑Rotation rotiert:

- die BOERSE‑Kette  
- die POS‑Positionen  
- die Reihenfolge der Slots  
- die Ghost‑Scan‑Impulse  
- die Status‑Antworten  

Damit entsteht eine **echte Rotation**, die nicht visuell, sondern systemisch ist.

---

## 🔹 Whirlpool‑Power‑Modell (WPM)

Respo‑Rotation nutzt ein eigenes Modell:

- **Trigger** – kleiner Impuls  
- **Pressure** – Druckunterschied  
- **Pull** – Sog entsteht  
- **Swirl** – Wirbel bildet sich  
- **Rotation** – bis 720°  
- **Boost** – Extra‑Speed  

Dieses Modell erzeugt die charakteristische Respo‑Rotation‑Dynamik.

---

## 🔹 Rotation‑Code

Die Rotation entsteht durch Umlauf der Kette:

```js
function rotateChain() {
    const first = chain.shift();
    chain.push(first);
}

