# EDU Analytics Platform — Simulação Big Data

Dashboard interativo desenvolvido em HTML para simular um pipeline de Big Data aplicado à Educação a Distância (EAD). A aplicação é executada inteiramente no navegador, sem necessidade de servidor ou ambiente de desenvolvimento configurado.

---

## Descrição

O projeto demonstra, de forma visual e didática, como um sistema de análise de dados educacionais processa informações de alunos em tempo real. A simulação percorre quatro etapas sequenciais do pipeline:

1. **Coletar Interação** — captura eventos gerados pelos alunos, como cliques, acessos e tempo de tela.
2. **Criar Perfil** — agrupa comportamentos e constrói o perfil de aprendizagem de cada aluno.
3. **Recomendar Conteúdo** — sugere materiais personalizados com base no perfil identificado.
4. **Medir Retenção** — calcula indicadores de engajamento e risco de abandono (churn).

---

## Funcionalidades

- Controles de simulação: iniciar, pausar e reiniciar
- Atualização automática configurável
- Controle deslizante de velocidade da simulação
- Destaque visual da etapa ativa do pipeline
- Painel de logs em tempo real
- Contadores de alunos ativos e recomendações do dia
- Gráficos dinâmicos:
  - Linha: interações ao longo do tempo
  - Rosca: distribuição dos perfis de aprendizagem
  - Barras: volume de recomendações por categoria
  - Dispersão: mapa de risco de churn
- Layout responsivo para desktop e dispositivos móveis

---

## Tecnologia

O projeto foi desenvolvido exclusivamente em **HTML**, com todo o conteúdo, estilos e lógica contidos em um único arquivo `index.html`.

---

## Estrutura do Repositório

```
/
├── index.html   — aplicação completa
└── README.md    — documentação
```

---

## Como Executar

1. Clone o repositório:
   ```
   git clone https://github.com/afonso11-11/Miss-o-Educa-o.git
   ```
2. Abra o arquivo `index.html` diretamente no navegador.

Não é necessário instalar dependências ou configurar um servidor.

---

## Como Utilizar

1. Clique em **Iniciar Simulação** para iniciar o pipeline.
2. Acompanhe os logs e os gráficos atualizando em tempo real.
3. Utilize o controle deslizante para ajustar a velocidade da simulação.
4. Ative ou desative a atualização automática conforme necessário.
5. Clique em **Reiniciar** para redefinir o estado da simulação.
