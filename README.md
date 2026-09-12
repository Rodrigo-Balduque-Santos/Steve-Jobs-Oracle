# 🍎 Oráculo Steve Jobs: Caderno Temático no NotebookLM

> **Desafio de Projeto — DIO (Digital Innovation One)**  
> *Uso de Inteligência Artificial para Aprendizagem Ativa, Engenharia de Prompts e Liderança de Negócios.*

---

## 📌 Contexto e Objetivos

### Contexto
Steve Jobs foi um dos executivos mais icônicos do século XXI, revolucionando as indústrias de computadores pessoais, animação, música e telefonia móvel. Este projeto consiste na criação de um **Caderno Temático no NotebookLM**, batizado de **"Oráculo Steve Jobs"**, com o objetivo de centralizar, analisar e sintetizar o ecossistema de conhecimento sobre o estilo de gestão, princípios de liderança e mentalidade de produto de Jobs.

### Objetivos de Estudo
1. **Liderança e Gestão Estratégica:** Compreender os princípios de tomada de decisão, gestão de equipes e cultura de inovação aplicados por Steve Jobs.
2. **Desenvolvimento de Produtos:** Extrair lições sobre simplicidade (*foco na experiência do usuário*), design funcional e visão mercadológica.
3. **Engenharia de Prompts & IA:** Testar e documentar o comportamento do NotebookLM operando sob uma instrução de persona personalizada (*Personalização: "Comporte-se como um CEO e gestor com todo o conhecimento e experiência de Steve Jobs"*).

---

## 📚 Curadoria de Fontes

O caderno **"Oráculo Steve Jobs"** reuniu 33 fontes abertas entre artigos, transcrições e vídeos. Abaixo destacam-se as principais referências utilizadas:

1. **Artigo:** *'Steve Jobs: as verdades e mitos sobre a gestão'* (Fonte externa / PDF)
2. **Vídeo/Transcrição:** *DE UMA GARAGEM À APPLE: A História de Inovação*
3. **Estudo de Caso:** *7 lições de Steve Jobs sobre Inovação e Liderança*
4. **Guia Prático:** *7 Táticas do Steve Jobs para Apresentações Persuasivas*
5. **Artigo:** *A regra 10-80-10 de Steve Jobs para delegação e foco*

---

## 🧠 Engenharia de Prompts, Testes e Troubleshooting ("Cicatrizes")

Nesta seção, registramos a evolução das interações com a IA no NotebookLM e as lições aprendidas durante o refinamento das perguntas.

### 1. Configuração do System Prompt (Personalização)
* **Prompt de Instrução:** `"Comporte-se como um CEO, e gestor, com todo o conhecimento e experiência de Steve Jobs."`
* **Objetivo:** Garantir respostas com tom executivo, direto, focado em simplicidade e com respostas fundamentadas nas fontes.

### 2. Teste de Prompts e Variações

#### 🔴 Teste 1: Prompt Genérico
* **Pergunta:** *"O que Steve Jobs pensava sobre reuniões?"*
* **Resultado:** A IA trouxe uma resposta genérica resumindo alguns pontos rasos sobre encontros produtivos.
* **Diagnóstico/Dificuldade:** Faltou contexto sobre o ambiente de trabalho e o método específico da Apple.

#### 🟡 Teste 2: Prompt Estruturado (Iteração)
* **Pergunta:** *"Com base nas fontes, quais eram as 3 regras de ouro de Steve Jobs para conduzir reuniões operacionais na Apple? Justifique com trechos dos materiais."*
* **Resultado:** Resposta precisa, listando a regra da sala enxuta (poucas pessoas), agenda focada e ausência de apresentações genéricas de PowerPoint.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados do Assunto

#### A. Filosofia de Produto e Design
* **Simplicidade Absoluta:** O design não é apenas a aparência, mas como a coisa funciona. Elimine o desnecessário.
* **Foco Extremo:** Saber dizer *"não"* para 1.000 boas ideias para conseguir focar em apenas 1 ideia revolucionária.
* **Integração Vertical:** Controle total do hardware e software para entregar a melhor experiência ao usuário.

#### B. Estilo de Liderança e Gestão
* **Regra 10-80-10:** Participar ativamente dos 10% iniciais (concepção/visão) e dos 10% finais (refinamento/qualidade), delegando os 80% intermediários para times capacitados.
* **Filtro de Excelência:** Não aceitar o "bom o suficiente". Exigir rigor máximo da equipe de engenharia e design.

---

### 2. Glossário de Conceitos Aprendidos

| Conceito | Definição |
| :--- | :--- |
| **Campo de Distorção da Realidade** | Habilidade de persuadir e inspirar equipes a alcançarem metas consideradas impossíveis. |
| **Integração Vertical** | Modelo de negócios no qual a empresa controla toda a jornada do produto (hardware, software e serviços). |
| **UX/UI Centrado no Usuário** | Princípio de colocar a facilidade de uso e a intuição acima da complexidade técnica. |
| **Foco Estratégico** | Capacidade executiva de eliminar distrações e focar em poucas iniciativas prioritárias. |

---

### 3. Prompts Reutilizáveis para Revisões Futuras

Abaixo estão os templates de prompts criados e validados para usar neste ou em outros cadernos de negócios:

* **Para Análise de Decisões:**
  ```text
  "Com base nas fontes anexadas, se você estivesse enfrentando o problema [INSERIR PROBLEMA], qual seria a tomada de decisão estratégica adotada por Steve Jobs? Liste 3 passos claros."
