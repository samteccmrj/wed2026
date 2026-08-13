[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

# Formação Docente para o Uso Pedagógico da Inteligência Artificial

---

## Descrição Geral do Artigo

Este repositório apresenta os dados anonimizados, códigos e análises utilizados no estudo **“Formação docente para o uso pedagógico da Inteligência Artificial: relato de experiência de um workshop na Educação Básica”**.

O estudo relata e analisa a experiência do **Workshop de Educação Digital**, realizado em 2026 no **Colégio Militar do Rio de Janeiro (CMRJ)**, com a participação de **84 agentes de ensino e professores da Educação Básica**, atuantes nos anos finais do Ensino Fundamental II e no Ensino Médio.

A formação teve duração de **120 minutos** e foi estruturada a partir da exploração prática de recursos de Inteligência Artificial aplicados ao cotidiano docente, utilizando a plataforma **Teachy**.

---

## Objetivo do Estudo

O estudo teve como objetivo relatar e analisar a experiência de realização do Workshop de Educação Digital, investigando as percepções dos participantes acerca da utilidade, clareza e aplicabilidade pedagógica dos recursos apresentados, bem como identificar potencialidades, limitações e oportunidades de aprimoramento da formação.

Foram estabelecidas duas questões de pesquisa:

**QP1:** Como os participantes avaliaram o Workshop de Educação Digital quanto à utilidade das ferramentas de IA, clareza das atividades, contribuição para o planejamento pedagógico, interesse pelo uso de IA e potencial de otimização do tempo docente?

**QP2:** Quais potencialidades, limitações e oportunidades de aprimoramento da formação docente para o uso pedagógico da IA emergiram das percepções dos participantes?

---

## Organização do Workshop

O workshop foi realizado em um único encontro de 120 minutos, com atividades práticas relacionadas à utilização de recursos de IA no contexto educacional.

Durante a formação, foram exploradas funcionalidades da plataforma Teachy relacionadas a:

* Elaboração de apresentações de slides;
* Elaboração de Plano Educacional Individualizado (PEI);
* Planejamento de aulas;
* Elaboração de questionários;
* Exploração de recursos relacionados à Base Nacional Comum Curricular (BNCC).

A proposta buscou aproximar a utilização da Inteligência Artificial de atividades características do planejamento e da prática docente.

---

## Instrumento de Avaliação

Ao final do workshop, foi aplicado um questionário por meio do **Google Forms**, composto por cinco itens fechados e uma questão aberta.

Os itens quantitativos utilizaram uma escala Likert de cinco pontos:

* 1 — Discordo totalmente;
* 2 — Discordo;
* 3 — Nem concordo nem discordo;
* 4 — Concordo;
* 5 — Concordo totalmente.

As cinco dimensões avaliadas foram:

| Item | Dimensão avaliada                                      |
| ---- | ------------------------------------------------------ |
| `Q1` | Utilidade das ferramentas de IA para a prática docente |
| `Q2` | Clareza das atividades práticas                        |
| `Q3` | Contribuição para o planejamento pedagógico            |
| `Q4` | Interesse pelo uso de IA na educação                   |
| `Q5` | Potencial de otimização do tempo docente               |

A questão aberta permitiu o registro de sugestões e comentários sobre a experiência formativa.

---

## Estrutura do Repositório

```text
├── LICENSE
│
├── README.md
│
├── wed2026.ipynb
│
└── wed2026.xlsx
```

> Os nomes dos arquivos podem ser ajustados de acordo com a organização final do repositório.

---

## Dataset

O conjunto de dados disponibilizado contém **84 registros** e foi preparado para permitir a reprodução das análises apresentadas no estudo sem disponibilizar identificadores pessoais ou as manifestações qualitativas originais.

Entre as principais variáveis encontram-se:

| Variável                 | Descrição                                                             |
| ------------------------ | --------------------------------------------------------------------- |
| `codigo`                 | Identificador anônimo do participante                                 |
| `ano_escolar`            | Ano escolar ou função do participante                                 |
| `Q1` a `Q5`              | Respostas aos cinco itens da escala Likert                            |
| `comentario_anonimizado` | Paráfrase anonimizada da manifestação qualitativa                     |
| `conteudo_analisavel`    | Indica se a resposta apresentou conteúdo passível de análise temática |
| `valencia`               | Valência geral da manifestação                                        |
| `codigos_tematicos`      | Código(s) atribuído(s) durante a análise temática                     |
| `categorias_tematicas`   | Categoria(s) temática(s) resultante(s) da análise                     |

### Dados Qualitativos

Por razões de privacidade, **as respostas textuais originais à questão aberta não são disponibilizadas publicamente**.

O dataset contém paráfrases anonimizadas das manifestações, elaboradas de modo a preservar seu conteúdo analítico e sua valência, reduzindo o risco de identificação dos participantes ou de exposição de informações contextuais não necessárias à reprodução das análises.

A codificação temática foi realizada pelos pesquisadores previamente à preparação do conjunto de dados público.

---

## Análises Realizadas

O notebook disponibilizado no repositório permite reproduzir as principais análises apresentadas no estudo, incluindo:

* Caracterização dos participantes;
* Frequências absolutas e relativas;
* Média e desvio-padrão;
* Mediana e intervalo interquartil;
* Percentual de concordância (Top-2 Box);
* Distribuição das respostas na escala Likert;
* Alfa de Cronbach;
* Correlação item-total corrigida;
* Correlações de Spearman;
* Análise da concentração das respostas nas categorias superiores da escala;
* Frequência dos códigos temáticos;
* Frequência das categorias temáticas;
* Integração entre resultados quantitativos e qualitativos.

---

## Principais Resultados

A avaliação do workshop foi predominantemente favorável. As médias dos cinco itens variaram entre **4,58 e 4,96**, enquanto os percentuais de concordância variaram entre **90,5% e 100%**.

A clareza das atividades apresentou o resultado mais elevado, com média de **4,96** e **100% de concordância**.

Os cinco itens apresentaram boa consistência interna:

**Alfa de Cronbach = 0,856**

A análise qualitativa identificou quatro categorias principais:

| Categoria temática                                          | Participantes | % das respostas analisáveis |
| ----------------------------------------------------------- | ------------: | --------------------------: |
| Avaliação e características da experiência formativa        |            28 |                       46,7% |
| Ampliação e contextualização das possibilidades pedagógicas |            17 |                       28,3% |
| Continuidade e aprofundamento da formação                   |            12 |                       20,0% |
| Condições de realização e acesso                            |             7 |                       11,7% |

> Uma mesma manifestação poderia pertencer a mais de uma categoria; portanto, os percentuais não somam necessariamente 100%.

Os resultados indicam que uma experiência formativa de curta duração e orientada à experimentação prática pode constituir uma estratégia introdutória para aproximar docentes das possibilidades pedagógicas da Inteligência Artificial, ao mesmo tempo em que evidencia demandas por continuidade, aprofundamento e contextualização das atividades.

---

## Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/samteccmrj/wed2026.git
```

### 2. Instale as dependências

```bash
pip install pandas numpy scipy matplotlib openpyxl
```

### 3. Execute o notebook

O arquivo `wed2026.ipynb` pode ser executado localmente utilizando Jupyter Notebook/JupyterLab ou diretamente no **Google Colab**.

O notebook utiliza o dataset anonimizado disponibilizado neste repositório como fonte para reprodução das análises.

---

## Considerações Éticas

A pesquisa envolveu agentes de ensino e professores da Educação Básica em contexto de formação continuada institucional.

A participação foi voluntária, mediante concordância com o **Termo de Consentimento Livre e Esclarecido (TCLE)**, e os dados foram anonimizados antes das análises, preservando a privacidade dos participantes.

O estudo observou as diretrizes da **Resolução CNS nº 510/2016**.

Para disponibilização pública, foi produzido um conjunto de dados sem identificadores pessoais. As manifestações qualitativas originais não são disponibilizadas, sendo substituídas por paráfrases anonimizadas que preservam seu conteúdo analítico e sua valência.

---

## Uso de Inteligência Artificial

Ferramentas de Inteligência Artificial Generativa foram utilizadas como apoio à elaboração de códigos para análise dos dados, à organização do processo analítico, à revisão linguística e ao aprimoramento da redação do manuscrito.

A codificação dos dados qualitativos, as decisões metodológicas, a análise crítica e a interpretação dos resultados foram realizadas pelos autores. Todas as sugestões produzidas com auxílio de IA foram revisadas pelos autores, que assumem integral responsabilidade pelo conteúdo apresentado.

---

## Ciência Aberta

Este repositório busca promover:

* Transparência metodológica;
* Reprodutibilidade das análises;
* Documentação do processo analítico;
* Reutilização dos códigos;
* Replicação do estudo em outros contextos educacionais.

Para preservar a privacidade dos participantes, o princípio de abertura dos dados foi conciliado com a proteção das manifestações qualitativas originais.

---

## Citação

Caso utilize os dados, códigos ou materiais deste repositório em trabalhos acadêmicos, recomenda-se citar o artigo correspondente e o registro do conjunto de dados.

A referência completa e o DOI poderão ser adicionados após a publicação do artigo.

---

## Licença

Os materiais disponibilizados neste repositório estão licenciados sob a **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

A licença permite compartilhamento e adaptação do material, desde que seja fornecida a atribuição apropriada aos autores.

---
