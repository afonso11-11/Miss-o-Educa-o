# EDU Analytics Platform - Simulação Big Data

Projeto de interface interativa para simular um cenário de Big Data aplicado à educação a distância (EAD), com foco em análise de comportamento de alunos, recomendação de conteúdo e retenção.

## Sobre o projeto

A página apresenta uma simulação visual do fluxo de dados de 100 mil alunos em uma plataforma educacional. O objetivo é demonstrar, de forma didática, as etapas principais de um pipeline analítico:

1. Coletar interação
2. Criar perfil
3. Recomendar conteúdo
4. Medir retenção

Além disso, o projeto exibe métricas dinâmicas, logs em tempo real e gráficos que ajudam na interpretação dos dados simulados.

## Funcionalidades

- Simulação interativa com controles de iniciar, pausar e reiniciar
- Atualização automática dos dados simulados
- Controle de velocidade da simulação
- Logs em tempo real no painel lateral
- Cartões de etapas com destaque visual da etapa ativa
- Gráficos interativos com Chart.js:
  - Linha: interações
  - Rosca: perfis de aprendizagem
  - Barras: recomendações
  - Dispersão: risco de churn
- Layout responsivo para desktop e mobile

## Tecnologias utilizadas

- HTML5
- CSS3 (estilo glassmorphism, gradientes e animações)
- JavaScript (manipulação de DOM e simulação de dados)
- Chart.js (renderização dos gráficos)
- Font Awesome (ícones)
- Google Fonts

## Estrutura do projeto

- index.html: página única com estrutura, estilos e scripts

## Como executar

1. Faça o download ou clone deste repositório.
2. Abra a pasta do projeto.
3. Abra o arquivo index.html no navegador.

Opcionalmente, para uma melhor experiência em desenvolvimento, utilize a extensão Live Server no VS Code e execute o arquivo em servidor local.

## Como usar

1. Clique em Iniciar Simulação.
2. Acompanhe a atualização das métricas e dos logs.
3. Ajuste a velocidade no controle deslizante.
4. Use Atualização Automática para ativar ou desativar o refresh contínuo.
5. Clique em Reiniciar para limpar o estado atual e começar novamente.

## Objetivo acadêmico

Este projeto é indicado para apresentações, prototipação e estudos de conceitos de Big Data em educação, como:

- ingestão de eventos
- perfilamento comportamental
- recomendação personalizada
- análise preditiva de evasão

## Melhorias futuras sugeridas

- Separar CSS e JavaScript em arquivos dedicados
- Integrar API real para dados históricos
- Persistir logs e métricas em banco de dados
- Adicionar filtros por curso, turma e período
- Incluir autenticação e perfis de usuário

## Autor

Projeto desenvolvido para fins educacionais e de demonstração.
