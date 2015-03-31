# Dependências

| Excesso de informação | - |
|--|
| Minimize a interface para diminuir acoplamento |

| Classe base dependendo de suas derivadas | - |
|--|
| Classe base deve trabalhar com qualquer classe derivada |

| Singletons / Serviço Localizado | - |
|--|
| Use injeção de dependência. Singletons escondem dependências |

| Acoplamento artificial | - |
|--|
| Coisas que não dependem uma da outra não devem ser acopladas artificialmente |

| Faça dependências lógicas em físicas | + |
|--|
| Se um modulo depende de outro, esta dependência deve ser física e não apenas lógica. Não faça suposições |

| Acoplamento temporário invisível | - |
|--|
| Se, por exemplo a ordem que o método é chamado então é lógico que ele não deve ser chamado na ordem errada |

| ***Não sei traduzir este título*** (Feature Envy) | - |
|--|
| O método de uma classe deve estar interessado em variáveis e métodos da classe a que pertence e não em variável e funções de outra classe. Utilizar assessores e modificadores para manipular os dados de algum outro objeto, é ultrapassar o escopo de outro objeto. |

| Navegação transitiva |-|
|--|
| Aqui conhecido como lei de Deméter, escrevendo código tímido.
Um modulo deve conhecer somente as dependências diretas deste.|