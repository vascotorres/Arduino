# Yaesu VX-8 — Memórias Portugal (CHIRP CSV)

Ficheiro: `vx8_portugal_chirp.csv`

## O que foi reforçado nesta versão
- Mais repetidores FM úteis no **Norte** (ex.: Serra de Arga, Guimarães/Penha, Oliveira de Azeméis).
- Inclusão explícita da **Serra da Estrela** (VHF/UHF e D-STAR).
- Tabela **PMR446 completa por canal (1–16)**.
- Tabela **CB27 completa por canal (1–40)** para escuta.

## Conteúdo do CSV
- Repetidores de radioamador (2 m / 70 cm) com `shift` e `CTCSS` quando aplicável.
- Canais simplex de chamada (145.500 / 433.500) e utilidade (ISS).
- Canais de escuta: aeronáutica, marítimo, AIS, PMR446 e CB27.

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
- O estado real dos repetidores pode variar (QRT, tom, offset, proprietário). **Valide localmente antes de transmitir**.
- Em Portugal, transmissão só com licença de radioamador válida.
- Entradas CB/PMR/aeronáutica/marítima foram colocadas como **escuta** (`Duplex=off`, `Skip=S`).
