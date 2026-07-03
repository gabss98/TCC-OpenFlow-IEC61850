# MAPA DO PROBLEMA

## 1. Contexto

Subestações digitais baseadas na IEC 61850 dependem de uma comunicação de baixa latência e alta confiabilidade entre IEDs.

Mensagens GOOSE possuem requisitos rigorosos de tempo e disponibilidade.

Uma falha em enlaces de comunicação pode comprometer a entrega dessas mensagens.

---

## 2. Problema Geral

Como manter a comunicação crítica entre IEDs mesmo diante de falhas na infraestrutura de rede?

---

## 3. Problema Específico

Como o mecanismo OpenFlow Fast Failover se comporta na recuperação de falhas durante a transmissão de mensagens GOOSE?

---

## 4. Variáveis que podem ser avaliadas

### Tempo

- Tempo de recuperação
- Latência fim a fim
- Tempo de convergência

### Qualidade

- Jitter
- Packet Loss
- Disponibilidade

### Rede

- Número de switches
- Número de IEDs
- Quantidade de fluxos
- Carga GOOSE

### Falhas

- Rompimento de fibra
- Falha simples
- Falha dupla
- Falhas consecutivas
- Falhas em cascata

### Topologias

- Linear
- Anel
- Estrela
- Malha

### Implementação

- Mininet
- Open vSwitch
- Ryu


## Hipóteses candidatas

H1

O Fast Failover mantém os requisitos temporais da IEC 61850 mesmo sob congestionamento?

Status:
⬜ Ainda não verificado

---

H2

O Fast Failover mantém desempenho adequado durante múltiplas falhas consecutivas?

Status:
⬜ Ainda não verificado

---

H3

A topologia influencia significativamente o tempo de recuperação?

Status:
⬜ Ainda não verificado

---

H4

As métricas normalmente utilizadas pela literatura são suficientes para caracterizar o desempenho?

Status:
⬜ Ainda não verificado
