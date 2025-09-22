Processador de Projetos PX
Aplicação web para otimizar o fluxo de trabalho das equipes da Parex Engenharia, automatizando a extração e verificação de dados em projetos de montagem de estruturas.

Sobre o Projeto
A extração e conferência manual de TAGs de peças em centenas de folhas de projetos PDF é um processo demorado, repetitivo e suscetível a erros. O Processador de Projetos PX foi desenvolvido para solucionar este problema, oferecendo uma ferramenta web que automatiza essas tarefas, garantindo mais agilidade, precisão e eficiência para as equipes de engenharia.

A aplicação opera inteiramente no navegador do usuário, garantindo que os dados e os arquivos de projeto permaneçam seguros e privados.

Funcionalidades Principais
O processador é dividido em duas funções principais:

1. Extração de TAGs para Excel
Esta função lê múltiplos arquivos PDF de projetos, identifica todas as TAGs de peças e as consolida em uma única planilha Excel.

Upload em Lote: Envie vários arquivos PDF de uma só vez.

Identificação Automática: O sistema varre os documentos e encontra as TAGs no formato padrão (ex: 72ED01F3840B).

Geração de Planilha: Exporta um arquivo .xlsx com duas colunas: "Nome da Estrutura" (baseado no nome do arquivo PDF) e "TAG".

2. Pintar TAGs no PDF (Verificação)
Esta função utiliza uma planilha Excel como referência para encontrar e destacar TAGs específicas dentro dos arquivos PDF, servindo como uma poderosa ferramenta de conferência visual.

Referência via Excel: Faça o upload dos PDFs e da planilha gerada na Função 1 (ou uma planilha customizada).

Destaque Visual: As TAGs encontradas são pintadas com um fundo verde para fácil identificação.

Controle de Quantidade: Se a planilha tiver uma coluna "Quantidade", a ferramenta pintará a TAG apenas o número de vezes especificado, permitindo auditorias precisas.

Suporte a Rotação: O destaque funciona corretamente mesmo em TAGs na vertical, horizontal ou em ângulo.

Exportação: Baixe as versões dos PDFs com as marcações visuais aplicadas.

Tecnologias Utilizadas
Frontend: HTML5, Tailwind CSS, JavaScript (Vanilla)

Manipulação de PDF: PDF.js e pdf-lib

Manipulação de Excel: SheetJS (xlsx)
