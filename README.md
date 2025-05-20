# 🤖 Agentes de IA para Criação de Posts no LinkedIn 🚀

Este projeto, desenvolvido durante a Imersão IA da Alura 🎓, demonstra a criação de um sistema de agentes de Inteligência Artificial (IA) para automatizar o processo de criação de posts para o LinkedIn. O sistema é composto por quatro agentes especializados que trabalham em conjunto para buscar notícias 📰, planejar o conteúdo 📝, redigir o post ✍️ e revisar a qualidade ✅.

## ✨ Funcionalidades

O sistema implementa os seguintes agentes:

1.  **Agente Buscador de Notícias 🔍:**
    * Utiliza a ferramenta de busca do Google para encontrar as últimas notícias sobre um tópico específico.
    * Filtra as notícias para selecionar apenas as mais relevantes e impactantes.
2.  **Agente Planejador de Posts 🗺️:**
    * Analisa as notícias encontradas pelo Agente Buscador.
    * Define os pontos mais relevantes a serem abordados no post.
    * Cria um plano detalhado do conteúdo do post.
3.  **Agente Redator de Posts ✍️:**
    * Escreve um rascunho do post do LinkedIn com base no plano fornecido pelo Agente Planejador.
    * Utiliza uma linguagem envolvente, informativa e adequada para o público do LinkedIn.
4.  **Agente Revisor de Qualidade 🧐:**
    * Revisa o rascunho do post, verificando a clareza, concisão, correção gramatical e tom.
    * Garante que o post esteja pronto para ser publicado.

## 🛠️ Tecnologias Utilizadas

* Python 🐍
* Google Gemini API ♊
* Google ADK (Agent Development Kit)
* Bibliotecas: `os`, `google.colab`, `google.genai`, `IPython.display`, `requests`, `datetime`, `textwrap`

## ⚙️ Pré-requisitos

* Chave da API do Google Gemini configurada como variável de ambiente (`GOOGLE_API_KEY`). 🔑
* Ambiente Python 3.6 ou superior.
* Bibliotecas listadas em "Tecnologias Utilizadas" instaladas.

## 🚀 Como Executar

1.  Clone o repositório. 📥
2.  Instale as dependências: `pip install -r requirements.txt` (se você criar um requirements.txt) ou execute os `pip install` do notebook.
3.  Execute o notebook `Imersão_IA_Alura_+_Google_Gemini_Aula_05_Agentes.ipynb` no Google Colab ou em seu ambiente local. 💻
4.  Siga as instruções no notebook para interagir com o sistema de agentes. 🚀

## 📂 Estrutura do Projeto
├── Imersão_IA_Alura_+_Google_Gemini_Aula_05_Agentes.ipynb # Notebook com o código do projeto 📓
└── README.md # Este arquivo 📄


## 🤝 Contribuição

Contribuições são bem-vindas! Se você tiver alguma sugestão de melhoria ou encontrar algum problema, sinta-se à vontade para abrir uma issue 🐛 ou enviar um pull request. 🎁


## 🙏 Agradecimentos

* Alura pela Imersão IA e pelo conteúdo educacional. 💙
* Google pela disponibilização da API Gemini e do ADK. 🚀
