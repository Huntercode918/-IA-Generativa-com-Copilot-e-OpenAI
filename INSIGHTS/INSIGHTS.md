# 🧠 Insights e Aprendizados

Este documento reúne os principais insights, aprendizados e reflexões adquiridos durante a exploração dos recursos de IA generativa com Copilot, OpenAI e Azure AI Foundry. O objetivo é compartilhar experiências práticas, destacar boas práticas e apontar desafios e oportunidades identificados ao longo do laboratório.

---

## ✨ Principais Aprendizados

- **Facilidade de Prototipação:**  
  O Azure AI Foundry e o playground permitem criar, configurar e testar rapidamente projetos com modelos de IA generativa, facilitando a prototipação de soluções e a experimentação de prompts.

- **Iteração de Prompts:**  
  Refinar perguntas, adicionar contexto, fornecer fontes (grounding) e definir expectativas claras são estratégias essenciais para obter respostas mais relevantes, precisas e alinhadas aos objetivos do usuário.

- **Importância dos Filtros de Conteúdo:**  
  Os filtros default bloqueiam automaticamente tentativas de geração de conteúdo sensível (violência, autoagressão, ódio, sexualidade etc.). Filtros customizados possibilitam controlar ainda mais o nível de tolerância, garantindo adequação às políticas da organização e à ética no uso da IA.

- **Autocensura dos Modelos:**  
  Mesmo sem filtros explícitos, modelos como GPT-4 e Phi-4 podem se autocensurar ao responder a prompts sensíveis, demonstrando uma camada adicional de responsabilidade embutida no próprio treinamento.

- **Documentação Visual:**  
  A inclusão de capturas de tela e exemplos reais de interações auxilia na compreensão dos resultados e no compartilhamento do conhecimento adquirido.

---

## ⚡ Dificuldades & Pontos de Atenção

- **Restrições Regionais:**  
  Alguns modelos e recursos estão disponíveis apenas em determinadas regiões do Azure, o que pode exigir ajustes na criação dos projetos.

- **Custo de Recursos:**  
  É fundamental remover os recursos criados ao final dos experimentos para evitar cobranças desnecessárias.

- **Bloqueios às Vezes Excessivos:**  
  Certos prompts inofensivos podem ser bloqueados dependendo do filtro configurado, exigindo revisões e ajustes constantes para equilibrar segurança e utilidade.

---

## 🏆 Boas Práticas

- Sempre experimente diferentes modelos e configurações de filtro para entender os limites e capacidades de cada ferramenta.
- Documente cada etapa do processo, incluindo exemplos de prompts, respostas e capturas de tela.
- Revise as políticas de uso responsável e de segurança antes de publicar ou disponibilizar soluções baseadas em IA generativa.
- Compartilhe insights e aprendizados com a equipe para acelerar o amadurecimento coletivo no uso dessas tecnologias.

---

## 🚀 Próximos Passos Sugeridos

- Explorar integrações com outras APIs e automações usando Copilot e OpenAI.
- Criar filtros customizados específicos para diferentes domínios de aplicação.
- Investigar métricas de avaliação de qualidade das respostas e satisfação do usuário final.
- Manter-se atualizado com os recursos em preview e novas funcionalidades lançadas pela Microsoft e OpenAI.

---

> 💬 Tem algum insight para compartilhar? Sinta-se à vontade para atualizar este arquivo ou abrir uma issue!
