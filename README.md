# EAD3010

1. Como você montou a estrutura básica do arquivo index.html? Explique a função de <!DOCTYPE html>, <html>, <head> e <body>.
Iniciei o arquivo com a declaração <!DOCTYPE html> para informar ao navegador que estou utilizando a versão mais recente, o HTML5. Em seguida, utilizei a tag <html> para englobar todo o documento e definir o idioma principal. Dentro dela, dividi o código entre o <head>, que contém as configurações ocultas da página, e o <body>, onde coloquei todo o conteúdo visível, como o título <h1>Meu perfil acadêmico</h1>.

2. O que você colocou dentro do <head> e qual é a função de cada elemento utilizado?
Dentro do <head>, incluí a tag <meta charset="UTF-8"> para garantir que os caracteres especiais e acentos do português sejam exibidos corretamente. Adicionei também a tag <meta name="viewport" content="width=device-width, initial-scale=1.0"> para garantir que a página se adapte a telas de celulares. Por fim, utilizei a tag <title>Meu perfil acadêmico</title> para nomear a aba do navegador e a tag <style> para incluir as regras de CSS.

3. Como você utilizou as duas <div> para separar e organizar os conteúdos da página? Informe também os nomes das classes criadas.
Utilizei as tags <div> para criar blocos distintos de conteúdo, o que facilitou a organização visual e a aplicação de estilos independentes em cada parte. A primeira delas recebeu a classe class="perfil" e agrupou minha apresentação, os parágrafos sobre minha formação e a lista de interesses. A segunda divisão foi nomeada com a classe class="objetivos" e abrigou o título e o texto sobre o que desejo aprender em tecnologia.

4. Como você aplicou o CSS dentro da tag <style>? Apresente um seletor, uma propriedade e um valor existentes no seu código.
Apliquei o CSS escrevendo regras de formatação diretamente dentro da tag <style>, localizada no <head> do documento. Para formatar a caixa principal, por exemplo, utilizei o seletor de classe .perfil. Dentro dessa regra, apliquei a propriedade padding com o valor 25px, garantindo um espaçamento interno para que o texto não ficasse colado nas bordas.

5. Quais cores e propriedades visuais você escolheu e qual foi o resultado observado no navegador?
Escolhi três cores diferentes para os textos usando a propriedade color, como o azul escuro (#2c3e50) no título <h1 > e o verde (#27ae60) no título <h2 > da seção de objetivos. Para destacar os blocos, apliquei background-color com tons muito claros e usei a propriedade border, criando uma linha sólida na classe .perfil e tracejada na classe .objetivos. O resultado no navegador foi uma página com os blocos de conteúdo muito bem demarcados visualmente e agradáveis de ler.

6. Qual alteração ou correção foi necessária depois que você testou a página? Caso não tenha ocorrido erro, explique como realizou o teste.
Usei a extensão Live Server e ativei o Go live.
