# Avaliação Coding Tank – Desafio "Marketplace Priority Sorter" (MPS)

---

## 1. Instruções gerais

1. O trabalho **não exige código**. A entrega consiste em:
    * **Canvas‑PDF** (até 2 páginas) utilizando o template fornecido.
    * **Apresentação** (slides e 15min de duração).
2. A apresentação ocorrerá no Dia 3, com 15min de exposição e 10min de perguntas. Se necessário, recursos de acessibilidade (legenda, contraste alto, etc) são obrigatórios.
3. O uso de IA generativa é permitido e incentivado, desde que citem como e quando a ferramenta foi utilizada e demonstrem compreensão da solução.

---

## 2. Cenário fictício: Marketplace Priority Sorter (MPS)

O *VelozMart*, grande empresa de logística e varejo da América Latina, lançou uma feature que mostra em tempo real uma lista de **pedidos** aguardando expedição. O objetivo é exibir os pedidos na **ordem ótima** para minimizar atrasos e custos logísticos.

### Elementos do problema

* Cada pedido possui:

    * *priorityScore* (0–100) calculado por IA com base em distância, SLA, valor do item e reputação do vendedor.
    * *dispatchWindow* (minutos restantes até prazo expirar).
    * *sizeCategory* (P, M, G) que impacta espaço na doca de embalagem.
* O time de logística pediu um **protótipo conceitual** que responda:

    1. Como **ordenar** pedidos considerando múltiplos critérios?
    2. Como re‑**enfileirar** pedidos à medida que novos chegam ou prazos mudam?
    3. Quais métricas comprovam que a estratégia é melhor que uma ordenação simples por tempo?

> Existem diversas estratégias válidas: peso composto (priorityScore × 1/dispatchWindow), duas filas (urgentes vs. normais), heap multi‑chave, algoritmo de aproximação de scheduling, etc. A escolha é livre, desde que fundamentada.

### Requisitos mínimos da solução

1. **Descrição textual do algoritmo/estrutura** escolhida (pseudocódigo opcional).
2. **Diagrama** (heap, fluxo, ou gráfico de Gantt) explicando o processo de inclusão, remoção e re‑priorização.
3. **Justificativa** dos critérios de ordenação e efeitos sobre métricas logísticas (p.ex. atraso médio, throughput/hora).
4. **Mapa de trade‑offs** (simplicidade × desempenho × manutenibilidade).

Itens bônus (não obrigatórios): análise Big O, comparação entre duas abordagens, proposta de teste A/B ou simulação, discussão de acessibilidade na UI.

---

## 3. Template de entrega (Canvas‑PDF)

<table>
  <tr>
    <th>Seção</th>
    <th>Guia de conteúdo</th>
  </tr>
  <tr>
    <td><strong>Problema</strong></td>
    <td>Situação real resumida em 3–4 linhas; dados de contexto.</td>
  </tr>
  <tr>
    <td><strong>Algoritmo / Estrutura</strong></td>
    <td>Nome, motivação e breve pseudocódigo.</td>
  </tr>
  <tr>
    <td><strong>Diagrama</strong></td>
    <td>Imagem autoexplicativa; use legenda e alto contraste.</td>
  </tr>
  <tr>
    <td><strong>Trade‑offs</strong></td>
    <td>3 prós & 3 contras; justificativa de escolha.</td>
  </tr>
  <tr>
    <td><strong>Próximos passos</strong></td>
    <td>Ideias futuras (ex.: incorporar aprendizagem online).</td>
  </tr>
</table>

---

## 4. Entrega

A entrega deverá ser realizada até as 22:00h do dia 03/03/2026 através do e-mail:

rodolfo.lima.ferreira11@gmail.com

**OBS:** Não é necessário mais de uma entrega por grupo.
