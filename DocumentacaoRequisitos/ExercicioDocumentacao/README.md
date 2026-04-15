# Sistema de Gerenciamneto de Reservsa de Hotel (Jan/2026)

## 1. Introdução
Este documento especifica os requisito original para o sistema de reservas do hotel, servindo como base para o desenvolvimento inicial.

## 2. Visão Geral
O sistema deve garantir que os usuários possam realizar suas reservas de quartos com antecedência mínima de até 24 horas e máxima de 6 meses.

## 3. Requisitos Específicos

### 3.1 Requisitos Funcionais

#### RF-010: Criação de Tarefas
**Descrição**: O sistema deve permitir que usuários realizem reservas de quartos com antecedência mínima de 24 horas e máxima de 6 meses.

**Prioridade**: Alta  
**Versão**: 1.0  
**Data**: Jan/2026

**Critérios de Aceitação**:
- [ ] O calendário só deve habilitar datas a partir de 24h do horário atual.
- [ ] O calendário deve bloquear datas além de 6 meses no futuro.
- [ ] Exibir mensagem de erro caso o usuário tente digitar uma data fora do intervalo.

**Dependências**: Nenhuma


## 4. Controle de Versão

### 4.1 Histórico de Versões

### Histórico de Alterações

|ID do Requisito|Descrição|Versão|Data|Autor|Modificação|Impacto|
|---------------|---------|------|----|-----|-----------|-------|
|RF-010|O sistema permite que usuários realizem reservas de quartos com antecedência mínima de 24 horas e máxima de 6 meses.|v1.0|Jan/2026|Analista Luna|Versão Inicial|Médio. Definição dos prazos padrão (24h a 6 meses)|

## 5. Conclusão
A Versão 1.0 define a regra básica de 24h a 6 meses para garantir a organização inicial do hotel.