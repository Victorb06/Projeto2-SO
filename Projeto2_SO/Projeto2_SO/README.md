# Projeto 2 — Uso de CPU em servidor dedicado de Left 4 Dead 2



## Ambiente de medição

* Jogo: Left 4 Dead 2, mapa `c1m1\_hotel`.
* Servidor: Left 4 Dead 2 Dedicated Server (`srcds.exe`).
* Computador: Intel Core i7-12700F, 12 núcleos físicos, 20 processadores lógicos, 16 GB RAM.
* Sistema: Windows 11 Pro, versão 10.0.26200, compilação 26200.
* Rede dos participantes: Radmin VPN.
* Ferramenta: Windows Performance Monitor (PerfMon).
* Contador: `Process(srcds)\\% Processor Time`.
* Intervalo: 1 segundo; três repetições de aproximadamente cinco minutos por condição.

## Pastas

* dados\_csv: 24 CSVs originais.
* graficos: gráfico final em PNG, PDF e SVG.
* relatorio: relatório final em PDF.
* configuracoes: configurações usadas para gerar os resultados dos testes no PerfMon
* comandos: comandos utilizados para rodar o server e conseguir configurar tudo.

## Principais médias

* 1 jogador: 3,38 parado; 4,75 em movimento.
* 2 jogadores: 5,35 parado; 7,29 em movimento.
* 3 jogadores: 6,05 parado; 7,74 em movimento.
* 4 jogadores: 5,98 parado; 8,18 em movimento.



## Reprodução

1. Use os CSVs originais em `dados\_csv/`.
2. Confira os valores e médias na tabela CSV.
3. Consulte o método no relatório para reproduzir as condições da partida.

