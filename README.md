# Eng Soft Continua Experimental

Simulados interativos para estudo e revisão da P1 e da P2 de Engenharia de Software Contínua Experimental.

## Estrutura do site

- `index.html`: página inicial, que explica o objetivo do material e guia o aluno para o simulado da P1 ou da P2.
- `P1/simulado.html`: simulado da P1 (validação de requisitos de software e métricas de qualidade de software), com questões baseadas nos livros da pasta `P1/`.
- `P2/simulado.html`: simulado da P2 (reúso de software, rastreabilidade de requisitos, lições aprendidas em projetos de TI, linguagens formais e autômatos, e técnicas de qualidade de software), com questões baseadas nos livros da pasta `P2/`.
- `P1/figuras/` e `P2/figuras/`: figuras, quadros e diagramas recortados diretamente dos PDFs de apoio, usados nas questões que reproduzem exemplos e ilustrações originais dos livros.
- `P1/*.pdf`, `P2/*.pdf`, `Eng Soft Cont Experimental.xlsx`: materiais de apoio e fontes de estudo da disciplina (não versionados no repositório, ver `.gitignore`).

## Objetivo

Como a disciplina é oferecida em formato EAD, as provas de P1 e P2 seguem de perto o conteúdo dos livros/apostilas usados no curso. Os simulados foram feitos para ajudar o aluno a entender a **estrutura de cada prova** — os temas cobrados e o formato das questões — e não para substituir o estudo dos livros.

Sempre que possível, as questões:

- reaproveitam **figuras, quadros e diagramas originais** dos livros (recortados dos PDFs de apoio);
- reproduzem **enunciados e exemplos** próximos do texto original, citando obra e página;
- indicam as **referências bibliográficas** completas ao final de cada simulado.

## Funcionalidades

- Questões objetivas com gabarito automático (8 delas, em cada prova, trazem a figura/quadro original do livro e a citação da fonte).
- Questões discursivas de treino, com correção parcial por palavras-chave.
- Campo para identificação do aluno e barra de progresso.
- Relatório final em nova aba, editável, com pontuação e feedback por questão.
- Botão para gerar PDF (impressão) do relatório, para entrega no AVA.

## Como usar

1. Abra `index.html` em um navegador e escolha o simulado da P1 ou da P2.
2. Digite o nome do aluno e responda às questões objetivas e discursivas.
3. Clique em **Finalizar simulado**.
4. Revise o relatório gerado na nova aba (o texto é editável).
5. Clique em **Gerar PDF para o AVA** e salve como PDF.

## Sobre as figuras e referências

As figuras usadas nas questões foram recortadas manualmente das páginas dos PDFs de apoio (pastas `P1/` e `P2/`), escolhendo diagramas, quadros e exemplos que já tinham citação de fonte no material original (unidades de aprendizagem da plataforma SAGAH usadas na disciplina). Cada simulado lista, ao final da página, as referências completas dos livros usados nas questões com figura.

Como as pastas P1 e P2 contêm PDFs diferentes — a P1 cobre apenas validação de requisitos e métricas de qualidade, enquanto a P2 cobre os cinco temas do semestre —, cada simulado tem 30 questões (20 objetivas + 10 discursivas), com os temas da P1 concentrados em duas apostilas e os da P2 distribuídos entre as cinco.

**Escopo atual:** 8 das 20 questões objetivas de cada prova trazem figura/quadro original e enunciado próximo do livro; as demais questões objetivas e todas as discursivas são conceituais (sem figura), no mesmo estilo. Ampliar a cobertura de figuras/enunciados originais para mais questões é um possível próximo passo, dado o volume de curadoria manual necessário (os PDFs de apoio são recortes escaneados dos livros, sem texto pesquisável, então cada figura precisa ser localizada e recortada visualmente).

## Observação

A correção das questões discursivas é apenas uma triagem automática baseada em palavras-chave. A revisão manual do professor continua sendo recomendada antes de considerar a nota final. Da mesma forma, edição/ano de publicação das apostilas SAGAH não puderam ser confirmados nos exemplares digitais consultados — as referências indicam isso explicitamente.
