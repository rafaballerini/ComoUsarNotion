# Como criar e personalizar páginas no Notion

[Nesse vídeo você aprenderá a desenvolver 3 páginas no Notion para organização](https://www.youtube.com/watch?v=weRgbHstLw8)

1. Criação de uma conta do zero no [site do Notion](https://ntn.so/rafaellanotion)

2. Escolher o plano pessoal, porém ele não te permite adicionar pessoas pra poderem editar e acompanharem o seu workspace, pra isso você utiliza o plano de time, que dependendo da quantidade de pessoas e das permissões delas é pago

3. Apagamos os templates pré definidos da plataforma para criarmos um do zero, afinal é assim que aprendemos

4. Colocamos no modo dark, porque nossos olhos merecem (para isso vamos em `settings & members` e depois em `appearance`)

A partir daqui iremos criar 3 páginas para o nosso workspace: uma de rotina, para acompanharmos as tarefas diárias, uma de estudos para fazermos resumos e anotações e outra de projeto, para acompanharmos o andamento de um projeto específico, com código e tudo mais!

## Página 1 - Rotina

1. Primeiramente, podemos colocar uma capa e um ícone em cada uma de nossas páginas pra ficar estilizado da maneira que quisermos

Agora para adicionarmos algum elemento na nossa página, podemos sempre digitar `/` que aparecerá uma lista de opções, incluindo títulos, tabelas e até embeds de outras plataformas

2. Selecionamos o `Board database full page`, que ocupará apenas um espaço na página, não ela inteira

Eu não vou mostrar aqui cada opção que tem, senão o vídeo ficaria gigantesco, mas eu recomendo muito que nesse começo vocês brinquem um pouco com todas as opções pra poder descobrir a variedade de coisas que você pode fazer na plataforma

3. Personalizamos o nosso "kanban", adicionando o título `Tarefas do dia` e criando as colunas de acordo com o status de cada uma dessas tarefas: `backlog`, `doing`, `done` e `wishlist`

4. Apagamos as propriedades pré definidas e adicionamos algumas que fazem sentido, como o `status`, `tipo de tarefa` e a `data de entrega` e deixamos os dois últimos aparecendo no card

5. Podemos criar diferentes visualizações para esses mesmos dados, clicando em `add view`

## Página 2 - Estudos

Agora que vimos como conseguimos criar do zero, vou dar um exemplo pra vocês de como podemos usar um dos templates já pré definidos na plataforma para fazer essa nossa próxima página. Nesse caso usaremos o template `Classroom Home`

1. Alteramos o título para `Estudos de programação`, colocamos um ícone de livros e uma capa também

2. Apagamos a parte de `Annoucements`, pois não iremos utilizar

3. Colocamos uma descrição motivadora, pra sempre lermos quando entrarmos na página, como `Sucesso é o acúmulo de pequenos esforços construídos a cada dia`

4. Trocamos o `History` por `Matérias` e adicionamos todas as áreas que iremos estudar no semestre ou como quiser se organizar

5. Colocamos abaixo também os nossos `Horários semanais`

6. Por fim, criamos a melhor parte nessa página, uma tabela de `Faltas e notas` e, pra isso adicionamos uma `table database inline`

7. Criamos as colunas de `Matéria`, `Faltas`, `Nota1`, `Nota2` e `Média`, cada uma com seu tipo específico e essa última colocamos como `Formula` e adicionamos a seguinte equação:

```
divide(prop("Nota1") + prop("Nota2"), 2)
```

Assim, nessa coluna aparecerá a soma da primeira nota na colunas `Nota1` com a segunda na coluna `Nota2`, divididas por 2

8. Além disso, na coluna de `Faltas`, podemos adicionar a soma de todas as linhas também com `sum`

## Página 3 - Projeto

Aqui também utilizaremos um tamplate base, chamado `Engineering Wiki`, dentro da pasta `Engineering`

1. Alteramos o título para `Balle Bot`, colocamos um ícone de foguete e uma capa também

2. Separamos os tópicos em `Links importantes`, `Código`, `Testes` e `Finanças`

3. Em `Links importantes`, colocamos uma página de `Kanban de tarefas do projeto` e um embed do figma com o design da página

4. Em `Código` deixamos a página `React`, pois deixaremos um link com a biblioteca e também colocaremos um embed de um gist do github

5. Em finanças colocamos `Gastos` e `Lucros`


## Finalização

Você encontra esses templates feitos [nesse link](https://stream-porcupine-f40.notion.site/Templates-8d402940e140454ba79d6c7521b9e53b)

Se quiserem que eu traga um vídeo mostrando como automatizar as tarefas no Notion ou como consumir dados de uma API, deixa aqui nos comentários que eu vou adorar ensinar vocês!

Não esqueça de se inscrever no [canal](https://youtube.com/rafaellaballerini) e até semana que vem! 
