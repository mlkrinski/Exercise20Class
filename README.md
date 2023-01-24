# Exercise20Class

# Exercício 20

Crie um conjunto de classes em javascript para auxiliar na interação com o DOM.

Você deverá criar, no mínimo, 4 classes diferentes:

- Uma classe para um elemento genérico do DOM (dica: utilize o nome **Component**, pois o nome Element poderá gerar conflitos com a implementação do navegador).
  - Essa classe deverá possuir um atributo privado para armazenar a referência ao elemento do DOM e um método de acesso para ler o valor desse atributo.
  - Ela também deve possuir um método _build_ para criar o elemento que deve ser chamado uma vez no construtor, mas também deve ser possível chamá-lo novamente através da instância.
  - Ela também deve possuir um método _render_ para adicionar o elemento na página que poderá ser chamado pela instância a qualquer momento.
- Uma classe específica para elementos **input**, que deve ser uma subclasse da classe Component.
- Uma classe específica para elementos **label**, que deve ser uma subclasse da classe Component e no seu construtor deve ser possível indicar como primeiro parâmetro qual será o seu conteúdo em texto.
- Uma classe específica para elementos **form**, que deve ser uma subclasse da classe Component e possuir um método para adicionar elementos como filhos (através das instâncias das classes Component e suas subclasses).
