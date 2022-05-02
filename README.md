# Data Binding
- Está relacionado a como um componente pode se comunicar entre a parte do template e a parte lógica comportamental.

Instalação
> [Download Node](https://nodejs.org/en/download/)

Comandos para Execução do Projeto
> `Instalação angular`: npm install -g @angular/cli

> `Baixar as dependências`: npm i

> `Executar`: ng serve

## Conceitos
> [`String Interpolation: {{expressao}}`](https://github.com/jcarloscody/angular_data_binding/tree/main/src/app/string-interpolation) está relacionado a como a partir do template eu consido acessar uma variável da classe do componente. 

> [`Property Binding: [atributo]="variavel"`](https://github.com/jcarloscody/angular_data_binding/tree/main/src/app/property-binding) A ideia é associar um atributo de uma tag ao valor de uma variável declarada na classe do componente. 

> [`Event Binding: (evento)="funcao()"`](https://github.com/jcarloscody/angular_data_binding/tree/main/src/app/event-binding) Com este conceito iremos associar eventos do templates a métodos da classe do componentes. 
> - com parâmetro: `(evento)="funcao($event)"`
> - associar evento com o property binding `Two way data binding`: é lincar um atributo de uma tag a um atributo de uma classe do componente ao mesmo tempo que é lincado as mundanças daquele mesmo componente.

> [`Two Way Data Binding: [(ngModel)]="variavel"`](https://github.com/jcarloscody/angular_data_binding/tree/main/src/app/two-way-data-binding) é refletir o valor da variavel para fora, ou seja, para a tag e o valor do evento de uma tag para dentro, ou seja, para a variável da classe. Para este exemplo usaremos o ngModel que vai substituir o uso conjunto do event binding e property binding que fizemos no exemplo anterior.
> - obs: é importante declararmos um name para a tag quando trabalhamos com o [(ngModel)]