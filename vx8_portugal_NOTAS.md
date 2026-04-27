# Yaesu VX-8 — Memórias Portugal (CHIRP CSV)

Ficheiro: `vx8_portugal_chirp.csv`

## Conteúdo
- Repetidores FM de 2m/70cm (continente e alguns Açores) com `shift` e `CTCSS` preenchidos.
- Canais simplex de chamada e simplex úteis.
- Canais de escuta (airband, marítimo, AIS, PMR, ISM) em RX (`Duplex=off` e `Skip=S` nos canais de escuta).

## Fontes usadas (consultadas em 2026-04-27)
- Radioamador.info (lista/repetidores e páginas de repetidor/associação)
- CT1ENI (lista histórica VHF para Portugal continental)

## Importar no CHIRP
1. Ligue o cabo USB MAXTON RPC--Y8R-U ao VX-8.
2. No CHIRP: **Radio > Download From Radio** (para detetar modelo e guardar backup).
3. **File > Import** e escolha `vx8_portugal_chirp.csv`.
4. Grave para o rádio em **Radio > Upload To Radio**.

## Nota importante
- A rede de repetidores muda com frequência (estado, tom, offset e operação). Valide localmente antes de transmitir.
- Em Portugal, transmissão só com licença de radioamador válida.
- Canais marcados como escuta devem permanecer em receção.
