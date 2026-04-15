# Sistema de Gerenciamento de Reservas de Hotel (Mar/2026)

## 1. Introdução
Este documento atualiza o requisito RF-010 para incluir a nova política de reservas de última hora com aplicação de taxa adicional.

## 2. Visão Geral
O sistema passa a permitir reservas imediatas (menos de 2h de antecedência), mas com cobrança para estes casos específicos.

## 3. Requisitos Específicos

### 3.1 Requisitos Funcionais

#### RF-010: Regras de Antecedência (VIP)
**Descrição**: Além das regras anteriores, agora são permitidas reservas com menos de 2 horas de antecedência, por meio do pagamento de uma taxa adicional de 15%.

**Prioridade**: Alta  
**Versão**: 2.0  
**Data**: Mar/2026

**Critérios de Aceitação**:
- [ ] Liberar reservas com antecedência inferior a 2 horas.
- [ ] Aplicar acréscimo de 15% no valor total para essas reservas.
- [ ] Exibir o valor da taxa separadamente no total da compra.

**Dependências**: Modo de pagamento.


## 4. Controle de Versão

### 4.1 Histórico de Versões

### Histórico de Alterações

|ID do Requisito|Descrição|Versão|Data|Autor|Modificação|Impacto|
|---------------|---------|------|----|-----|-----------|-------|
|RF-010|Permite reservas com menos de 2h com taxa extra de 15%.|v3.0|Mar/2026|Analista Luna|Nova política de última hora.|Alto. Altera o cálculo do valor total|

## Análise de Impacto
- Requisitos Afetados: Pagamentos (Cálculo).
- Stakeholders: Gerente de Vendas e Financeiro.
- Esforço: Alto (exige testes financeiros).

## 5. Conclusão
A Versão 3.0 altera o sistema para atender demandas urgentes, transformando uma restrição em uma nova oportunidade de ganho.