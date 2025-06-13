# 🧠 Gold Trading Bot (In Entwicklung)

Ein modularer, datengestützter Trading-Bot für den Handel mit **XAU/USD (Gold)**.  
Das Projekt kombiniert **technische Analyse**, **News-Sentiment** und **Marktindikatoren**, um präzise Handelssignale zu erzeugen.

---

## 📌 Funktionen (Stand: In Entwicklung)

- 📈 **Technische Analyse** (MACD, RSI, Bollinger Bands, EMA u. a.)
- 📰 **Fundamentalanalyse & News-Sentiment** über echte Finanz-APIs
- 🧠 **Signal-Kombination** mit Begründung (kein Autotrading!)
- 🌐 **REST-API** (Flask) zur Abfrage von Handelssignalen
- 📊 **HTML-Reports** für Analyse-Ergebnisse
- 🛠️ Deployment-Skripte für Backend, Frontend und Mobile

---

## 🖼️ Screenshots

### ✅ Erfolgreiches Deployment

![Deployment 1](docs/screenshots/deployment_logs_1.png)
![Deployment 2](docs/screenshots/deployment_logs_2.png)
![Deployment 3](docs/screenshots/deployment_logs_3.png)

### 📈 Generierte Handelssignale

![Signale](docs/screenshots/final_signals.png)

---

## 🚀 Installation & Nutzung

```bash
# Backend starten
cd backend
pip install -r requirements.txt
python src/main.py
```

API ist erreichbar unter: `http://localhost:10000/api/signal`

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
```

---

## 🔐 Hinweis

Das Projekt befindet sich noch in der **aktiven Entwicklung**. Es werden keine realen Trades durchgeführt – es dient nur der **Analyse und Signalgebung**.

---

## 🧑‍💻 Autor

**Mohammad Alfayad**  
GitHub: [Alfayad96](https://github.com/Alfayad96)  
Projektstatus: _Lernprojekt / IHK-Abschlussprojekt_

---

## 📝 Lizenz

Dieses Projekt steht unter der MIT-Lizenz.
