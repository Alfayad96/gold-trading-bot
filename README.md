# 🧠 Gold Trading Bot (In Entwicklung)

🌍 **Live ansehen:** [https://gold-trading-frontend.onrender.com](https://gold-trading-frontend.onrender.com)

Ein modularer, datengestützter Trading-Bot für den Handel mit **XAU/USD (Gold)**.  
Das Projekt kombiniert **technische Analyse**, **News-Sentiment** und **Marktindikatoren**, um präzise Handelssignale zu erzeugen.  
🧰 **Technologie-Stack:** Python, Flask, Pandas, NLTK, TA-Lib, REST-API, React (Frontend)

---

## 📌 Funktionen (Stand: In Entwicklung)

- 📈 **Technische Analyse** (MACD, RSI, Bollinger Bands, EMA u. a.)
- 📰 **Fundamentalanalyse & News-Sentiment** über echte Finanz-APIs
- 🧠 **Signal-Kombination** mit Begründung (kein Autotrading!)
- 🌐 **REST-API** (Flask) zur Abfrage von Handelssignalen
- 📊 **HTML-Reports** für Analyse-Ergebnisse
- 🛠️ Deployment-Skripte für Backend, Frontend und Mobile
- 🐍 **Komplett in Python entwickelt**

---

## 🖼️ Screenshots

### ✅ Erfolgreiches Deployment

![Deployment Schritt 1](https://github.com/Alfayad96/gold-trading-bot/raw/main/LOGS1.png)
![Deployment Schritt 2](https://github.com/Alfayad96/gold-trading-bot/raw/main/LOGS2.png)
![Deployment Schritt 3](https://github.com/Alfayad96/gold-trading-bot/raw/main/LOGS3.png)
![Signale erzeugt](https://github.com/Alfayad96/gold-trading-bot/raw/main/LOGS4.png)

---

## ⚠️ Hinweis zur aktuellen Version

> 🔧 **Die Signale werden bereits erfolgreich erzeugt und gespeichert** (siehe oben),  
> aber **sie werden im Dashboard aktuell noch nicht angezeigt**.  
> Ich arbeite derzeit aktiv daran, das Frontend mit den Signaldaten korrekt zu verbinden.

### 📊 Aktuelles Dashboard

![Dashboard Screenshot](https://github.com/Alfayad96/gold-trading-bot/raw/main/Dashboard.png)

---

## 🧪 Beispiel-Antwort (API `/api/signal`)

```json
{
  "signal": "buy",
  "confidence": 87,
  "entry_price": 2312.5,
  "stop_loss": 2294.0,
  "take_profit": 2348.0,
  "reason": "Technische Indikatoren bullish, Sentiment positiv"
}
🔐 Hinweis

Das Projekt befindet sich noch in der aktiven Entwicklung. Es werden keine realen Trades durchgeführt – es dient nur der Analyse und Signalgebung.
🧑‍💻 Autor

Mohammad Alfayad
GitHub: Alfayad96
Projektstatus: Lernprojekt / IHK-Abschlussprojekt
📝 Lizenz

Dieses Projekt steht unter der MIT-Lizenz.
