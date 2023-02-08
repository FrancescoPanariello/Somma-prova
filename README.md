# RANDOM PARALLEL TESTING   
## USING RANDOOP AND EMMA

GitHub Actions per testare in parallelo randomicamente classi java utilizzando randoop per la generazione dei test ed Emma per ottenere il report sulla coverage

## Utilizzo

-Clona la repository
-Carica il progetto nella repository clonata
-Modifica il file "lista.txt" inserendo il nome delle classi da testare
-Modifica lo script main.yml inserendo appositamente il nome del progetto da testare 

## Output

Al termine della GitHub Action saranno creati 2 Artifacts(Si trovano in basso nella sezione summary)
- Emma Reports, che contiene le cartelle coverage_?, in cui sono presenti i report parziali "coverage_?.html" delle singole sessioni e i test generati che trovano un fallimento 
- Coverage, che contiene il report "coverageunion.html" finale sulla copertura di tutti i test eseguiti

Cliccando sugli Artifacts vengono scaricati i .zip  
