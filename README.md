<div>
  <h3 align="center">
  <img align="center" alt="Intellij" height="40" width="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/intellij/intellij-original.svg" />
   DEFINIÇÃO E CONSTRUÇÃO <img align="center" alt="Kotlin" height="80" width="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kotlin/kotlin-original-wordmark.svg" /></h3>
</div>

<h4>➡️Em relação ao uso de classes em Kotlin, é importante ressaltar as seguintes características:</h4>

Definem propriedades para armazenar valores.
Definem métodos para fornecer funcionalidades.
Definem inicializadores para configurar seu estado inicial.
Podem ser estendidas para expandir suas funcionalidades, além das presentes em suas implementações.
Trabalham com herança, o que permite que uma classe possa herdar as características de outra.
Type casting, que lhe permite checar e interpretar uma classe como sendo outra.
Para criar uma classe, deve ser utilizada a palavra reservada class, seguida do nome da classe (iniciando em
maiúsculo) e sua implementação entre chaves ({ }). Veja o exemplo de criação de uma classe chamada Person no
Código-fonte “Classes”.
A classe Person representa uma pessoa e possui as propriedades name, isMale e age, que armazenam o nome,
o sexo (se for true significa que é masculino) e a idade. Em uma classe, as propriedades que armazenam um
conteúdo também são chamadas de propriedades armazenadas.
Toda classe necessita de um método construtor (ou método inicializador) para criar uma instância daquela
classe (também chamada de objeto).

⭐DICA: Dentro de classes, as funções passam a ser chamadas de métodos, e as variáveis são chamadas de
propriedades.

O método construtor cria uma instância daquela classe e tem por obrigação alimentar qualquer propriedade
que não tenha sido inicializada. No exemplo desenvolvido, a propriedade age é a única que foi definida e já
inicializada com um valor (0). As demais (name e isMale) precisam ser inicializadas, e cabe ao método
construtor efetuar essa tarefa, então é por isso que o construtor solicita dois parâmetros, name e isMale,
que serão repassados às respectivas propriedades. Vale ressaltar que o nome dos parâmetros não precisa,
necessariamente, ser o mesmo.
A nossa classe Person possui dois métodos: o introduce(), que serve para retornar a apresentação da pessoa,
e o speak(sentence: String), que faz com que a pessoa fale algo. Nesse método, será incluída uma regra
informando que uma pessoa com menos de três anos só fala “gugu dada”.
Para instanciarmos uma classe, criamos uma variável e atribuímos a ela a chamada do método construtor da
classe que desejamos. Para chamarmos o método construtor, usamos apenas o nome da classe, passando os
valores dos parâmetros do método.
