# 🐼 Panda Food Calculator

Una bellissima app web responsive per calcolare il peso del cibo una volta cotto, con un'interfaccia mobile-friendly decorata con simpatici panda!

## 📱 Caratteristiche

- **Calcolo automatico** del peso della porzione cotta
- **Design responsive** ottimizzato per dispositivi mobile
- **Interfaccia moderna** con glassmorphism e animazioni fluide
- **Tema panda** con animazioni divertenti
- **Validazione input** intelligente
- **Effetti celebrativi** quando si ottiene un risultato

## 🧮 Formula di calcolo

La formula utilizzata è:
```
Porzione Cotta = (Porzione Cruda ÷ Peso Crudo Totale) × Peso Cotto Totale
```

## 📂 Struttura dei file

```
panda-food-calculator/
├── index.html          # File principale dell'app
├── README.md           # Questo file
└── .gitignore          # File per ignorare file non necessari
```


##Accedere all'app
- L'app sarà disponibile all'indirizzo: `https://simoneloru.github.io/panda-food-calculator/`
- Puoi trovare il link esatto nella sezione **Pages** delle impostazioni

## 🔧 Personalizzazioni possibili

### Cambiare i colori
Nel file `index.html`, cerca questi selettori CSS per modificare i colori:
- `.app-card` - Sfondo principale
- `.calculate-btn` - Pulsante di calcolo
- `body` - Gradiente di sfondo

### Aggiungere più validazioni
Nella funzione `calculatePortion()` puoi aggiungere controlli aggiuntivi come:
```javascript
if (cookedWeight > rawWeight * 1.5) {
    showError('🤔 Il peso cotto sembra troppo alto rispetto al crudo');
    return;
}
```

### Modificare le animazioni
Puoi personalizzare le animazioni CSS modificando i `@keyframes` nel tag `<style>`.

## 🐛 Risoluzione problemi

### L'app non si carica
- Verifica che il file si chiami esattamente `index.html`
- Controlla che GitHub Pages sia attivato nelle impostazioni
- Aspetta 5-10 minuti dopo l'attivazione

### Il calcolo non funziona
- Apri gli strumenti per sviluppatori (F12) per vedere eventuali errori
- Verifica che tutti gli input abbiano valori numerici validi

### Su mobile non funziona bene
- L'app è ottimizzata per mobile, ma assicurati che il viewport sia configurato correttamente
- Il meta tag viewport è già incluso nel codice

## 📱 Compatibilità

- ✅ Chrome/Chromium (Desktop/Mobile)
- ✅ Firefox (Desktop/Mobile) 
- ✅ Safari (Desktop/Mobile)
- ✅ Edge
- ✅ Tutti i dispositivi iOS e Android moderni

## 🎯 Esempi di utilizzo

1. **Riso**: 100g crudo → 250g cotto. La mia porzione: 80g crudo → 200g cotto
2. **Pasta**: 100g cruda → 200g cotta. La mia porzione: 75g cruda → 150g cotta
3. **Carne**: 200g cruda → 150g cotta. La mia porzione: 120g cruda → 90g cotta

## 🆔 Crediti

Creato con ❤️ e 🐼 per semplificare il calcolo delle porzioni in cucina!

---

### 💡 Suggerimenti per l'uso

- Salva l'app nella home screen del tuo telefono per un accesso rapido
- I valori decimali sono supportati (es. 85.5g)
- L'app funziona offline una volta caricata
- Usa il pulsante "Pulisci tutto" per resettare rapidamente tutti i campi

**Buona cucina con i panda! 🐼👨‍🍳**
