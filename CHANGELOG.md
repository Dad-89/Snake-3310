# 📜 Diario di Bordo (Changelog)

Ho creato questo file solo perché fa figo e mi fa sentire un ingegnere del software serio, anche se in realtà sto solo muovendo un pixel verde su uno sfondo verde. Ma ehi, ogni grande progetto ha bisogno di un changelog, no?

## [v2.0.0] - Edizione "Ultimate Legend"
*Il giorno in cui Snake ha preso vita (e parola).*

### ✨ Aggiunto
- **Sonoro**: Ho implementato l'API `AudioContext`. Ora il gioco emette suoni. Ho dovuto litigare con le policy di sicurezza di Safari che odiano l'autoplay, ma alla fine ho vinto io.
- **Supporto PWA**: Ho aggiunto `manifest.json` e un Service Worker. Ora Snake è un'app installabile. Così puoi mettere l'icona del 3310 sul tuo telefono da 1500€, proprio di fianco all'app della banca. Il contrasto è poetico.
- **Icona**: Aggiunta un'icona dedicata per la Home Screen, così non sfigura vicino a Instagram.
- **Logica Velocità**: Il gioco accelera ogni 50 punti (5 mele). Preparate i riflessi o il valium.

### 🎨 Migliorato
- **Rendering Schermo**: Il canvas di gioco ora "entra" perfettamente nell'immagine del Nokia grazie a una fustellatura CSS chirurgica e coordinate ricalcolate al millimetro (e a occhio).
- **Immersività**: Ho aggiunto l'effetto `mix-blend-mode: multiply` per simulare le ombre dell'LCD vero. Sembra quasi che ci siano i cristalli liquidi, manca solo la retroilluminazione fioca.
- **Audio Unlock**: Il gioco sblocca l'audio al primo tocco ovunque, aggirando i blocchi del browser moderni che vogliono proteggerci dai suoni improvvisi (poveri illusi).

### 🐛 Risolto
- Il serpente non scappa più sulla scocca di plastica blu. L'ho recintato a dovere.
- Rimossa la scacchiera trasparente dai bordi dell'immagine JPG con uno zoom tattico del 128%.

---

## [v1.0.0] - Edizione "Hello World"
*L'inizio di tutto.*

- Porting iniziale del gioco in HTML5/JS.
- Sistema di controllo touch e tastiera.
- Classifica salvata nel LocalStorage (perché pagare per un database cloud era eccessivo).
- Easter egg nella classifica ("AAAAAAAAA").
