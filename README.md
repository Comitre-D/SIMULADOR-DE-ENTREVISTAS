🤖 IA Entrevistador

Simulador de processos seletivos técnicos baseado em inteligência artificial, prompt engineering e técnicas de entrevistas reais.

📌 Sobre o Projeto
IA Entrevistador é um projeto acadêmico que utiliza prompt engineering para criar uma experiência imersiva de entrevista técnica. Ao invés de um sistema tradicional com código, o projeto funciona como um prompt inteligente e autocontido, projetado para ser utilizado diretamente em interfaces de IA generativa (como ChatGPT, Claude, Gemini, etc.).
O objetivo é ajudar estudantes e profissionais a se prepararem para processos seletivos de forma prática, direcionada e realista.

🎯 Funcionalidades

Funcionalidade	Descrição
🎭 Simulação Realista	A IA assume o papel de um recrutador técnico sênior
📊 Avaliação por Critérios	Notas de 0 a 10 com base em Clareza, Profundidade, Aplicação Prática e Coerência Técnica
📈 Progressão de Dificuldade	5 perguntas que evoluem de conceituais a cenários complexos
📝 Feedback Personalizado	Relatório final com pontos fortes, melhorias e dicas de estudo
🏆 Decisão Simulada	Resultado: Aprovado, Aprovado com Ressalvas ou Reprovado
🚀 Como Usar

Passo 1: Acesse uma IA Generativa
Abra qualquer plataforma com acesso a modelos de linguagem (ChatGPT, Claude, Gemini, etc.).

Passo 2: Cole o Prompt
Copie o conteúdo do arquivo ./prompt.md e cole na caixa de mensagem.

Passo 3: Inicie a Entrevista
A IA assumirá o papel de entrevistador. Responda às perguntas uma a uma.

Passo 4: Receba o Feedback
Ao final das 5 perguntas, você receberá uma avaliação completa do seu desempenho.
📁 Estrutura do Projeto
plain
ia-entrevistador/
├── README.md          # Este arquivo
├── prompt.md          # Prompt principal para colar na IA
└── docs/
    └── explicacao.md  # Documentação técnica do prompt
🧠 Técnicas de Prompt Engineering Utilizadas
🎭 Role Prompting: Define uma persona clara (recrutador técnico sênior)
📋 Structured Output: Formato fixo e previsível para as respostas
🚫 Negative Prompting: Restrições do que NÃO fazer (ex: não dar respostas antes da avaliação)
📊 Chain-of-Thought: Progressão lógica e crescente de dificuldade
🎯 Few-Shot Implicit: Critérios de avaliação bem definidos guiam o comportamento da IA
📝 Exemplo de Fluxo
plain
[Usuário] → Cola o prompt

[IA] 👋 Olá! Sou seu entrevistador técnico hoje. 
       Antes de começarmos, por favor, apresente-se e me conte:
       1. Qual área técnica você deseja ser entrevistado?
       2. Qual seu nível de senioridade (Júnior, Pleno ou Sênior)?

[Usuário] → "Sou desenvolvedor backend, nível Pleno"

[IA] → [Pergunta 1 - Fundamentos]
       → [Avaliação: 8/10]
       → [Pergunta 2 - Aplicação Prática]
       → ...
       → [Feedback Final Completo]
🎓 Contexto Acadêmico
Este projeto foi desenvolvido como atividade escolar para a disciplina de [inserir nome da disciplina], com foco em:
Compreensão de Prompt Engineering
Aplicação de IA Generativa em cenários práticos
Simulação de processos seletivos reais
Desenvolvimento de soft skills técnicas
