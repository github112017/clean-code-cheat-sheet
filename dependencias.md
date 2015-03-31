# Dependências

| Faça dependências lógicas em físicas | + |
|--|
| Se um modulo depende de outro, esta dependência deve ser física e não apenas lógica. Não faça suposições |

| Singletons / Serviço Localizado | - |
|--|
| Use injeção de dependência. Singletons escondem dependências |

| Classe base dependendo de suad derivadas | - |
|--|
| Classe base deve trabalhar com qualquer classe derivada |

| Excesso de informação | - |
|--|
| Minimise a interface para diminuir acoplamento |

| Não sei traduzir este titulo ( Feature Envy ) | - |
|--|
| O método de uma classe deve estar interessado em variáveis e métodos da classe a que pertence e não em variavel e funções de outra classe. Utilizar acessores e modificadores para manipular os dados de algum outro objeto, é ultrapassar o escopo de outro objeto. |

| Acoplamento artificial | - |
|--|
| Coisas que não dependem uma da outra não devem ser acopladas artificialmente |

| Acoplamento temporarios invisíveis | - |
|--|
| Se, por exemplo  a ordem que o método é chamado então é lógico que ele não deve ser chamado na ordem errada |