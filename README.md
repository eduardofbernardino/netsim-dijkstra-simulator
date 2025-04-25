# netsim-dijkstra-simulator
Simulador de rede OSPF com Cisco Packet Tracer. Observa convergência de rotas em tempo real usando o algoritmo de Dijkstra.

# NETSIM - Simulador OSPF com Cisco Packet Tracer

# 📌 Sobre o Projeto

O **NETSIM** é um projeto acadêmico voltado à simulação de redes de computadores utilizando o protocolo **OSPF (Open Shortest Path First)**, configurado em roteadores Cisco através da linguagem CLI do IOS. A simulação é feita no **Cisco Packet Tracer**, com foco na análise da **convergência de rotas** diante de falhas de links ou nós, utilizando o **algoritmo de Dijkstra (SPF)**.

# 🎯 Objetivo

Demonstrar, de forma visual e técnica, o comportamento dinâmico de uma rede configurada com OSPF, incluindo:
- Criação da topologia.
- Simulação de falhas.
- Observação da recalculação automática de rotas.
- Coleta de tabelas de roteamento antes e depois das falhas.

# 🔧 Tecnologias Utilizadas

- **Cisco Packet Tracer 8.2+**  
- **Cisco IOS CLI** (Command Line Interface)  
- **Protocolo OSPF v2**  
- **Algoritmo de Dijkstra (SPF)**

# 👥 Equipe

- **Eduardo Ferreira Bernardino** – Gerente de Projeto  
- **Paulo Roberto Alves Genuíno** – Configurador de Rede (Backend)  
- **Thiago Ventura Silva** – Analista de Visualização (Frontend)  

# 📁 Estrutura do Projeto

```bash
netsim_ospf_project/
│── topologia/
│   ├── redes_visuais/
│   │   └── topologia_inicial.png
│   │   └── topologia_com_falha.png
│   └── packet_tracer/
│       └── netsim_final.pkt
│
│── configuracoes/
│   ├── roteador_A.txt
│   ├── roteador_B.txt
│   └── roteador_C.txt
│
│── resultados/
│   ├── tabelas_roteamento_iniciais.txt
│   ├── tabelas_roteamento_pos_falha.txt
│   └── comparativo_convergencia.txt
│
│── apresentacao/
│   ├── slides_apresentacao.pdf
│   └── graficos_convergencia.png
│
└── README.md
