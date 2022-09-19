criando váriaveis:

o termo "const", você usa para criar uma váriavel que não se muda, usamos muito em programação para guardar valores, por ex, se queremos armazenar um nome dentro de uma váriavel, colocamos :
const qualquerNome = "daniel", qualquerNome agora recebe o valor de "daniel", onde você chamar essa váriavel, ela vai ser daniel, é muito útil para mudarmos as propriedades do valor inicial.

o termo "let" é quando a váriavel pode virar outra coisa, como por ex, se temos algo como let qualquerNome = "daniel" e então deficimos mudar o valor, podemos fazer assim:
qualquerNome = "Maria", agora a váriavel troca o nome para "Maria" a const não seria possível, por não muda seu valor inicial.

funções servem para executar um bloco de codigo, elas começão com a palavra "function" e em seguida tem um nome qualquer, os () são onde passamos parametros caso necessário e ela pode ou não retornar algo,
lembre-se que serve para executar alguma coisa, não precisa ter "return" sempre, depende do que quer fazer.

arrays são como uma lista, tudo dentro é separado por "," e cada item dentro tem uma posição, começando sempre por 0, ou seja, se termos o array  de strings const arrayQualquer = ["olá", "oi", "xau"] e queremos pegar o primeiro item,
basta chamarmos a posição desejada, se queremos o "olá", ele se encontra na posição 0 do arrayQualquer, que ficaria assim arrayQualquer[0] e ele vai devolver o "olá"

para objetos, ele guardam várias informações que você pode definir como quiser, pegamos como exemplo o objeto: const qualquerObjeto = { name: "Maria", age: 30 }, para acessarmos o name dentro do objeto, basta 
chamarmos assim qualquerObjeto.name ou qualquerObjeto["name"] e vai retornar o nome.

usamos o console.log() para ver os resultados no console, invocar funções e testes, você vai usar nos próximos testes.

muitas funções dos testes precisam de parametros, forneça eles para que as funções tenham valores, você também pode colocar console.log() dentro das funções para ver qualquer váriavel dentro da função, por ex:

function algumaCoisa(parametro) {
  console.log(parametro)
}

ao invocar essa função, por ex, console.log(algumaCoisa("Maria")) vai aparecer no console Maria, pois a função foi invocada no console.log com o parametro em formato de string "Maria" a

String são tudo que são palavras, basicamente sempre tem aspas entre o valor, ou seja, para Daniel virar uma string, basta colocar "Daniel"
Number são números, mas é possível colocar aspas também, logo eles vão virar strings, tudo dentro de "" vira uma string, mesmo que seja um número