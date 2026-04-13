# PLC_Project

# Descrizione
Mini linea automatizzata sviluppata in TwinCAT 3 per simulare un sistema industriale.

# Architettura
- MAIN: logica di coordinamento
- FB_Motor: gestione motore con state machine
- FB_Valve: gestione valvola con apertura/chiusura

## Funzionamento
Un sensore rileva un pezzo sul nastro. Dopo un ritardo, viene attivata una valvola per espulsione.

## Caratteristiche
- Structured Text (TwinCAT 3)
- State machine per attuatori
- Gestione fault (timeout, interlock)
- Simulazione segnali
