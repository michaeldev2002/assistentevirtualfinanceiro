GuiaInvest - Assistente Financeiro com Inteligência Artificial 🤖💰

Bem-vindo ao repositório do GuiaInvest! Este projeto foi desenvolvido como parte do desafio "Construa seu Assistente Virtual com Inteligência Artificial" da DIO.

🎯 O Pitch (Por que este projeto existe?)

O Problema:
A educação financeira ainda é um grande tabu no Brasil. Muitas pessoas têm dificuldade em organizar o próprio orçamento mensal (vivendo no limite ou no vermelho) e têm receio de começar a investir porque o mercado financeiro utiliza uma linguagem complexa, cheia de jargões (o famoso "economês"). Além disso, iniciantes são frequentemente alvos de promessas de dinheiro fácil ou recomendações irresponsáveis na internet.

A Solução:
O GuiaInvest é um assistente virtual educacional movido por Inteligência Artificial (Google Gemini). Ele atua como um mentor financeiro de bolso para iniciantes. Com base em uma base de conhecimento curada e restrita, ele explica conceitos como a Regra 50/30/20, Taxa Selic e a diferença entre Renda Fixa e Variável de forma extremamente didática, paciente e usando analogias do dia a dia.

O Valor Gerado:
O projeto democratiza o acesso à informação financeira de qualidade e segura. Ao travar a IA com prompts rigorosos, garantimos que o assistente não invente informações (alucinações) e não forneça recomendações de compra de ativos, protegendo o usuário enquanto o empodera para tomar suas próprias decisões financeiras com mais clareza e confiança.

📂 Estrutura do Projeto (Os 6 Passos)

Para construir essa solução, o desenvolvimento foi dividido em 6 etapas estruturadas:

Documentação (/docs/documentacao_agente.md): Definição da persona, público-alvo e regras de segurança do assistente.

Base de Conhecimento (/data/base_conhecimento.md): Curadoria dos textos e conceitos financeiros que servem de "cérebro" para a IA.

Prompts (/docs/system_prompt.md): Instruções de sistema que ditam o comportamento do bot, garantindo uma linguagem simples e blindando contra dicas de investimento diretas.

Aplicação Funcional (/src/agent.py): Script em Python integrado à API do Google Gemini (gemini-pro/gemini-1.5-flash) capaz de ler os arquivos do repositório e executar o chat no terminal.

Avaliação e Métricas (/docs/avaliacao.md): Bateria de testes documentada provando a eficácia do bot contra alucinações e quebra de regras.

Pitch (Este README): Apresentação do problema, solução e valor do projeto.

🚀 Como testar localmente

Clone o repositório.

Instale a biblioteca do Google Gemini: pip install google-generativeai

Substitua a variável API_KEY no arquivo src/agent.py pela sua chave gerada no Google AI Studio.

Execute o script no terminal: python src/agent.py

Comece a tirar suas dúvidas sobre orçamento ou investimentos!

Desenvolvido durante o Bootcamp da DIO.
