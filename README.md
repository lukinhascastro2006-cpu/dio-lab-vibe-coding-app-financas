# Prompt final utilizado na IA

# PRD - Organizador Financeiro Conversacional

## Visão do Produto

Criar um aplicativo de finanças pessoais baseado em conversação, onde o usuário registra despesas, receitas e metas financeiras utilizando linguagem natural.

O sistema atua como um Agente Financeiro Inteligente, interpretando mensagens, organizando transações automaticamente e oferecendo orientações personalizadas para melhorar a saúde financeira do usuário.

---

## Objetivo

Permitir que pessoas sem conhecimento financeiro ou experiência com planilhas consigam controlar seu dinheiro de forma simples, intuitiva e sustentável através de uma experiência conversacional.

---

## Problema

Grande parte dos aplicativos financeiros exige:

- Cadastro manual de transações
- Configurações complexas
- Conhecimento prévio de categorias financeiras
- Disciplina constante para alimentar dados

Como consequência, muitos usuários abandonam o controle financeiro poucos dias após iniciar.

O produto busca reduzir essa fricção utilizando uma interface natural baseada em conversa.

---

## Público-Alvo

### Primário

Pessoas entre 18 e 45 anos que:

- Desejam organizar finanças pessoais
- Nunca utilizaram aplicativos financeiros de forma consistente
- Têm dificuldade em manter planilhas atualizadas
- Preferem experiências simples e guiadas

### Secundário

Usuários que já utilizam aplicativos financeiros, mas procuram uma experiência mais automatizada e personalizada.

---

## Proposta de Valor

"Controle suas finanças conversando como se estivesse falando com um consultor financeiro pessoal."

O usuário não precisa aprender categorias, preencher formulários ou interpretar relatórios complexos.

---

## Funcionalidades do MVP

### 1. Registro de Transações via Chat

Exemplos:

Usuário:
"Gastei R$ 45 no Uber hoje."

Sistema:
"Entendi. Registrei um gasto de R$ 45 na categoria Transporte."

Usuário:
"Recebi meu salário de R$ 5.000."

Sistema:
"Receita registrada em Salário."

Requisitos:

- Interpretar valores monetários
- Detectar receitas e despesas
- Identificar datas
- Extrair descrição da transação

---

### 2. Classificação Automática

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Lazer
- Educação
- Assinaturas
- Salário
- Outras Receitas

O usuário poderá corrigir a classificação quando necessário.

---

### 3. Metas Financeiras

Exemplos:

- Guardar R$ 10.000 para viagem
- Construir reserva de emergência
- Comprar um notebook

Funcionalidades:

- Criar meta
- Acompanhar progresso
- Exibir percentual concluído

---

### 4. Agente Financeiro

Responsável por:

- Identificar padrões de gasto
- Alertar excessos
- Sugerir economia
- Incentivar o cumprimento de metas

Exemplos:

"Seus gastos com delivery aumentaram 22% este mês."

"Se economizar R$ 150 por mês você atingirá sua meta dois meses antes."

---

### 5. Dashboard Simplificado

Indicadores:

- Saldo atual
- Receitas do mês
- Despesas do mês
- Evolução do saldo
- Gastos por categoria

---

## Principais Telas

### Tela 1 - Onboarding

Objetivo:

Entender o perfil inicial do usuário.

Coletar:

- Nome
- Objetivo financeiro principal
- Faixa de renda (opcional)

---

### Tela 2 - Chat Principal

Centro da experiência.

Permite:

- Registrar transações
- Consultar saldo
- Criar metas
- Solicitar dicas financeiras

---

### Tela 3 - Dashboard

Visualização resumida:

- Receitas
- Despesas
- Saldo
- Gráficos simples

---

### Tela 4 - Metas Financeiras

Exibir:

- Valor alvo
- Valor acumulado
- Percentual atingido
- Prazo estimado

---

### Tela 5 - Perfil e Configurações

Permite:

- Editar preferências
- Gerenciar categorias
- Exportar dados

---

## Fluxo Principal do Usuário

1. Realiza cadastro inicial.
2. Informa um gasto ou receita pelo chat.
3. O sistema interpreta a mensagem.
4. A transação é classificada automaticamente.
5. Os dados são atualizados no dashboard.
6. O usuário cria uma meta financeira.
7. O Agente Financeiro gera recomendações personalizadas.
8. O usuário acompanha sua evolução mensal.

---

## Critérios de Sucesso do MVP

### Engajamento

- 70% dos usuários registram ao menos uma transação no primeiro dia.

### Retenção

- 30% retornam após sete dias.

### Uso

- Média de 10 registros por usuário na primeira semana.

### Qualidade da IA

- 85% de classificação correta das transações.

---

## Requisitos Não Funcionais

- Interface mobile-first
- Tempo médio de resposta inferior a 3 segundos
- Linguagem simples e acolhedora
- Conformidade com LGPD
- Criptografia de dados sensíveis

---

## Fora de Escopo do MVP

As funcionalidades abaixo não fazem parte da primeira versão:

- Integração com Open Finance
- Conexão direta com bancos
- Importação automática de extratos
- Assistente por voz
- Previsões financeiras avançadas
- Planejamento tributário

---

## Evoluções Futuras

- Integração com Open Finance
- Leitura automática de extratos
- Assistente por voz
- Planejamento financeiro avançado
- Previsão de fluxo de caixa
- Recomendações avançadas com IA generativa

---

## Entregável Esperado da IA

Gerar:

1. Estrutura do aplicativo
2. Arquitetura do MVP
3. Design inicial das telas
4. Componentes da interface
5. Fluxos de navegação
6. Modelo de banco de dados
7. Estratégia de validação com usuários
8. Roadmap de evolução do produto

---

## Prompt de Contexto para Lovable

Crie um aplicativo mobile-first de finanças pessoais baseado em conversa.

O usuário deve ser capaz de registrar receitas, despesas e metas financeiras utilizando linguagem natural em português.

A principal experiência deve acontecer em uma tela de chat semelhante a um assistente virtual.

O sistema deve interpretar mensagens financeiras, classificar transações automaticamente, acompanhar metas e fornecer recomendações simples de educação financeira.

Priorize simplicidade, acessibilidade e experiência para usuários iniciantes.

Gere telas modernas, fluxo intuitivo, banco de dados sugerido, componentes reutilizáveis e arquitetura adequada para um MVP validável.
