# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

'''markdown
    PRD – App de Organização de Finanças Pessoais com Design Universal

    1. Contexto
    O aplicativo tem como objetivo facilitar a organização financeira pessoal por meio de uma experiência conversacional em linguagem natural. 
    A solução deve seguir princípios de Design Universal, garantindo que o maior número possível de pessoas, com diferentes habilidades e níveis de familiaridade tecnológica, consiga usar o app com clareza, autonomia e conforto.

    2. Problema
    Usuários frequentemente desistem de controlar suas finanças porque os apps atuais exigem muitas etapas manuais, têm interfaces complexas e oferecem pouca personalização. 
    Além disso, muitas soluções não consideram diversidade de perfis e necessidades, resultando em barreiras de uso. 
    Este projeto busca oferecer uma experiência inclusiva, simples e personalizada, baseada em conversa natural.

    3. Público-Alvo
    Pessoas que desejam começar a organizar suas finanças de forma prática e descomplicada, especialmente:
    • Iniciantes em educação financeira
    • Usuários com pouca familiaridade com apps
    • Pessoas que preferem interação conversacional
    • Usuários que necessitam de interfaces acessíveis e adaptáveis
    O objetivo é proporcionar boa experiência para qualquer pessoa, independentemente de limitações sensoriais, motoras ou cognitivas.

    4. Princípio Central: Design Universal
    O aplicativo deve incorporar desde a concepção:
    • Interface limpa, clara e consistente
    • Compatibilidade com leitores de tela (ex.: VoiceOver, TalkBack)
    • Textos legíveis, com contraste adequado e tipografia acessível
    • Fluxos simples e previsíveis
    • Entrada por texto e por voz
    • Feedbacks compreensíveis e imediatos
    • Possibilidade de personalização (tamanho de fonte, notificações, visualizações)
    Esses requisitos influenciam UI, UX, conteúdo e comportamento do agente conversacional.

    5. Funcionalidades-Chave (MVP)
    1. Registro de gastos via chat em linguagem natural
       - Suporte a texto e voz
       - Interpretação automática de valores, datas e categorias

    2. Classificação automática das transações
       - Sugestões justificáveis e fáceis de corrigir pelo usuário

    3. Definição e acompanhamento de metas financeiras básicas
       - Orientações simples e exemplos concretos durante a configuração

    4. Agente Financeiro com dicas personalizadas
       - Recomendações contextualizadas e linguagem acessível

    5. Relatórios simples e personalizáveis
       - Visualizações acessíveis e resumos textuais

    6. Entregável da IA
    A IA deve produzir:
    • Plano de MVP
      - Telas essenciais
      - Fluxos principais
      - Recursos mínimos necessários
      - Requisitos de Design Universal aplicáveis

    • Esboço de validação inicial
      - Hipóteses
      - Métricas
      - Primeiros testes com usuários diversos
      '''
Interações com o Lovable:

> Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}

> Segui o exemplo que o próprio programa deu que foi incluir alguns gastos;

> Estou com dúvidas sobre categorizar pizza em "outros" e não em "alimentação". Por quê?

Resultado final no Lovable: https://conversa-facil-financeiro.lovable.app/

<img width="688" height="478" alt="image" src="https://github.com/user-attachments/assets/b09fbc5f-39fc-47b8-b5cf-eb45a8205d7e" />


***

# Funcionalidades do Aplicativo

## 1. Registro de Gastos via Chat

O usuário registra despesas e receitas usando linguagem natural por texto ou voz.  
Exemplos de entrada:

*   "Gastei 40 reais com transporte"
*   "Recebi 3200 de salário hoje"

O sistema interpreta automaticamente valor, categoria, data e tipo da transação.

***

## 2. Resumo do Mês

Com base no print fornecido, a tela de resumo apresenta:

*   **Saldo:** R$ 4.558,00
*   **Receitas:** R$ 5.200,00
*   **Gastos:** R$ 642,00

Inclui também um gráfico de **Gastos por categoria**, oferecendo visão rápida e clara do mês.

***

## 3. Classificação Automática

Cada transação registrada é automaticamente categorizada (ex.: alimentação, transporte, lazer).  
O usuário pode revisar e corrigir com facilidade.  
A categorização é explicável e transparente.

***

## 4. Metas Financeiras

O app permite criar e acompanhar metas como:

*   "Gastar até R$ 200 com delivery este mês"
*   "Economizar R$ 150 por semana"

A aba **Metas** (visível no menu inferior) centraliza o acompanhamento.

***

## 5. Agente Financeiro

Um assistente integrado fornece recomendações personalizadas, tais como:

*   alertas de gastos fora do padrão
*   sugestões de economia
*   insights sobre categorias com maior peso no orçamento
*   lembretes de registro

Sempre com linguagem simples e didática.

***

## 6. Relatórios Simples e Acessíveis

O app oferece:

*   Resumo semanal ou mensal
*   Visualizações acessíveis
*   Versão em texto para leitura facilitada
*   Gráfico por categorias

Projetado para atender diferentes perfis e necessidades.

***

## 7. Ajustes Personalizáveis

A aba **Ajustes** permite configurar:

*   preferências de notificação
*   visualização dos relatórios
*   parâmetros gerais de uso
*   opções de acessibilidade (segundo os princípios de Design Universal)

***

## 8. Design Universal

Toda a interface foi concebida para ser utilizável pelo maior número possível de pessoas.  
Inclui:

*   interface clara e com bom contraste
*   textos legíveis
*   navegação simples e previsível
*   compatibilidade com leitores de tela
*   possibilidade de entrada por voz ou texto
*   personalização de ritmo e preferências

O fluxo reduz carga cognitiva e respeita ritmos diferentes de aprendizado.

***
 
## Reflexão
  
  ## O que funcionou bem? 
  O refinamento do PRD previamente realizado no Copilot ajudou muito, pois os créditos do Lovable acabaram em apenas 3 interações. 
  
  ## O que não funcionou como o esperado?  
  Esperava interagir mais vezes gratuitamente com o Lovable, mas as interações feitas já foram de grande valia para aprender mais sobre Vibe Coding.
  
  ## O que aprendeu sobre conversar com IAs?
  Aprendi que é basicamente igual a falar com humanos, quanto mais detalhes e clareza você dá, melhor é a interação.

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
