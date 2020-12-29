### Design Patterns na prática

Design Patterns são soluções para os problemas de design de software que você encontra repetidamente no desenvolvimento de aplicativos no mundo real. Padrões são sobre projetos reutilizáveis e interações de objetos.

Esses conceitos ficaram realmente conhecidos em 1994, quando os engenheiros de software Erich Gamma, Richard Helm, Ralph Johnson e John Vlissides escreveram o livro **“Design Patterns: Elements of Reusable Object-Oriented Software”** com o objetivo de catalogar problemas comuns aos projetos de desenvolvimento de software e as formas de resolver esses problemas. Os autores catalogaram 23 padrões que utilizaram ao longo de suas carreiras.

Os 23 padrões de Gang of Four (GoF) são geralmente considerados a base para todos os outros padrões. Eles são classificados em três grupos: Creational, Structural, and Behavioral.



![](https://miro.medium.com/max/875/0*OFt61YRnYTkCkuKX.jpeg)

No curso da plataforma da DIO,  ministrado por Victor Fructuoso, Manager da Avanade, foram apresentados na prática, alguns destes padrões, tendo como base processos do Detran, programados em C#:

#### Strategy

O padrão Strategy serve para “definir uma família de algoritmos, encapsular cada uma delas e torná-las intercambiáveis. Strategy permite que o algoritmo varie independentemente dos clientes que o utilizam” (como definido no livro do GoF).

Em outras palavras, Strategy nos permite configurar uma classe com um de vários comportamentos, utilizando o conceito de OO chamado de composição.

#### Factory

Factory, um padrão que fornece a possibilidade de criarmos uma fabrica para criação dos nossos objetos em tempo de execução, deixando o cliente isento de instanciar a classe ganhando um dinamismo para a aplicação.

#### Template

O pattern template method é muito simples, é como se ele montasse o esqueleto de um algoritmo de uma forma abstrata, e deixasse para que as classes concretas realizem as devidas implementações. O Template Method utiliza uma classe abstrata base, que vai encapsular o template do algoritmo em um método, para que as classes concretas possam herdar desta classe e realizar a implementação de determinados passos deste algoritmo.

#### Decorator

O padrão Decorator permite que se adicione funcionalidades a um objeto dinamicamente. Em outras palavras, o cliente tem a liberdade de criar um objeto e então extendê-lo, adicionando uma variedade de  “features” nele.

#### Singleton 

O Padrão Singleton tem como definição garantir que uma classe tenha apenas uma instância de si mesma e que forneça um ponto global de acesso a ela. Ou seja, uma classe gerencia a própria instância dela além de evitar que qualquer outra classe crie uma instância dela. Para criar a instancia tem-se que passar pela classe obrigatoriamente, nenhuma outra classe pode instanciar ela. O Padrão Singleton também oferece um ponto global de acesso a sua instância. A própria classe sempre vai oferecer a própria instância dela e caso não tenha ainda uma instância, então ela mesma cria e retorna essa nova instância criada.






