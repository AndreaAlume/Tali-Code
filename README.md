# Tali-Code

## Descrizione

Tali Code è uno strumento per lo sviluppo software pensato per velocizzare il lavoro del developer ed eliminare gli errori di sintassi migliorando l'accuratezza durante la fase di scrittura del codice. La semplicità di Tali e la potenza dell'AI generativa rendono il tutto un processo di coding fluido e privo di intoppi.

# Analisi funzionalità

Verranno elencate le funzionalità da realizzare per il progetto con una descrizione approfondita.

## Speech to text avanzata

Questa funzionalità prevede un **input vocale** da parte dell'utente in un linguaggio umano e il software dovrà tradurlo in codice.

Ciò che renderà davvero interessante questa feature sarà:

- la sua estrema accuratezza nella stesura del codice in merito alla sintassi.
- il delay (che dovrà essere minimo pari a 0 o quasi) tra l'input vocale dell'utente e l'output del codice scritto.
- l'abilità di capire i diversi intenti nello stesso input.
    - Ad esempio l'utente dice: *"Creami una funzione 'somma' che sommi la variabile intera x più la variabile intera y e mi restituisca la somma z"* e il programma scrive istantaneamnte
        ```python
        def somma(x, y): {
            z = x + y
            return z
        }
        ```
> [!ATTENTION]
> Sarà necessario stabilire bene la forma e il grado di specificita 