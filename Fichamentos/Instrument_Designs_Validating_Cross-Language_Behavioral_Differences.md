# Instrument Designs for Validating Cross-Language Behavioral Differences

--

## Fichamento de conteúdo

O projeto é uma pesquisa na área de engenharia de software, sendo responsável por esse trabalho Nischal Shrestha, Chris Parnin. Esse artigo tem foco em mostrar 3 técnicas as quais vão identificar equívocos cometidos por programadores ao trocarem de linguagens de programação utilizando o que eles chamam de conhecimento passado de outras linguagens, apesar de algumas serem bem diferentes ainda se consegue passar vícios bons e ruins de uma linguagem para outra, sendo elas Multiple Choice, Simple Yes/No, Surprise. Neste estudo foi usado as linguagens Python e R, pois são famosas na época que o artigo foi escrito(2019). Além disso recrutaram 32 participantes graduados em Ciência da Computação tendo eles obtido média 4 numa escala de 5 sendo 1 sem familiaridade com a tecnologia(Python) e 5 muito familiar. No primeiro teste foram feitas 10 perguntas sendo 5 de múltipla escolha e 5 de Sim e Não, no segundo teste foram feitas 12 perguntas para somente 13 estudantes. Em relação aos dados obtidos com isso, foram observados que em perguntas de múltipla escolha, 64% dos participantes erraram as previsões. Já nas perguntas de Sim/Não, a taxa de acerto foi de 78%. As questões de surpresa revelaram que 62% dos participantes ficaram surpresos com as maiores diferenças comportamentais entre Python e R. Os pesquisadores chegaram à conclusão de que para programadores experientes é interessante utilizar conhecimento prévio em outras linguagem, mas é importante ficar atento a pequenas confusões entre elas. Para professores e tutores de ensino vale ressaltar aos alunos os equívocos que geralmente são cometidos ao aprender essa tecnologia o que facilitaria e deixaria mais leve a transição.


## Fichamento Bibliográfico

Multiple Choice(Múltiplas escolhas) significa que só terá múltiplas escolhas nas questões. 
Simple Yes/No(Simples Sim e Não) significa que será um questionário com resposta binária, ou sim ou não.
Surprise(Surpresa) significa que o questionário vai mostrar um comportamento que talvez o programador não saberia que aconteceria com aquela linguagem e quando é surpreendido significa que ele tem expectativas erradas sobre aquela tecnologia.


## Fichamento de Citações

“This can be quite unexpected behavior for a Python programmer who is accustomed to rows with NA being gracefully handled. In both examples, the behavior of the expressions differ across languages, but perhaps some differences are more meaningful than others? While the topic of subsetting with [ is covered in Tidynomicon, the unexpected behavior when using logical indexing is not mentioned.The second expression seems a more worthy addition as it is much more surprising for a Python programmer: “what on earth is happening?”
“In the open responses, P15 expressed “that R looks a bit goofy” and another observed “in R, it’s not specified that ‘A’ is column or not” (P19). We believe participants were confused because the Python code uses a bracket notation whereas R uses a function call.”
“We examined the open responses for those who were surprised and found them saying “I would say the Python one surprised me more... Python is the language I use the least of the two” (P4) and “Pandas locators are magic and always surprise me when they work” (P5).”
“We inspected the open responses for those who weren’t surprised despite a large difference in syntax. P5 explained that the “- notation is often seen for negation, so I guess this makes sense after seeing it” and P12 expressed that “it’s interesting how -A will be understood as removing A column in the df.”
