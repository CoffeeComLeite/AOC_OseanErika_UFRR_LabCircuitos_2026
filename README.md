# AOC_OseanErika_UFRR_LabCircuitos_2026
# Projeto Integrador: Subsistema de Memória e Unidade de Controle

- **Disciplina:** Arquitetura e Organização de Computadores
- **Semestre:** 2026.2
- **Instituição:** Universidade Federal de Roraima (UFRR)
- **Integrantes:** 
  - Osean Pinto Cordeiro do Nascimento (2025015571)
  - Erika Andreina Mejías Palma (2025015123)

## Ferramentas Utilizadas
- **Logisim-Evolution** (Versão 5.0.0)
- **Microsoft Excel**
- **Microsoft Word**
- **GitHub**

## Lista de Arquivos Entregues
- **Universal:**
  - relatorio_tecnico.pdf: Relatório exigido com o conteúdo produzido.
- **Parte I:**
  - parte1_cache.circ
  - parte1_memoria.circ
  - parte1_planilha.xlsx
  - **Evidências:**
    - T-01CS_IO.png
    - T-01CS_RAM.png
    - T-01CS_REG.png
    - T-01CS_ROM.png
    - T-02_ERRO_PARIDADE (1).png
    - T-02_ERRO_PARIDADE (2).png
    - T-02_PARIDADE_INATIVA.png
    - T-03Passo1-Reset.png
    - T-03Passo1-Reset.png
    - T-03Passo2-Ler_0x00 (2).png
    - T-03Passo2-Ler_0x00.png
    - T-04Passo1-Ler_0x01.png
    - T-04Passo2_Clock.png
    - T-05Passo1-Ler_0x20.png
    - T-05Passo2_Clock.png
    - evidencia.txt
    - memoria.png
    - parte1_memoria.png
- **Parte II:**
  - parte2_cabeada.circ: Circuito da versão cabeada
  - parte2_microprogramada: Circuito da versão microprogramada
  - tabela_tempo.xlsx: Tabela de tempo das instruções da versão cabeada com cálculo de CPI
  - microcodigo.txt: Conteúdo da ROM microprogramada da versão microprogramada
  - **Evidências:**
    - print_BEQsetup.png: Preparativo ao teste do BEQ, com foco no conteúdo da ROM
    - print_BEQsetup1.png: Preparativo ao teste do BEQ, com foco no conteúdo dos registradores
    - print_tipoRsetup.png: Preparativo do teste tipo-R,com foco no conteúdo dos registradores
    - T09_testes_tabela_evidencia.xlsx: Tabela com entradas e saídas de cada teste, mostrando equivalência das versões
    - testesUCcabeada
      - T06_UCcabeadaS0.png: Apresentando UC cabeada com estado inicial
      - T06_UCcabeadaS0flags.png: Apresentando sinais de controle do estado inicial
      - T06_UCcabeadaS1.png: Apresentando UC cabeada com estado S1
      - T06_UCcabeadaS1flags.png: Apresentando sinais de controle do estado S1
      - T08_print_BEQfalhacabeada0.png: Teste de falha do BEQ cabeado, foco nos registradores A e B carregados
      - T08_print_BEQfalhacabeada1.png: Teste de falha do BEQ cabeado, foco no ULAOut produzido
      - T08_print_BEQfalhacabeada2.png: Teste de falha do BEQ cabeado, foco na falha do desvio em PC
      - T08_print_BEQsucessocabeada0.png: Teste de sucesso do BEQ cabeado, foco no ULAOut produzido
      - T08_print_BEQsucessocabeada1.png: Teste de sucesso do BEQ cabeado, foco no desvio em PC
      - T06_print_fetchcabeada0.png: Teste de busca cabeada, primeiro ciclo
      - T06_print_fetchcabeada1.png: Teste de busca cabeada, segundo ciclo
      - T06_print_fetchcabeada2.png: Teste de busca cabeada, terceiro ciclo
      - T07_print_tipoRcabeada0.png: Teste tipo-R cabeado, foco no ULAOut produzido
      - T07_print_tipoRcabeada1.png: Teste tipo-R cabeado, foco no registrador de destino escrito
      - T06_teste_UCcabeada.mp4: Vídeo do teste da unidade de controle cabeada
      - T08_teste_beqcabeada.mp4: Vídeo do teste BEQ cabeado
      - T06_teste_fetchcabeada.mp4: Vídeo do teste de busca cabeada
      - T07_teste_tipoRcabeada.mp4: Vídeo do teste tipo-R cabeado
    - testesUCmicroprogramada
      - T06_UCmicropcS0.png: Apresentando UC microprogramada com estado inicial
      - T06_UCmicropcS1.png: Apresentando UC microprogramada com estado S1
      - T08_print_beqfalhamicropc0.png: Teste de falha do BEQ microprogramado, foco nos registradores A e B carregados
      - T08_print_beqfalhamicropc1.png: Teste de falha do BEQ microprogramado, foco no ULAOut produzido
      - T08_print_beqfalhamicropc2.png: Teste de falha do BEQ microprogramado, foco na falha do desvio em PC
      - T08_print_beqsucessomicropc0.png: Teste de sucesso do BEQ microprogramado, foco no ULAOut produzido
      - T08_print_beqsucessomicropc1.png: Teste de sucesso do BEQ microprogramado, foco no desvio em PC
      - T06_print_fetchmicropc0.png: Teste de busca microprogramada, primeiro ciclo
      - T06_print_fetchmicropc1.png: Teste de busca microprogramada, segundo ciclo
      - T06_print_fetchmicropc2.png: Teste de busca microprogramada, terceiro ciclo
      - T07_print_tipoRmicropc0.png: Teste tipo-R microprogramado, foco no ULAOut produzido
      - T07_print_tipoRmicropc1.png: Teste tipo-R microrpogramado, foco no registrador de destino escrito
      - T06_teste_UCmicroprogramada.mp4: Vídeo do teste da unidade de controle microprogramada
      - T08_teste_beqmicropc.mp4: Vídeo do teste BEQ microprogramado
      - T06_teste_fetchmicropc.mp4: Vídeo do teste de busca microprogramada
      - T07_teste_tipoRmicropc.mp4: Vídeo do teste tipo-R micrprogramado

## Subcircuitos Instanciados
- **Parte I:**
  - 
- **Parte II:**
  - Flip flop tipo D: parte2_cabeada.circ, em UC_cabeada
  - MUX de 4 entradas: parte2_cabeada.circ e parte2_microprogramada.circ, em ALU e UC_microprogramada
  - Somador de 8 bits: parte2_cabeada.circ e parte2_microprogramada.circ, em ALU e UC_microprogramada
  - ROM de 8 bits: parte2_cabeada.circ e parte2_microprogramada.circ, em main e UC_microprogramada
  - Detector da sequência 101: parte2_cabeada.circ,em UC_cabeada
  - ULA de 8 bits: parte2_cabeada.circ e parte2_microprogramada.circ, em ALU
  - Banco de registradores: parte2_cabeada.circ e parte2_microprogramada.circ, em Banco_registradores
  - Extensor de sinal 4 bits para 8 bits: parte2_cabeada.circ e parte2_microprogramada.circ, em main
  - Máquina de estados: parte2_cabeada.circ, em UC_cabeada
  - Contador síncrono: parte2_cabeada.circ, em UC_cabeada
  - Otimização por mapas de Karnaugh: parte2_cabeada.circ, em UC_cabeada
  - Decodificador de 7 segmentos: parte2_cabeada.circ, em UC_cabeada
## Declaração de Uso de IA
Esse arquivo README foi modelado com Gemini 3.5 Lite com raciocínio estendido.
Além disso, a IA foi consultada para:
  - Revisar conceitos da disciplina;
  - Confirmar a validade dos entregáveis;
  - Auxiliar no debugging do Logisim;
  - Automatização de tarefas no cerne deste README. (Exemplo: Transcrever e listar o nome de todos os arquivos entregues para inclusão)

## Divisão do Trabalho
- Parte I - Subsistema de memória: Erika Andreina Mejías Palma
- Parte II - Unidade de controle: Osean Pinto Cordeiro do Nascimento
