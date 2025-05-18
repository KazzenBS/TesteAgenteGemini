# Criação de Posts para Instagram com Agentes de IA

Este projeto demonstra a criação automatizada de posts para o Instagram utilizando múltiplos agentes de inteligência artificial (IA) e o modelo Gemini do Google. 
O sistema é capaz de buscar tendências, planejar o conteúdo, redigir o post e revisar a qualidade, tudo de forma automatizada.

## Descrição

O notebook `Imersão_IA_Alura_+_Google_Gemini_Aula_05_Agentes_de_IA.ipynb` implementa um fluxo de trabalho com quatro agentes de IA:

1.  **Agente Buscador de Notícias:** Utiliza a busca do Google para encontrar notícias recentes e relevantes sobre um tópico específico.
2.  **Agente Planejador de Posts:** Analisa as notícias encontradas e cria um plano de conteúdo detalhado para um post no Instagram, definindo o tema, os pontos relevantes e a estrutura do post.
3.  **Agente Redator do Post:** Escreve um rascunho do post para o Instagram, seguindo o plano gerado pelo Agente Planejador. O post é criado com uma linguagem engajadora e apropriada para a plataforma.
4.  **Agente Revisor de Qualidade:** Revisa o rascunho do post, verificando clareza, concisão, correção e tom. Fornece feedback ou aprova o post para publicação.

O sistema permite que o usuário forneça um tópico e, em seguida, os agentes trabalham em conjunto para gerar um post completo e revisado.

## Como Usar

1.  **Pré-requisitos:**

    * Conta Google Cloud com acesso à API Gemini.
    * Chave da API do Google GenAI configurada no Google Colab (ou em seu ambiente local).
    * Python 3.7 ou superior.
    * Bibliotecas Python: `google-genai`, `google-adk`, `IPython`, `requests`.

2.  **Configuração:**

    * Abra o notebook `Imersão_IA_Alura_+_Google_Gemini_Aula_05_Agentes_de_IA.ipynb` no Google Colab ou em seu ambiente Jupyter.
    * Certifique-se de que a variável de ambiente `GOOGLE_API_KEY` esteja configurada com sua chave da API. No Colab, você pode usar `google.colab.userdata`.
    * Execute a célula que instala as bibliotecas necessárias (`%pip install -q google-adk`).

3.  **Execução:**

    * Execute as células do notebook sequencialmente.
    * Quando solicitado, digite o tópico sobre o qual você deseja criar o post.
    * O sistema de agentes irá gerar e exibir os resultados de cada agente (busca de notícias, plano de post, rascunho e revisão final).

## Estrutura do Código

O código é organizado em células em um notebook Jupyter:

* **Células 1-3:** Instalação das bibliotecas e configuração da API Gemini.
* **Células 4-6:** Demonstração do uso do Gemini para buscar informações com e sem a ferramenta de busca do Google.
* **Célula 7:** Instalação do framework ADK (Agent Development Kit) do Google.
* **Células 8-10:** Importação das bibliotecas e definição de funções auxiliares para interação com os agentes e formatação de texto.
* **Células 11-14:** Definição das funções que representam cada um dos quatro agentes (buscador, planejador, redator e revisor). Cada função cria um objeto `Agent` com suas respectivas instruções e ferramentas.
* **Célula 15:** Lógica principal do sistema. Obtém o tópico do usuário, instancia os agentes e os executa em sequência para gerar o post final.

## Contribuição

Contribuições são bem-vindas! Se você tiver ideias para melhorar este projeto, como adicionar mais agentes, aprimorar os prompts ou implementar novas funcionalidades, sinta-se à vontade para abrir uma issue ou enviar um pull request.


## Agradecimentos

Agradecimentos à equipe do Google GenAI e à Alura pela inspiração e recursos educacionais.
