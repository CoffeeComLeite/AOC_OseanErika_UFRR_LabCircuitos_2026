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
  - relatorio_tecnico.pdf
- **Parte I:**
  - 
- **Parte II:**
  - parte2_cabeada.circ: Circuito da versão cabeada
  - parte2_microprogramada: Circuito da versão microprogramada
  - tabela_tempo.xlsx: Tabela de tempo das instruções da versão cabeada com cálculo de CPI
  - microcodigo.txt: Conteúdo da ROM microprogramada da versão microprogramada
  - **Evidências:**
    - print_BEQsetup.png: Preparativo ao teste do BEQ, com foco no conteúdo da ROM
    - print_BEQsetup1.png: Preparativo ao teste do BEQ, com foco no conteúdo dos registradores
    - print_tipoRsetup.png: Preparativo do teste tipo-R,com foco no conteúdo dos registradores
    - testesUCcabeada
      - UCcabeadaS0.png: Apresentando UC cabeada com estado inicial
      - UCcabeadaS0flags.png: Apresentando sinais de controle do estado inicial
      - UCcabeadaS1.png: Apresentando UC cabeada com estado S1
      - UCcabeadaS1flags.png: Apresentando sinais de controle do estado S1
      - print_BEQfalhacabeada0.png: Teste de falha do BEQ cabeado, foco nos registradores A e B carregados
      - print_BEQfalhacabeada1.png: Teste de falha do BEQ cabeado, foco no ULAOut produzido
      - print_BEQfalhacabeada2.png: Teste de falha do BEQ cabeado, foco na falha do desvio em PC
      - print_BEQsucessocabeada0.png: Teste de sucesso do BEQ cabeado, foco no ULAOut produzido
      - print_BEQsucessocabeada1.png: Teste de sucesso do BEQ cabeado, foco no desvio em PC
      - print_fetchcabeada0.png: Teste de busca cabeada, primeiro ciclo
      - print_fetchcabeada1.png: Teste de busca cabeada, segundo ciclo
      - print_fetchcabeada2.png: Teste de busca cabeada, terceiro ciclo
      - print_tipoRcabeada0.png: Teste tipo-R cabeado, foco no ULAOut produzido
      - print_tipoRcabeada1.png: Teste tipo-R cabeado, foco no registrador de destino escrito
      - teste_UCcabeada.mp4: Vídeo do teste da unidade de controle cabeada
      - teste_beqcabeada.mp4: Vídeo do teste BEQ cabeado
      - teste_fetchcabeada.mp4: Vídeo do teste de busca cabeada
      - teste_tipoRcabeada.mp4: Vídeo do teste tipo-R cabeado
    - testesUCmicroprogramada
      - UCmicropcS0.png: Apresentando UC microprogramada com estado inicial
      - UCmicropcS1.png: Apresentando UC microprogramada com estado S1
      - print_beqfalhamicropc0.png: Teste de falha do BEQ microprogramado, foco nos registradores A e B carregados
      - print_beqfalhamicropc1.png: Teste de falha do BEQ microprogramado, foco no ULAOut produzido
      - print_beqfalhamicropc2.png: Teste de falha do BEQ microprogramado, foco na falha do desvio em PC
      - print_beqsucessomicropc0.png: Teste de sucesso do BEQ microprogramado, foco no ULAOut produzido
      - print_beqsucessomicropc1.png: Teste de sucesso do BEQ microprogramado, foco no desvio em PC
      - print_fetchmicropc0.png: Teste de busca microprogramada, primeiro ciclo
      - print_fetchmicropc1.png: Teste de busca microprogramada, segundo ciclo
      - print_fetchmicropc2.png: Teste de busca microprogramada, terceiro ciclo
      - print_tipoRmicropc0.png: Teste tipo-R microprogramado, foco no ULAOut produzido
      - print_tipoRmicropc1.png: Teste tipo-R microrpogramado, foco no registrador de destino escrito
      - teste_UCmicroprogramada.mp4: Vídeo do teste da unidade de controle microprogramada
      - teste_beqmicropc.mp4: Vídeo do teste BEQ microprogramado
      - teste_fetchmicropc.mp4: Vídeo do teste de busca microprogramada
      - teste_tipormicropc.mp4: Vídeo do teste tipo-R micrprogramado

## Subcircuitos Instanciados
- **Parte I:**
  - 
- **Parte II:**
  - main
  - ULA
  - Banco de registradores
  - IR
  - UC_cabeada
  - UC_microprogramada
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
