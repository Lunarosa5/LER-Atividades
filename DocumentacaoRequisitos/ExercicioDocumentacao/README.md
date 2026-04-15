# Sistema de Gerenciamento de Reservas de Hotel (Fev/2026)

## 1. Introdução
Este documento atualiza o requisito original para incluir condições especiais para clientes VIP, conforme solicitado pelo departamento de vendas.

## 2. Visão Geral
O sistema mantém as regras originais, mas agora expande o limite de reserva para usuários com status VIP.

## 3. Requisitos Específicos

### 3.1 Requisitos Funcionais

#### RF-010: Regras de Antecedência (VIP)
**Descrição**: O sistema deve permitir reservas com antecedência mínima de 24 horas e máxima de 6 meses. Clientes VIP têm o benefício de reservar com até 1 ano de antecedência.

**Prioridade**: Alta  
**Versão**: 2.0  
**Data**: Fev/2026

**Critérios de Aceitação**:
- [ ] Validar se o usuário possui status "VIP" no perfil.
- [ ] Liberar calendário de 1 ano apenas para usuários autenticados como VIP.
- [ ] Manter bloqueio de 6 meses para usuários comuns.

**Dependências**: Cadastro de Usuários (VIP).


## 4. Controle de Versão

### 4.1 Histórico de Versões

### Histórico de Alterações

|ID do Requisito|Descrição|Versão|Data|Autor|Modificação|Impacto|
|---------------|---------|------|----|-----|-----------|-------|
|RF-010|Reservas de 24h a 6 meses; Clientes VIP podem reservar até 1 ano|v2.0|Fev/2026|Analista Luna|Clientes VIP podem reservar até 1 ano antes|Médio. Necessário identificar o tipo de cliente|

## 5. Conclusão
A Versão 2.0 adapta o sistema para estratégias comerciais, permitindo maior flexibilidade de planejamento para clientes VIP.