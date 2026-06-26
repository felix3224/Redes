```markdown
# 🧩 Repositório de Estudos em Redes de Computadores

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📖 Sobre o Repositório

Este repositório documenta minha jornada prática de aprendizado em **Redes de Computadores II**. Aqui, consolido atividades, projetos e simulações realizadas no **Cisco Packet Tracer**, abrangendo desde a configuração de protocolos de roteamento (RIP, OSPF, BGP) até a compreensão dos fundamentos das camadas **IP/TCP e OSI**.

O objetivo é duplo: servir como material de revisão para estudos e provas, e, principalmente, demonstrar a recrutadores minhas habilidades práticas em projetos de infraestrutura de rede.

## 🎯 Objetivos do Projeto

*   **Consolidar o Aprendizado:** Aplicar na prática os conceitos teóricos de redes, indo além da sala de aula.
*   **Resolver Problemas Reais:** Criar topologias que simulam cenários do mundo real, como a segmentação de uma empresa ou a interconexão de filiais.
*   **Desenvolver Documentação:** Praticar a criação de documentação clara e organizada, uma soft skill crucial para qualquer profissional de TI.
*   **Construir um Portfólio:** Apresentar de forma tangível minhas competências técnicas para futuros empregadores.

## 🛠️ Tecnologias e Ferramentas

*   **Simulador:** Cisco Packet Tracer
*   **Protocolos de Roteamento:**
    *   **RIP (v1 e v2):** Protocolo de vetor de distância para redes menores.
    *   **OSPF:** Protocolo de estado de enlace para redes maiores e mais complexas.
    *   **BGP:** Protocolo de roteamento entre sistemas autônomos (interdomínio).
*   **Conceitos Fundamentais:**
    *   Modelo OSI e pilha TCP/IP.
    *   Endereçamento IP e Sub-redes (VLSM).
    *   VLANs e Trunking.
    *   Tabelas de Roteamento e Rota Padrão.
*   **Ferramentas de Análise:** (Opcional) Wireshark para captura e análise de pacotes.

## 📂 Estrutura do Repositório

A organização do repositório reflete a progressão dos meus estudos:

```
Redes/
├── Topologias-Cisco/          # Arquivos .pkt do Packet Tracer
│   ├── RIP/                   # Configurações e cenários com RIP
│   ├── OSPF/                  # Configurações e cenários com OSPF
│   └── BGP/                   # Configurações e cenários com BGP
├── Configuracoes/             # Arquivos de configuração (CLI) em .txt
│   ├── roteadores/            # Configurações dos roteadores
│   └── switches/              # Configurações dos switches
├── Diagramas/                 # Imagens e diagramas das topologias
└── Anotacoes/                 # Resumos teóricos e anotações de estudo
```

## ⚙️ Como Utilizar Este Repositório

1.  **Pré-requisito:** Ter o **Cisco Packet Tracer** instalado em sua máquina.
2.  **Clonar o Repositório:**
    ```bash
    git clone https://github.com/felix3224/Redes.git
    ```
3.  **Abrir os Projetos:** Navegue até a pasta `Topologias-Cisco/` e abra o arquivo `.pkt` desejado no Packet Tracer para visualizar e interagir com a topologia.
4.  **Explorar as Configurações:** Consulte os arquivos `.txt` na pasta `Configuracoes/` para ver os comandos CLI utilizados.

## 💡 Principais Aprendizados

*   **Compreensão Prática dos Protocolos:** A diferença entre um protocolo de vetor de distância (RIP) e um de estado de enlace (OSPF) ficou clara ao ver como cada um calcula e propaga as rotas na prática.
*   **Resolução de Problemas:** Aprendi a diagnosticar e corrigir problemas comuns, como loops de roteamento, inconsistências na tabela de roteamento e falhas de adjacência OSPF.
*   **Importância do Planejamento:** Projetar uma topologia de rede eficiente exige um planejamento cuidadoso de endereçamento IP e da hierarquia de roteamento, algo que os laboratórios me ajudaram a internalizar.
*   **Documentação como Ferramenta:** Documentar cada passo e decisão não só ajuda na revisão, mas também me prepara para a rotina profissional, onde a documentação é fundamental.

## 🚀 Próximos Passos

*   **Integrar Serviços:** Adicionar configurações de serviços como **DHCP**, **DNS** e **NAT** às topologias existentes.
*   **Simulações com Wireshark:** Realizar capturas de tráfego para analisar o funcionamento dos protocolos em detalhe.
*   **Cenários de Troubleshooting:** Criar laboratórios com erros intencionais para praticar o diagnóstico e a correção de problemas.
*   **Expandir para Segurança:** Implementar **ACLs** (Access Control Lists) para controlar o tráfego e aumentar a segurança das redes simuladas.

## 📫 Contato

*   **Nome:** Davi Witalo Félix da Silva
*   **LinkedIn:** https://www.linkedin.com/in/witalofelix/
*   **E-mail:** davi.witalo@gmail.com

---

**Nota:** Este repositório está em constante evolução, refletindo meu progresso contínuo nos estudos de redes.
```
