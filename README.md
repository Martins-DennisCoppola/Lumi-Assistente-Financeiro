# 💡 Lumi - Assistente de Educação Financeira com IA Local

O **Lumi** é um assistente inteligente projetado para transformar a forma como as pessoas interagem com suas finanças pessoais. O projeto nasceu da necessidade de unir análise de dados estruturada com a facilidade de conversação da Inteligência Artificial.

---

## 🎯 Diferenciais Técnicos: Privacidade e Eficiência
Diferente de assistentes que dependem de APIs de nuvem, o Lumi utiliza o **Ollama** para rodar modelos de linguagem (LLMs) localmente. 
- **Soberania de Dados:** Informações financeiras sensíveis nunca saem da máquina do usuário.
- **Custo Zero:** Sem dependência de tokens pagos de terceiros.
- **Performance:** Respostas rápidas e processamento offline.

## 🛠️ Tecnologias Utilizadas
- **Python**: Linguagem base para toda a lógica de processamento de dados.
- **Streamlit**: Interface web moderna, focada na experiência do usuário (UX).
- **Ollama**: Orquestração de modelos de IA locais.
- **SQLite**: (Próxima etapa) Banco de dados relacional para persistência de transações e histórico.

## 📈 Jornada de Desenvolvimento
Este projeto foi iniciado como um desafio prático dentro do bootcamp **Bradesco GenAI & Dados (DIO)**. Desde então, venho evoluindo sua arquitetura para incluir:
1. Melhoria na engenharia de prompts para evitar alucinações.
2. Estruturação de dados para futuras análises estatísticas.
3. Interface interativa para visualização de metas financeiras.

## 🚀 Como executar o projeto
1. Instale o [Ollama](https://ollama.ai/) e baixe o modelo de sua preferência (ex: Llama3 ou Mistral).
2. Clone este repositório.
3. Instale as dependências: `pip install streamlit`
4. Execute: `streamlit run app.py`

---
*Desenvolvido por **Dennis Martins Coppola** como parte do meu portfólio de transição para a carreira de **Analista de Dados**.*
