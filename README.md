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
| 2 | Sistema de vendas (com frete pela tabela dos Correios) | Cap. 14 a 16 — SE / SENÃO / SENÃO SE |
| 3 | Sistema de classificação de idade | Cap. 16 — SE / SENÃO SE / SENÃO |
| 4 | Melhoria contínua na prática: operadores relacionais | Cap. 12 — Comparações |
| 5 | Integrando estrutura sequencial com o comando SE | Cap. 14 — SE |
| 6 | Projeto guiado: verificador de desconto do Cine Pipoca | Cap. 14 e 15 — SE e SENÃO |
| 7 | Vamos desenvolver uma venda para um e-commerce de atacado! | Cap. 15 — SE e SENÃO |

### 2º bimestre

| Semana | Atividade | Ferramenta |
|---|---|---|
| 8 | O detetive de bugs: encontrando e corrigindo um loop infinito | Visualg ou Bloco de Notas |
| 9 | Programando o Robô Chef: sua primeira receita com for | VS Code + Python |
| 10 | Detetives de performance (O(n²) x O(n)) | Teste de mesa no papel |
| 11 | Ordenando listas com Bubble Sort | Teste de mesa no papel |
| 12 | Desafio: Jogo da Velha (matriz 3×3 e trincas) | Papel ou Bloco de Notas |
| 13 | Boas práticas de nomeação (refatoração de funções) | VS Code + Python |
| 14 | Gerenciador de tarefas em dois módulos | VS Code + Python |

### 3º bimestre

| Semana | Atividade | Ferramenta |
|---|---|---|
| 15 | Percurso sequencial de vetores *(prática guiada A2)* | VS Code + Python |
| 15 | Investigando dados: média, busca e listas *(prática guiada A3)* | VS Code + Python |
| 15 | Sistema de análise de notas da turma *(registro A4)* | VS Code + Python |
| 16 | Aninhando laços para percorrer matrizes *(prática guiada A2)* | VS Code + Python |
| 16 | Agregando dados em matrizes *(prática guiada A3)* | VS Code + Python |
| 16 | Miniprojeto: Planilha de vendas *(registro A4)* | VS Code + Python |
| 17 | Revisão por pares e feedback assertivo | Revisão em dupla |
| 18 | Técnicas básicas de depuração *(registro A3)* | Depurador do VS Code |
| 18 | Mini-kata TDD: Calculadora *(A4)* | VS Code + Python |
| 19 | Slicing e formatação com f-strings *(prática guiada A3)* | VS Code + Python |
| 19 | Parsing de logs: desafio de automação SOC *(registro A4)* | VS Code + Python |
| 20 | Gerador de relatório de estoque *(prática guiada A3)* | VS Code + Python |
| 20 | Integrador de dados com planilhas *(registro A4)* | VS Code + Python (csv) |

## Ferramentas do laboratório

As atividades usam apenas o que está instalado nos computadores da escola e
funciona sem depender da internet:

- **pseudocódigo** → **Visualg** (executa com F9) ou **Bloco de Notas**;
- **Python** → **Visual Studio Code**, com o trabalho salvo no **GitHub**.

O Google Colab, citado em alguns roteiros da SEDUC-SP, é bloqueado pelo firewall
da escola — as páginas indicam o VS Code no lugar, que faz o mesmo e roda offline.

Para a entrega no GitHub há um guia à parte,
[**Salvando seu trabalho no GitHub**](https://olisam2303-ux.github.io/atividades-interativas-logica/github-passo-a-passo.html),
com dois caminhos: pelo VS Code e, quando o Git não estiver instalado, pelo
próprio site, arrastando os arquivos. Ele está linkado no índice e no card de
ferramenta de cada atividade de Python.

Sobre a conta: o guia manda **tentar primeiro o e-mail institucional** e, se a
associação for recusada — que é o que parece acontecer também com o Colab —,
criar um Gmail no formato `<RA>sp@gmail.com`, para que o RA no endereço
identifique de quem é a entrega. Os repositórios são **públicos**, para abrir
pelo link sem convite.

## Como usar

Cada arquivo `.html` é autocontido: funciona offline, sem instalar nada e sem
depender de servidor. Dá para abrir pelo link acima, baixar o repositório em
`.zip` e abrir por duplo clique, ou distribuir um arquivo avulso para a turma.

O que o aluno digita fica salvo apenas no navegador dele (`localStorage`) —
nada é enviado para lugar nenhum automaticamente.

---

Cenários baseados nos Registros de Aula da SEDUC-SP, ampliados com o passo a
passo, os diagramas e os critérios de avaliação da apostila da disciplina.
