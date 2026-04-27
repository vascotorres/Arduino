# Yaesu VX-8 — Memórias Portugal (CHIRP CSV)

Ficheiro: `vx8_portugal_chirp.csv`

## O que foi reforçado nesta versão
- Pesquisa ampliada para confirmar se havia mais repetidores além dos já listados.
- Inclusão de muitos repetidores adicionais (Continente + Madeira + Açores) com base em fonte portuguesa consolidada.
- Mantida a compatibilidade do VX-8: sem modos `DV` e sem `NFM`.
- Mantidos PMR446 (1–16) e CB27 (1–40) por canal para escuta.

## Conteúdo do CSV
- Repetidores analógicos VHF/UHF de radioamador com `shift` e `CTCSS`.
- Canais simplex nacionais, ISS, aeronáutica, marítimo e AIS.
- Canais de escuta PMR446 e CB27 por canal.

## Fontes consultadas (2026-04-27)
- Macanudos QRG (PDF): https://macanudos.org/app/mediateca/Frequencias/QRG-Frequencias.pdf
- Radioamador.info (bandas/repetidores): https://www.radioamador.info/bands/ e https://www.radioamador.info/repetidores/
- ANACOM (QNAF e enquadramento): https://www.anacom.pt/render.jsp?categoryId=348130
- Radioamador.pt (referência complementar): https://radioamador.pt/

## Importar no CHIRP
1. Ligue o cabo USB MAXTON RPC--Y8R-U ao VX-8.
2. No CHIRP: **Radio > Download From Radio** (backup da configuração atual).
3. **File > Import** e escolha `vx8_portugal_chirp.csv`.
4. Ajuste nomes/ordem por bancos (se quiser) e faça **Radio > Upload To Radio**.

## Nota importante
- A operação real dos repetidores muda com frequência (QRT/QRV, tom, offset, links). Valide localmente antes de transmitir.
- Em Portugal, transmissão só com licença de radioamador válida.
- Entradas CB/PMR/aeronáutica/marítima foram configuradas para escuta (`Duplex=off`, `Skip=S`).
