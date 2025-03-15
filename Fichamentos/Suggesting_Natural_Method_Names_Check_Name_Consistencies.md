# Suggesting Natural Method Names to Check Name Consistencies

	
## Fichamento de conteúdo

O projeto é uma pesquisa na área de engenharia de software, sendo responsável por esse trabalho Son Nguyen, Hung Phan, Trinh Le, e Tien N. Nguyen. Este artigo tem em foco uma ferramenta chamada *MNIRE* que utiliza aprendizagem de máquina para sugerir nomes aos programadores. Ele utiliza 3 regras sendo elas contexto de implementação, interface e classe envolvente. Utilizando a ideia de gerar um nome para o método como um resumo abstrato de texto, ele utiliza o modelo *Encoder-Decoder* que se baseia em aprendizagem profunda. Foi utilizado 14 milhões de métodos em 14 mil projetos de código aberto do *GitHub* e perceberam que 62,9% dos nomes de métodos são únicos, 78,1% indicando que tokens de nomes existentes são reutilizados frequentemente. Além disso foram enviados 50 *pull requests* e 42 desses foram aceitos e 5 com mesclagem direta. E com esses dados foi detectado que o *MNIRE* superou o *Code2vec* melhorando a precisão em 18,2% e com recall em 11%. Sendo assim concluíram que a abordagem baseada na naturalidade dos nomes de entidades melhora a recomendação de nomes de métodos. Sendo mais eficazmente do que abordagens que utilizam apenas estruturas como *AST* (*Abstract Syntax Tree*) ou *PDG* (*Program Dependence Graph*).


## Fichamento Bibliográfico

* Contexto de Implementação diz que inclui variáveis, campos e métodos usados no corpo do método.
* Contexto de Interface considera os tipos de parâmetros e o tipo de retorno do método.
* Contexto de Classe Envolvente analisa o nome da classe à qual o método pertence​


## Fichamento de Citações

* “*Common tokens shared between a method name and the contexts. For a method, we first computed the percentage of the tokens of the method name that also appear in its contexts.*”

* “*We also aim to explore the pervasiveness ofthe sharing tokens between method names and the contexts. Specifically, we calculated the percentages of the methods whose names share certain proportions oftokens with the corresponding contexts.*”

* “*First, to suggest a good name for a method, relying on the naturalness of the program entities in the contexts yields better results than using the AST or PDG structures. Second, method names are quite unique, however, the tokens composing them are repeated frequently. Thus, MNIRE exploits the regularity of the tokens in program entities' names for method name suggestion. Finally, our generative approach is more effective in producing new names than IR-based search approach in a corpus.*”

