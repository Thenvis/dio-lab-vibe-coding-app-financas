# 💸 App de Organização de Finanças Pessoais do Andrew com Vibe Coding - FinanChat

- PRD final:
```markdown
# PRD - FinanChat

## Visão do Produto

O FinanChat é um aplicativo de finanças pessoais baseado em conversação, permitindo que usuários registrem gastos, receitas e metas financeiras utilizando linguagem natural.

Ao invés de preencher formulários ou editar planilhas, o usuário conversa com um assistente financeiro inteligente que interpreta suas mensagens, organiza automaticamente as informações e gera recomendações práticas para melhorar sua saúde financeira.

O produto será desenvolvido com princípios de Design Universal, priorizando simplicidade, acessibilidade e inclusão, para que qualquer pessoa possa organizar suas finanças por meio de conversas naturais, independentemente do nível de conhecimento financeiro ou experiência tecnológica.

---

## Problema

Grande parte das pessoas abandona aplicativos de controle financeiro porque:

- Exigem cadastro manual de transações.
- Possuem interfaces complexas.
- Demandam conhecimento financeiro prévio.
- Não oferecem orientação personalizada.

Como consequência, os usuários perdem visibilidade sobre seus gastos e encontram dificuldades para alcançar metas financeiras.

---

## Objetivo do Produto

Tornar o controle financeiro pessoal simples, acessível e engajador por meio de uma interface conversacional baseada em linguagem natural.

---

## Público-Alvo

### Primário

Pessoas iniciantes em educação financeira que desejam organizar melhor seu dinheiro sem utilizar planilhas ou sistemas complexos.

### Secundário

Usuários que já tentaram usar aplicativos financeiros tradicionais, mas abandonaram o hábito por considerá-los trabalhosos.

---

## Proposta de Valor

"O usuário conversa naturalmente sobre suas finanças e o sistema faz o trabalho de organizar, analisar e sugerir melhorias."

Exemplos:

- "Gastei R$ 45 com almoço."
- "Recebi meu salário de R$ 4.500."
- "Quero economizar R$ 3.000 para viajar."

---

## Funcionalidades do MVP

### 1. Registro Conversacional de Transações

O usuário informa receitas e despesas por mensagem.

Exemplos:

- "Paguei R$ 120 no mercado."
- "Gastei R$ 50 em transporte."
- "Recebi R$ 2.000 de um freela."

Resultado esperado:

O sistema identifica automaticamente:

- Valor
- Tipo (receita ou despesa)
- Categoria
- Data

### 2. Classificação Automática

O sistema categoriza transações sem intervenção do usuário.

Categorias iniciais:

- Alimentação
- Transporte
- Moradia
- Saúde
- Lazer
- Educação
- Salário
- Investimentos
- Outros

### 3. Metas Financeiras

Usuários podem criar objetivos financeiros.

Exemplos:

- Comprar um notebook.
- Formar reserva de emergência.
- Fazer uma viagem.

O sistema acompanha:

- Valor-alvo
- Valor acumulado
- Percentual de progresso
- Prazo estimado

### 4. Agente Financeiro

Assistente virtual que analisa comportamentos financeiros e oferece recomendações.

Exemplos:

- "Você gastou 20% mais com alimentação este mês."
- "Se reduzir R$ 10 por dia em delivery, poderá economizar R$ 300 por mês."
- "Sua meta de viagem está 65% concluída."

### 5. Relatórios Simplificados

Painel com visualização simples das finanças.

Indicadores:

- Gastos do mês
- Receitas do mês
- Saldo atual
- Categorias com maiores despesas
- Evolução mensal

---

## Fluxo Principal do Usuário

### Primeiro Acesso

1. Criar conta.
2. Informar renda mensal aproximada.
3. Definir uma primeira meta financeira.
4. Iniciar conversa com o Agente Financeiro.

### Uso Diário

1. Registrar gastos pelo chat.
2. Receber confirmação automática.
3. Consultar saldo e relatórios.
4. Receber insights e recomendações.

---

## Telas do MVP

### Tela 1 - Onboarding

Objetivo:
Coletar informações básicas do usuário.

Itens:

- Nome
- Faixa de renda
- Objetivo financeiro principal

### Tela 2 - Chat Financeiro

Objetivo:
Centralizar toda interação do usuário.

Recursos:

- Campo de mensagem
- Sugestões rápidas
- Histórico de conversa

### Tela 3 - Dashboard

Objetivo:
Exibir visão geral da situação financeira.

Componentes:

- Saldo atual
- Receitas
- Despesas
- Metas
- Insights

### Tela 4 - Metas Financeiras

Objetivo:
Gerenciar objetivos financeiros.

Componentes:

- Lista de metas
- Progresso visual
- Estimativa de conclusão

### Tela 5 - Histórico de Transações

Objetivo:
Permitir revisão e correção dos lançamentos.

Componentes:

- Busca
- Filtro por categoria
- Edição de registros

---

## Design Universal e Acessibilidade

### Objetivo

Garantir que o produto seja simples, intuitivo e acessível para o maior número possível de pessoas.

### Linguagem Simples

Todo o conteúdo deverá utilizar linguagem clara e acessível.

Evitar:

- Termos técnicos financeiros complexos.
- Jargões contábeis.
- Siglas sem explicação.

Exemplos:

Em vez de:
"Seu fluxo de caixa apresentou déficit no período."

Utilizar:
"Você gastou mais do que recebeu neste mês."

### Interface Conversacional Natural

O usuário não deve precisar decorar comandos ou instruções específicas.

Exemplos válidos:

- "Paguei R$ 50 de Uber."
- "Gastei R$ 30 no almoço."
- "Recebi R$ 2.500 de salário."

### Baixa Carga Cognitiva

A interface deve priorizar:

- Simplicidade.
- Poucas ações por tela.
- Informações essenciais.
- Feedback imediato.

Evitar:

- Excesso de gráficos.
- Muitas opções simultâneas.
- Terminologia técnica.

### Acessibilidade

O produto deverá:

- Possuir contraste adequado.
- Utilizar fontes legíveis.
- Ser compatível com leitores de tela.
- Permitir navegação por teclado.
- Utilizar textos alternativos em elementos visuais.
- Não depender exclusivamente de cores para transmitir informações.

### Mobile First

A experiência principal deve ser otimizada para dispositivos móveis.

### Feedback Contínuo

Após cada ação, o sistema deve informar claramente o resultado.

Exemplo:

"Gasto de R$ 45 registrado em Alimentação."

### Personalização Progressiva

O sistema deve funcionar para iniciantes desde o primeiro uso, apresentando recursos mais avançados gradualmente conforme o usuário evolui.

---

## Requisitos Técnicos

### Frontend

- Interface mobile-first.
- Design limpo e amigável.
- Experiência semelhante a aplicativos de mensagens.
- Componentes acessíveis.
- Navegação simplificada.

### Backend

- Banco de dados de usuários.
- Banco de dados de transações.
- Motor de interpretação de linguagem natural.
- Sistema de categorização automática.

### Inteligência Artificial

Capaz de:

- Extrair valores monetários.
- Detectar receitas e despesas.
- Classificar categorias.
- Gerar insights financeiros.
- Detectar padrões de consumo.
- Produzir recomendações personalizadas.

---

## Métricas de Sucesso

### Engajamento

- 70% dos usuários registram pelo menos uma transação na primeira sessão.

### Retenção

- 30% dos usuários retornam após 7 dias.

### Usabilidade

- 80% das transações são registradas sem necessidade de edição manual.

### Valor Percebido

- Nota média superior a 4/5 para recomendações do Agente Financeiro.

---

## Estratégia de Validação

### Hipótese Principal

Usuários preferem registrar gastos utilizando conversas em linguagem natural em vez de formulários tradicionais.

### Teste Inicial

Liberar o MVP para 10 a 20 usuários.

### Coletar

- Frequência de uso.
- Número de transações registradas.
- Tempo médio por registro.
- Feedback qualitativo.
- Facilidade de aprendizado.

### Critério de Sucesso

Pelo menos 60% dos usuários consideram a experiência mais simples do que aplicativos financeiros tradicionais.

---

## Não Objetivos do MVP

Itens fora do escopo da primeira versão:

- Integração bancária automática.
- Open Finance.
- Investimentos avançados.
- Planejamento tributário.
- Gestão financeira familiar.
- Integração com cartões de crédito.
- Compartilhamento de contas entre usuários.
- Análises financeiras complexas.
```

Resultado final no Lovable: 
https://bolso-brilhante-financas-pessoais.lovable.app/painel

<img width="1920" height="951" alt="image" src="https://github.com/user-attachments/assets/46a6fad1-2dbf-458a-ab64-ab441c30d2a5" />
<img width="1920" height="1625" alt="image" src="https://github.com/user-attachments/assets/2be8fdb5-a39b-4ec5-b151-00c1e3e1f243" />
<img width="1920" height="1391" alt="image" src="https://github.com/user-attachments/assets/4f63574b-19e6-4b78-9247-f154202ef1d5" />
<img width="1920" height="951" alt="image" src="https://github.com/user-attachments/assets/9c4f7290-16d9-41ee-b47b-e1b285b40b4b" />
<img width="1920" height="951" alt="image" src="https://github.com/user-attachments/assets/d7fbf57b-cb82-43ab-92ae-346afa9771b6" />
<img width="1920" height="951" alt="image" src="https://github.com/user-attachments/assets/88133b50-a7a8-4c58-867f-c2e0536a6e69" />
<img width="1920" height="951" alt="image" src="https://github.com/user-attachments/assets/a5b8fc81-7411-4b11-a25d-1e00951be7db" />

# Resumo do FinanChat

FinanChat é uma aplicação web de finanças pessoais que utiliza linguagem natural para simplificar o controle financeiro.

Em vez de preencher planilhas ou formulários complexos, o usuário pode registrar receitas e despesas por meio de uma conversa simples. O sistema interpreta automaticamente as mensagens, classifica as transações, atualiza o saldo e gera visualizações financeiras em tempo real.

## Proposta

O objetivo do FinanChat é tornar a organização financeira mais acessível para pessoas que desejam controlar melhor seu dinheiro sem precisar aprender ferramentas complexas.

Exemplos de uso:

- "Gastei 50 reais no almoço"
- "Recebi meu salário de 4500"
- "Paguei 23 reais no cinema"

A partir dessas mensagens, o sistema identifica valores, categorias e tipos de transação automaticamente.

## Funcionalidades

- Registro de receitas e despesas via chat.
- Processamento de linguagem natural.
- Classificação automática de transações.
- Atualização automática de saldo.
- Dashboard financeiro.
- Análise de gastos por categoria.
- Histórico de movimentações.
- Gerenciamento de metas financeiras.
- Acompanhamento de progresso das metas.
- Interface simples e acessível.

## Principais Telas

### Chat Financeiro

Permite registrar movimentações financeiras por meio de mensagens em linguagem natural.

### Painel

Apresenta indicadores financeiros importantes, incluindo:

- Saldo atual.
- Total recebido.
- Total gasto.
- Resumo financeiro do mês.
- Categorias com maiores despesas.
- Evolução financeira.

### Metas

Permite criar e acompanhar objetivos financeiros, mostrando:

- Valor desejado.
- Valor acumulado.
- Percentual de conclusão.
- Prazo estimado.
- Valor necessário para atingir a meta no prazo definido.

### Histórico

Centraliza todas as movimentações registradas pelo usuário para consulta futura.

## Design

O projeto foi desenvolvido seguindo princípios de Design Universal, priorizando:

- Simplicidade.
- Acessibilidade.
- Linguagem clara.
- Baixa curva de aprendizado.
- Boa experiência para diferentes perfis de usuários.

## Tecnologias

- React
- TypeScript
- Tailwind CSS
- Lovable

## Objetivo do Projeto

Este projeto foi desenvolvido como exercício de Product Discovery, UX Design e Vibe-Coding, explorando o uso de inteligência artificial para criação rápida de produtos digitais centrados no usuário.

## Reflexão
### O que funcionou bem?  
O copilot fez um excelente trabalho ao refinar o PRD inicial que resultou em um ótimo MVP.

### O que não funcionou como o esperado?  
Foi necessário aguardar mais tempo que o esperado por conta dos créditos do lovable acabarem antes dele concluir a construção do app.

### O que aprendeu sobre conversar com IAs?
Aprendi que é necessário ser bem claro para assim não ser necessário gastar tantos tokens/créditos das IAs.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
