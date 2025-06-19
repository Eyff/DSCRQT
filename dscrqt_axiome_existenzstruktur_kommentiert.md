# DSCRQT – Axiomatische Struktur zur ontologischen Existenz und Realisation

## Ziel
Dieses Dokument enthält eine kommentierte und vertiefte axiomatische Struktur zur Beschreibung der ontologischen Ebene, auf der Zustände in der Theorie DSCRQT (Dual State Complex Realisation Quantum Theory) verankert sind. Die Axiome A1–A3 betreffen die grundsätzliche Struktur von Existenzzuweisung, Axiom A4 erweitert dies um den Begriff der Realisation als Interaktionskriterium.

---

## Axiomatische Struktur

### 🔹 A1 – Metazustände
Es existieren genau zwei ontologische Metazustände:

\[ \text{MET} = \{\text{Existiert}, \text{Nicht-Existiert}\} \]

Diese sind disjunkt und erschöpfend. Sie beschreiben nicht den Inhalt eines Zustandes, sondern seine Seinskategorie.

---

### 🔹 A2 – Definition eines Zustands
Ein Zustand ist eine konkrete, unterscheidbare und gegebenenfalls messbare Beschreibungseinheit.

\[ \text{ZUSTAND} = \{Z_1, Z_2, \ldots, Z_n\} \]

Diese Zustände können sein:
- klassische physikalische Größen (z. B. Ort, Impuls)
- quantenmechanische Eigenzustände (z. B. Spin-up, Spin-down)
- qualitative Merkmale (z. B. Aggregatszustände wie Eis, Wasser, Dampf)

---

### 🔹 A3 – Ontologische Zuweisung
Jeder Zustand gehört **entweder** dem Metazustand „Existiert“ **oder** „Nicht-Existiert“ an. Dritte Optionen oder gleichzeitige Zuordnung sind ausgeschlossen:

\[
\forall Z \in \text{ZUSTAND}:\quad (Z \in \text{Existiert}) \lor (Z \in \text{Nicht-Existiert}) \quad \land \quad \neg((Z \in \text{Existiert}) \land (Z \in \text{Nicht-Existiert}))
\]

Dies ist die formale Entsprechung des aristotelischen Satzes vom ausgeschlossenen Dritten, angewendet auf Seinszuweisungen.

---

### 🔹 A4 – Realisation und Nicht-Realisation
Zur Unterscheidung innerhalb der Metazustände wird die Begriffszuordnung Realisation ↔ Interaktion eingeführt:

- **Realisiert:**  
  Ein Zustand gilt als realisiert, wenn er dem Metazustand „Existiert“ zugehört **und mit der Umwelt interagiert**. Er entfaltet Wirkung, Information oder messbare Veränderung. Er ist damit **innerhalb des Universums beobachtbar oder kausal wirksam**.

- **Nicht-Realisiert (potenziell):**  
  Ein Zustand ist nicht realisiert, wenn er dem Metazustand „Nicht-Existiert“ zugewiesen ist oder – obwohl existierend – **keinerlei Wechselwirkung mit der Umwelt entfaltet**. Er ist dem Universum faktisch verborgen und tritt nicht in Erscheinung.

Formalisierung (inkl. Interaktionskomponente):

\[
\text{Realisiert}(Z) \Leftrightarrow Z \in \text{Existiert} \land \text{Interagiert}(Z)
\]
\[
\text{Nicht-Realisiert}(Z) \Leftrightarrow Z \in \text{Nicht-Existiert} \lor \neg\text{Interagiert}(Z)
\]

Diese Definition ermöglicht es, zwischen **ontologischer Seinszuweisung** und **physikalischer Wirksamkeit** zu unterscheiden – ein zentrales Unterscheidungsmerkmal in der DSCRQT.

---

## Weiteres Vorgehen
Diese Axiomenstruktur stellt die **erste Version** eines möglichen ontologischen Rahmens für die DSCRQT dar. Weitere Axiome können folgen, um Dynamik, Zeitstruktur, Beobachtung und mathematische Kopplung genauer zu erfassen. Folgende Themenfelder sind angedacht, aber noch nicht ausgearbeitet:

- A5: Zeitabhängige Realisation (temporale Strukturierung)
- A6: Rolle von Messung und Beobachtung als Übergang zwischen Nicht-Realisation und Realisation
- A7: Verbindung zur mathematischen Darstellung in komplexen Vektorräumen (z. B. durch Projektionsoperatoren, Norm, Phase)

