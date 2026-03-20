# EDU Analytics Platform — Simulação Big Data

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)

Dashboard interativo que simula um pipeline de **Big Data aplicado à Educação a Distância (EAD)**. Toda a aplicação roda em um único arquivo HTML, sem necessidade de servidor ou dependências externas além de CDNs públicos.

---

## Visão Geral

A simulação percorre **4 etapas** do pipeline de dados em tempo real:

| # | Etapa | Descrição |
|---|-------|-----------|
| 1 | **Coletar Interação** | Captura eventos gerados pelos alunos (cliques, acessos, tempo de tela) |
| 2 | **Criar Perfil** | Agrupa comportamentos e constrói o perfil de aprendizagem do aluno |
| 3 | **Recomendar Conteúdo** | Sugere materiais personalizados com base no perfil identificado |
| 4 | **Medir Retenção** | Calcula indicadores de engajamento e risco de churn |

---

## Funcionalidades

- ▶ Iniciar, ⏸ Pausar e 🔄 Reiniciar a simulação
- Atualização automática configurável (ON/OFF)
- Controle deslizante de velocidade da simulação
- Cartões com destaque visual da etapa ativa
- Painel de logs em tempo real
- Estatísticas de alunos ativos e recomendações do dia
- Gráficos dinâmicos com **Chart.js**:
  - **Linha** — interações ao longo do tempo
  - **Rosca (Doughnut)** — distribuição dos perfis de aprendizagem
  - **Barras** — volume de recomendações por categoria
  - **Dispersão (Scatter)** — mapa de risco de churn
- Layout **responsivo** para desktop e mobile

---

## Estrutura do Projeto

```
big data duo/
├── index.html   # Aplicação completa (HTML + CSS + JavaScript)
└── README.md    # Documentação do projeto
```

---

## Tecnologias Utilizadas

| Tecnologia | Versão / CDN |
|------------|-------------|
| HTML5 | — |
| CSS3 | — |
| JavaScript (ES6+) | — |
| [Chart.js](https://www.chartjs.org/) | CDN (jsdelivr) |
| [Font Awesome](https://fontawesome.com/) | 6.4.0 (cdnjs) |
| [Google Fonts](https://fonts.google.com/) | Inter + Montserrat |

---

## Como Executar

```bash
# 1. Clone o repositório
git clone https://github.com/afonso11-11/Miss-o-Educa-o.git

# 2. Acesse a pasta
cd "Miss-o-Educa-o"

# 3. Abra o arquivo no navegador
start index.html   # Windows
open index.html    # macOS
xdg-open index.html # Linux
```

> **Dica:** No VS Code, use a extensão **Live Server** para recarregamento automático durante o desenvolvimento.

---

## Como Usar

1. Clique em **Iniciar Simulação** para começar o pipeline.
2. Acompanhe os **logs** e os **gráficos** sendo atualizados em tempo real.
3. Ajuste a **velocidade** no controle deslizante.
4. Ative ou desative a **Atualização Automática** conforme necessário.
5. Clique em **Reiniciar** para limpar o estado e recomeçar do zero.

---

## Licença

Este projeto é de uso educacional e livre para fins de estudo e demonstração.
