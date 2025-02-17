Generatore di Battute Random
Generatore di battute random che usa l'API di jokeapi.dev.

Introduzione
Questo progetto è un generatore di battute casuali costruito con Node.js e Express. Recupera le battute dall'API jokeapi.dev e le serve tramite un endpoint API.

Installazione
Per iniziare con questo progetto, clona il repository e installa le dipendenze:

```
bash
git clone https://github.com/xaxoman/rand_joke.git
cd rand_joke
npm install
```
## Utilizzo
Per avviare il server, esegui:
```
bash
npm start
```

Il server sarà in esecuzione su `http://localhost:3000`

Endpoint API
GET /api/joke?category=<category>: Recupera una battuta casuale. La categoria è opzionale e predefinita a Any.

Esempio:
```
bash
curl http://localhost:3000/api/joke?category=Programming
```

Dipendenze
- express: ^4.21.2
- node-fetch: ^3.3.2 (necessario per versioni di Node.js < 18)
- sv443-joke-api: ^0.1.0
- nodemon: ^3.1.9 (dipendenza di sviluppo)

Licenza
Questo progetto è concesso in licenza sotto Apache 2.0 license.
