# Modelo para Apresentação do Lab08 - Modelo Lógico e Análise de Dados em Grafos

Estrutura de pastas:

~~~
├── README.md  <- arquivo apresentando a tarefa
│
└── images     <- arquivos de imagem usados na tarefa
~~~

# Equipe `Os Brabos de Banco de Dados` - `OBBD`
* `Victor Agozzini Scholze` - `206457`
* `Thiago Henrique Da Costa` - `206234`

## Modelo Lógico Combinado do Banco de Dados de Grafos
>
> ![Modelo Lógico de Grafos](images/modelo-logico-grafos.png)

## Perguntas de Pesquisa/Análise Combinadas e Respectivas Análises

>
### Pergunta/Análise 1
> * Quais são os principais locais aonde ocorre queimada?
>   
>   * Conforme feita a coleta dos dados há tendência será de uma ocorrência elevada de queimadas em um mesmo local. Dessa forma, conseguiremos fazer análise de centralidade nestes locais.

### Pergunta/Análise 2
> * Qual o impacto do clima sobre o local da queimada?
>   
>   * Para entendermos melhor a ocorrência das queimadas precisamos entender quais são os principais fatores externos que influenciam nesse aspecto, com isso analisando o modelo lógico de grafos verificamos a importância do clima. Nesse sentido, podemos verificar a grande dependência do clima, sem esta variável não será possível realizar uma análise com exatidão satisfatória. Assim a modalidade de vulnerabilidade se encaixa nessa pergunta.
>   
### Pergunta/Análise 3
> * Pode ocorrer queimadas em determinado local?
>   
>   * Conforme o grafo for crescendo é possível observar determinados padrões. Com isso conseguimos identificar aspectos que influenciam certos tipos de queimadas. De tal forma utilizando predição de links poderemos identificar possíveis queimadas que ocorrerá no local.
