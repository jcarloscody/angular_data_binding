# Data Binding
- Está relacionado a como um componente pode se comunicar entre a parte do template e a parte lógica comportamental.

## Conceitos
> [`String Interpolation: {{expressao}}`](https://github.com/jcarloscody/angular_data_binding/tree/main/src/app/string-interpolation) está relacionado a como a partir do template eu consido acessar uma variável da classe do componente. 

> [`Property Binding: [atributo]="variavel"`](https://github.com/jcarloscody/angular_data_binding/tree/main/src/app/property-binding) A ideia é associar um atributo de uma tag ao valor de uma variável declarada na classe do componente. 

> [`Event Binding: (evento)="funcao()"`](https://github.com/jcarloscody/angular_data_binding/tree/main/src/app/event-binding) Com este conceito iremos associar eventos do templates a métodos da classe do componentes. 
- com parâmetro: `(evento)="funcao($event)"`
- associar evento com o property binding `Two way data binding`: é lincar um atributo de uma tag a um atributo de uma classe do componente ao mesmo tempo que é lincado as mundanças daquele mesmo componente.