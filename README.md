# Atividades Interativas — Lógica e Linguagem de Programação

Páginas interativas dos **Registros de Aula** da disciplina *Lógica e
Linguagem de Programação*, com diagramas explicativos, passo a passo guiado,
formulário preenchível e geração do relatório em PDF direto pelo navegador.

**Acesso:** https://olisam2303-ux.github.io/atividades-interativas-logica/

## O que cada página tem

- **Cenário** da atividade, como aparece no AVA
- **Objetivos de aprendizagem** e **referências**, retirados do capítulo
  correspondente da apostila da disciplina
- **Diagramas** (SVG, desenhados na própria página) explicando o conceito —
  entrada/processamento/saída, cascatas de SE/SENÃO, faixas de classificação
- **Esqueleto de pseudocódigo com lacunas** ao lado do campo onde o aluno
  escreve a versão dele
- **Passo a passo guiado**, com dica de "como pensar" em cada etapa
- **Formulário** com os campos do registro, salvo automaticamente no navegador
- **Botão "Gerar PDF da resposta"**, que monta o relatório no padrão de
  roteiro de aula prática (capa, folha de rosto, objetivos, procedimentos,
  respostas do grupo, checklist e referências) para o aluno salvar e enviar
  no AVA

## Conteúdo

| Semana | Atividade | Base |
|---|---|---|
| 1 | Criando seu primeiro algoritmo | Cap. 1 — O que é programação |
| 2 | Sistema de vendas | Cap. 14 a 16 — SE / SENÃO / SENÃO SE |
| 3 | Sistema de classificação de idade | Cap. 16 — SE / SENÃO SE / SENÃO |
| 4 | Melhoria contínua na prática: operadores relacionais | Cap. 12 — Comparações |
| 5 | Calculadora de média com verificação de aprovação | Cap. 14 — SE |
| 6 | Projeto guiado: simulador de desconto por idade | Cap. 12 e 15 — SE e SENÃO |
| 7 | Venda para um e-commerce de atacado | Cap. 15 — SE e SENÃO |

### 2º bimestre

| Semana | Atividade | Ferramenta |
|---|---|---|
| 8 | O detetive de bugs: encontrando e corrigindo um loop infinito | Visualg |
| 9 | Programando o Robô Chef: sua primeira receita com for | Google Colab (Python) |
| 10 | Detetives de performance (O(n²) x O(n)) | Teste de mesa |
| 11 | Ordenando listas com Bubble Sort | Teste de mesa |
| 12 | Desafio: Jogo da Velha (matriz 3×3 e trincas) | Modelagem em texto |
| 13 | Boas práticas de nomeação (refatoração de funções) | Python |
| 14 | Gerenciador de tarefas em dois módulos | Python |

### 3º bimestre

| Semana | Atividade | Ferramenta |
|---|---|---|
| 15 | Percurso sequencial de vetores *(prática guiada A2)* | Python |
| 15 | Investigando dados: média, busca e listas *(prática guiada A3)* | Python |
| 15 | Sistema de análise de notas da turma *(registro A4)* | Python |
| 16 | Aninhando laços para percorrer matrizes *(prática guiada A2)* | Python |
| 16 | Agregando dados em matrizes *(prática guiada A3)* | Python |
| 16 | Miniprojeto: Planilha de vendas *(registro A4)* | Python |
| 17 | Revisão por pares e feedback assertivo | Revisão em dupla |
| 18 | Técnicas básicas de depuração *(registro A3)* | Depurador da IDE |
| 18 | Mini-kata TDD: Calculadora *(A4)* | Python |
| 19 | Slicing e formatação com f-strings *(prática guiada A3)* | Python |
| 19 | Parsing de logs: desafio de automação SOC *(registro A4)* | Python |
| 20 | Gerador de relatório de estoque *(prática guiada A3)* | Python |
| 20 | Integrador de dados com planilhas *(registro A4)* | Python + csv |

## Procedência do material

Nem toda semana da SEDUC-SP tem roteiro de atividade prática publicado, e
alguns dos que existem trazem inconsistências. Onde foi preciso completar ou
corrigir alguma coisa, a página diz exatamente o quê, num bloco
**"Procedência deste material"** que separa o que veio do material oficial do
que foi construído aqui — e que sai também no PDF gerado pelo aluno.

| Semana | O que aconteceu |
|---|---|
| 1 | O enunciado pede "considere possíveis problemas" sem dizer o que vale como resposta; os critérios de aceitação foram definidos aqui. |
| 2 | O card fala em "código", o roteiro pede pseudocódigo — a página adota o pseudocódigo, que é o que a semana ensina. |
| 3 | O enunciado não define entrega; formato, nome de arquivo e conteúdo obrigatório foram definidos aqui. |
| 4 | O roteiro nunca foi disponibilizado. A atividade foi escrita a partir do tema oficial da aula e da situação-problema da própria aula (a autoescola). |
| 5 | O enunciado oficial pede só a mensagem "Aprovado"; aqui o SENÃO é obrigatório e vale nota. |
| 6 | O roteiro nunca foi disponibilizado — e o card repete, por engano, o título da Semana 4. O projeto foi montado a partir das três aulas da semana e das suas questões "Pause e responda". |
| 9, 10, 12 | A lista de materiais do card não corresponde à ferramenta que o roteiro pede; cada página diz qual vale. |
| 14 | O card vem com o título de outra atividade (retrospectiva de Sprint) e o roteiro cita blocos de código que não foram incluídos; o código de referência foi escrito para preencher a lacuna. |
| 19 | O roteiro erra a régua de índices da string; a página traz a régua correta (0 a 16 e −1 a −17, para 17 caracteres). |
| 20 | Os roteiros mandam ler os arquivos `estoque.csv` e `funcionarios.csv` sem fornecê-los; ambos foram gerados a partir das tabelas dos próprios roteiros e estão em [`arquivos/`](arquivos), além de embutidos nas páginas para copiar ou baixar. |

## Como usar

Cada arquivo `.html` é autocontido: funciona offline, sem instalar nada e sem
depender de servidor. Dá para abrir pelo link acima, baixar o repositório em
`.zip` e abrir por duplo clique, ou distribuir um arquivo avulso para a turma.

O que o aluno digita fica salvo apenas no navegador dele (`localStorage`) —
nada é enviado para lugar nenhum automaticamente.

---

Cenários baseados nos Registros de Aula da SEDUC-SP, ampliados com o passo a
passo, os diagramas e os critérios de avaliação da apostila da disciplina.
