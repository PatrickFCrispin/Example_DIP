# Example_DIP

Princípio da Inversão da Dependência (DIP), é um principio de POO e design de código e faz parte do SOLID.
-> https://medium.com/desenvolvendo-com-paixao/o-que-%C3%A9-solid-o-guia-completo-para-voc%C3%AA-entender-os-5-princ%C3%ADpios-da-poo-2b937b3fc530

É um dos princípios do SOLID e propõe que módulos (classe ou componente) de alto nível não devem depender de módulos de baixo nível, ambos devem depender de abstrações. Isso significa que ao invés de depender de implementações concretas, o código deve depender de interfaces ou classes abstratas.

Para aplicar esse princípio, é comum a utilização de Injeção de Depêndecia (DI), um design pattern que implementa o DIP ao injetar as dependências de um objeto por meio de um construtor e facilita a Inversão de Controle (IoC) ao permitir que implementações concretas sejam fornecidas de fora ao invés de serem criadas diretamente dentro do próprio módulo.

“Programe para uma interface e não para uma implementação.”.
