# Alura C#

## Aprendizado:
- Podemos criar diretórios na raiz de nosso projeto para organizar melhor o código!
- O recurso de possíveis soluções do Visual Studio, acessível pelo atalho CTRL+PONTO;
- Podemos ter vários métodos com o mesmo nome, desde que possuam lista de argumentos diferentes! Estas são as sobrecargas.

- Herança: Aprendemos herança e vimos que, com sua sintaxe bastante simples, ela é importantíssima em qualquer projeto.
- Polimorfismo: Com isso, foi possível tratar objetos do tipo Diretor como Funcionario e evitar repetição de código e várias sobrecargas iguais.
- Modificadores virtual e override: Alguns comportamentos possuem implementações diferentes nas classes derivadas, para resolver este problema basta usarmos métodos virtuais e a sobrescrita.
- base: A classe filha pode fazer referência aos membros da classe base com uso desta palavra reservada

- O modificador de acesso protected;
- Preenchendo construtores da classe base a partir da classe derivada, com a sintaxe public Diretor(string cpf) : base(5000, cpf);
- Classes e métodos abstratos!
- As diferenças entre throw; e throw ex;;
- Como a CLR preenche a propriedade StackTrace;
- O padrão de inner exceptions;
- O terceiro construtor que as exceções devem ter: (string mensagem, Exception excecaoInterna);

- Os comentários de documentação ///;
- O elemento de documentação <summary/>;
- O elemento <param/>;
- O elemento <paramref/>;
- O elemento <exception/>;
- O elemento <see/>.

- O que é o NuGet;
- O comando Install-Package;
- O tipo DateTime;
- O tipo TimeSpan;
- Conhecemos a biblioteca Humanizer.
