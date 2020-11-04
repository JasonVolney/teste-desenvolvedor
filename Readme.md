# Teste para Desenvolvedor

### União Brasileira Beneficente (UBB)

Esse teste é apresentado aos candidatos à vaga de desenvolvedor para avaliar os quesitos técnicos.

**Passos:**

1. Fazer um fork deste repositório (o prazo começará a contar à partir disso)
2. Desenvolver o teste
3. Fazer uma pull request para esse repositório

**Requisitos:**

* A aplicação deverá ser feita com React ou Angular
* A aplicação deverá ser responsiva, pois será testada no desktop e celular
* Hospedagem do projeto (Heroku, Netlify, Azure/AWS gratuitos, etc.)

**O que deverá ser feito?**

Usando a API de filmes gratuita [themoviedb](https://developers.themoviedb.org/3/getting-started/introduction) você será responsável por criar uma listagem dos filmes mais populares do dia, consultando o endpoint `GET /movie/popular` para realizar a listagem.

Os usuários dessa lista costumam ter uma melhor experiência utilizando um filtro com seu `gênero favorito`. Portanto, devemos permitir com que filtros de filmes por gênero sejam realizados na listagem. Note que um novo endpoint deverá ser consultado para obter uma lista dos possíveis gêneros a serem filtrados, `GET /genre/movie/list`.

Para garantir que o usuário encontre o filme que está procurando, essa lista deverá ser paginada sempre que não existir nenhum filtro de gênero ativo.
 
* O usuário deve ter acesso a uma listagem dos filmes mais populares do dia
* O usuário deve conseguir paginar a lista para encontrar novos filmes
* O usuário deve conseguir filtrar os filmes listados por gênero
* Ao realizar um filtro, a paginação deve ser desabilitada
* O usuário deve conseguir remover o filtro e a paginação deverá voltar a funcionar
 
 
 **Referências para consulta**
 
* [https://developers.themoviedb.org/3/movies/get-popular-movies](https://developers.themoviedb.org/3/movies/get-popular-movies)
* [https://developers.themoviedb.org/3/genres/get-movie-list](https://developers.themoviedb.org/3/movies/get-popular-movies)

**Extras**

* Pode utilizar qualquer library para ajudar no design, como Material-UI, Bootstrap, Foundation, Bulma, Flexbox Grid e etc.
* Pode consultar qualquer site para te auxiliar (stack overflow, google, github, etc)
* Gostariamos de avaliar a sua percepção de UI e UX, por isso use a criatividade para desenvolver a melhor tela/experiência

**Diferenciais:**

* Clean Code
* Componentização
* Testes
* Design Patterns
* Organização do código


## Dúvidas
Caso haja qualquer dúvida sobre o teste, nos envie um email para [desenvolvimento@ubbonline.org.br](mailto:desenvolvimento@ubbonline.org.br) com o título: `[Teste Desenvolvedor] Briefing da dúvida`

Obrigado e bom desafio!


