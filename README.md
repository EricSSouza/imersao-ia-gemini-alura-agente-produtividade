# Agente de Produtividade Pessoal com Gemini

Este projeto foi desenvolvido como parte da Imersão IA do Google com Gemini e Alura.
O objetivo é criar um agente de IA que auxilie o usuário a organizar seu dia, definir tarefas com base em seus objetivos e oferecer dicas.

## Sobre o Projeto

O "Agente de Produtividade Pessoal" visa ser um assistente virtual que:
- Ajuda a decompor objetivos maiores em tarefas menores.
- Sugere os próximos passos para alcançar uma meta diária.
- (Funcionalidade futura) Oferece dicas personalizadas com base nas dificuldades apresentadas pelo usuário.

## Como Executar

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/EricSSouza/agente-de-produtividade.git
    cd agente-de-produtividade
    ```
2.  **Abra o Notebook:**
    O projeto principal está no arquivo `agente_produtividade.ipynb`. Abra-o no Google Colab ou em um ambiente Jupyter local.
3.  **Configure sua API Key do Gemini:**
    *   Obtenha sua API Key do [Google AI Studio](https://makersuite.google.com/app/apikey) (ou conforme as instruções da imersão).
    *   No Google Colab, adicione a chave aos "Segredos" (ícone de chave 🔑 na barra lateral esquerda):
        *   Nome do segredo: `GEMINI_API_KEY`
        *   Valor: `SUA_API_KEY_AQUI`
4.  **Execute as Células:**
    Execute as células do notebook em ordem. A primeira célula instalará as dependências, e as seguintes configurarão a API e iniciarão a interação com o agente.

## Tecnologias Utilizadas

-   Python
-   Google Gemini API (via `google-generativeai`)
-   Google Colab

## Autor

-   Eric S. Souza - [http://github.com/EricSSouza](http://github.com/EricSSouza)

## Desafios e Próximos Passos (Se Aplicável)
*(Esta seção pode ser atualizada conforme o desenvolvimento ou se enfrentar problemas como o da quota)*

-   **Desafio Atual:** Gerenciamento de quotas da API do Gemini.
-   **Próximos Passos Planejados:**
    -   Implementar um loop de conversa mais interativo.
    -   Permitir que o usuário relate dificuldades e receba dicas personalizadas.
    -   (Opcional) Salvar o histórico de objetivos e progresso.
