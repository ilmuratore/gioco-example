# Gioco Example — Fondamenti di Unity e C#

Progetto Unity di esempio utilizzato durante le lezioni sui **fondamenti di Unity e C#**.  
Serve come punto di partenza per gli studenti: contiene una scena base, la pipeline di rendering 2D (URP) e i principali pacchetti necessari per seguire il corso.

---

## Requisiti

| Strumento | Versione minima |
|-----------|----------------|
| Unity Editor | **6000.3.16f1** (Unity 6) |
| Visual Studio / Rider | qualsiasi versione recente con supporto C# |
| Git | 2.x o superiore |

> Scarica Unity Hub da [unity.com/download](https://unity.com/download) e installa la versione indicata sopra.

---

## Struttura del progetto

```
Assets/
├── Scenes/          # Scene di esempio
├── Settings/        # Configurazioni URP e rendering
Packages/            # Dipendenze Unity (gestite automaticamente)
ProjectSettings/     # Impostazioni di progetto
```

---

## Pacchetti inclusi

- **Universal Render Pipeline (URP)** — rendering moderno ottimizzato per 2D
- **2D Animation / Sprite Shape / Tilemap** — strumenti per giochi 2D
- **Input System** — gestione input cross-platform
- **Visual Scripting** — scripting visuale per chi inizia
- **Timeline** — animazioni e cutscene
- **Test Framework** — testing automatizzato

---

## Come aprire il progetto

1. Clona la repository:
   ```bash
   git clone https://github.com/ilmuratore/gioco-example.git
   ```
2. Apri **Unity Hub** → **Open** → seleziona la cartella `gioco-example`.
3. Unity installerà automaticamente tutti i pacchetti al primo avvio (può richiedere alcuni minuti).
4. Apri la scena `Assets/Scenes/SampleScene.unity` per iniziare.

---

## Argomenti del corso

- Interfaccia di Unity e navigazione nell'Editor
- GameObject, Component e Transform
- Scripting C#: variabili, condizioni, cicli, classi
- MonoBehaviour: `Start()`, `Update()`, eventi
- Fisica 2D: Rigidbody2D, Collider2D
- Input System e gestione del giocatore
- Tilemap e costruzione dei livelli
- Audio, UI e scene management

---

## Contribuire

Questo repository è principalmente a scopo didattico.  
Gli studenti possono fare fork e sperimentare liberamente nel proprio spazio.  
Per segnalare errori o proporre miglioramenti al materiale del corso, apri una **Issue**.

---

## Licenza

Distribuito sotto licenza **MIT**. Vedi il file [LICENSE](LICENSE) per i dettagli.
