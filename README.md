# 🤖 IA Generativa com Copilot e OpenAI

[![Azure AI Foundry](https://img.shields.io/badge/Azure%20AI-Foundry-blue?logo=microsoftazure)](https://ai.azure.com)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-green?logo=openai)]
[![Copilot](https://img.shields.io/badge/GitHub-Copilot-blueviolet?logo=github)]
[![License: MIT](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)

Explorando os Recursos de IA Generativa com Copilot e OpenAI  
Este repositório reúne experimentos práticos e documentação detalhada sobre as principais funcionalidades de IA generativa disponíveis nas plataformas Microsoft (Copilot), OpenAI e Azure AI Foundry.

Aqui você vai encontrar exemplos de uso real, prompts testados, resultados obtidos e anotações sobre os aprendizados adquiridos durante a exploração dessas tecnologias avançadas. O objetivo é facilitar o entendimento, a aplicação e o compartilhamento de boas práticas para quem deseja iniciar ou aprofundar seus conhecimentos em IA generativa aplicada ao desenvolvimento e à automação.

---

## 📊 Dashboard do Laboratório

| Tópico                                | Status       | Exemplos disponíveis | Observações |
|---------------------------------------|:------------:|:-------------------:|:-----------:|
| Criação de Projeto Azure AI Foundry   | ✅ Concluído |     🟢 Sim          | Passo a passo no README |
| Playground de Modelos (GPT-4, Phi-4)  | ✅ Concluído |     🟢 Sim          | Exemplos em `PROMPTS.md`  |
| Experimentação de Prompts             | ✅ Concluído |     🟢 Sim          | Iteração, contexto e grounding |
| Filtros de Conteúdo (default/custom)  | ✅ Concluído |     🟢 Sim          | Testes em `PROMPTS.md`    |
| Anotações e Insights                  | ✅ Concluído |     🟢 Sim          | Veja `INSIGHTS.md`        |
| Limpeza de Recursos                   | ✅ Concluído |         -           | Detalhado abaixo        |

---

## 📁 Estrutura do Repositório

```
/
├── README.md
├── PROMPTS/
│   └── PROMPTS.md
├── INSIGHTS/
│   └── INSIGHTS.md
```

- **README.md**: Visão geral, dashboard e links principais
- **PROMPTS.md**: Exemplos de prompts utilizados e resultados
- **INSIGHTS.md**: Reflexões e aprendizados do laboratório
- **LICENSE**: Licença do projeto

---

## 🚀 Passo a Passo Resumido

### 1️⃣ Criação de Projeto no Azure AI Foundry

- Acesse [Azure AI Foundry Portal](https://ai.azure.com)
- Crie um novo projeto com AI Hub Resource, preenchendo nome, subscription, resource group e região.
- Acesse o Overview do projeto após a criação.

### 2️⃣ Playground de Modelos

- No menu, acesse **Playgrounds** e selecione **Chat playground**.
- Realize o deploy de um modelo (gpt-4, gpt-4o ou phi-4).
- Utilize prompts variados para explorar respostas (veja exemplos em `PROMPTS.md`).

### 3️⃣ Melhoria e Iteração de Prompts

- Experimente prompts com objetivos claros, refina as perguntas conforme as respostas, adicione fontes/contexto e defina o formato desejado na resposta.
- Exemplos práticos estão em [`PROMPTS.md`](PROMPTS.md).

### 4️⃣ Testes com Filtros de Conteúdo

- Teste o comportamento do modelo com filtros **default**, **sem filtro** e **customizado** (bloqueando temas como violência, ódio, sexual e autoagressão).
- Confira exemplos de prompts e respostas para cada contexto.

### 5️⃣ Anotações e Insights

- As principais lições, boas práticas e dificuldades estão em [`INSIGHTS.md`](INSIGHTS.md).

### 6️⃣ Limpeza dos Recursos

- Após os testes, acesse o [Azure Portal](https://portal.azure.com), localize o resource group utilizado e exclua para evitar custos adicionais.

---

## 📌 Exemplos de Uso

Consulte [`PROMPTS.md`](PROMPTS.md) para ver exemplos práticos de prompts aplicados, incluindo:

- Planejamento de viagem com contexto e iteração de perguntas
- Consulta a fontes externas para grounding das respostas
- Testes de segurança com prompts sensíveis
- Definição de papéis e formatos de resposta

---

## 📚 Recursos Oficiais

- [Explore generative AI with Microsoft Copilot](https://learn.microsoft.com/en-us/training/modules/explore-generative-ai-microsoft-copilot/)
- [Explore Azure OpenAI](https://learn.microsoft.com/en-us/training/modules/explore-azure-openai/)
- [Explore content filters in Azure OpenAI](https://learn.microsoft.com/en-us/training/modules/explore-content-filters-azure-openai/)

---

> 💡 **Colabore!** Este repositório é aberto para consulta e colaboração. Sinta-se à vontade para sugerir melhorias ou compartilhar seus próprios exemplos!
