<h1 align="center">
  <img src="https://github.com/HC3-Grupo-15/store-front/blob/main/assets/hc.png?raw=true">
  <p>
  Desafio Final<br>Hiring Coders 2021.2 - Grupo 15
  </p>
</h1>

<h3 align="center">
  Índice
</h3>

<p align="center">
	<a href="#notes">Notas</a> • 
	<a href="#partners">Parceiros</a> • 
	<a href="#requirements">Requisitos</a> • 
	<a href="#get-project">Obtendo o projeto</a> • 
	<a href="#tools">Ferramentas</a> • 
	<a href="#technologies">Tecnologias</a> • 
	<a href="#contributors">Participantes</a>
</p>

<h6 id="notes"></h6>

## :memo: Notas

- Projeto realizado durante o Desafio Final do Hiring Coders 2021.2 da VTEX.

<h6 id="partners"></h6>

## 🤝 Parceiros

- [VTEX](https://vtex.com/br-pt/)
- [Gama Academy](https://www.gama.academy/)
- [AWS](https://aws.amazon.com/pt/)
- [Corebiz](https://www.corebiz.ag/pt/)
- [ACCT](https://acct.global/pt/)
- [We.digi](https://www.wedigi.com.br/)
- [Whirlpool](https://www.whirlpool.com.br/)
- [Loja Integrada](https://lojaintegrada.com.br/)

<h6 id="requirements"></h6>

## :heavy_check_mark: Requisitos do desafio

- [x] Desenvolver um serviço VTEX para servir os dados dos produtos, pedidos e clientes;
- [x] Desenvolver uma API Gateway na AWS para gerenciamento de venda ativa, clientes que se cadastraram em uma lead ou clientes que já compraram no e-commerce;
- [x] Fazer a integração entre o serviço VTEX e a AWS API Gateway;
- [x] Ao concluir uma compra, verificar se o usuário que finalizou é o mesmo usuário cadastrado na lead da API AWS, marcar este usuário que era somente um prospect na lead agora como cliente;
- [x] Criar uma página sobre com a temática, missão, valores e virtudes dos serviços da [Corebiz](https://www.corebiz.ag/pt/);
- [x] Criar uma página para exibir todos os produtos disponíveis na loja;
- [x] Criar uma página para trazer a lista das leads cadastradas na API Gateway na
      AWS, listando os clientes cadastrados;

<h6 id="get-project"></h6>

## :open_file_folder: Obtendo o projeto

```bash
# Clone os repositórios
git clone https://github.com/HC3-Grupo-15/store-front.git
git clone https://github.com/HC3-Grupo-15/api-vtex.git
git clone https://github.com/HC3-Grupo-15/form-leads-component.git

# Execute o comando abaixo em cada pasta que foi clonada
vtex link
```

<h6 id="tools"></h6>

## :zap: Ferramentas utilizadas

- [x] **Trello** para organização da equipe;
- [x] **Whimsical** para definir a arquitetura do projeto [(link aqui)](https://whimsical.com/hc3-desafio-final-Wn5dUUGaZpzEmvgJNjgBv4);
- [x] **Figma** para design do layout [(link aqui)](https://www.figma.com/file/05cESpoNNwlGBW3iOWRqku/Corebiz-Frontend?node-id=0:1);

<h6 id="technologies"></h6>

## :zap: Tecnologias utilizadas

### API VTEX

> Criamos os clients e middlewares para acessar as rotas da AWS e prover todos os dados para nosso front-end utilizando as tecnologias abaixo:

- [x] **Node.js**;
- [x] **TypeScript**;

Repositório do serviço [aqui.](https://github.com/HC3-Grupo-15/api-vtex)

### AWS API Gateway

> Criamos o banco de dados DynamoDB. Criamos também a função Lambda para realizar o CRUD no banco. A função foi criada no editor da própria plataforma com a linguagem Javascript utilizando Node.js. Ela recebe uma requisição http e por meio de um switch case, identifica o verbo e executa as suas ações necessárias.

#### Rotas:

- [x] /leads (GET);
- [x] /leads (POST);
- [x] /leads/{id} (PUT);
- [x] /leads/{id} (DELETE);

Repositório da API [aqui.](https://github.com/HC3-Grupo-15/aws-lambda-function)

### Front-end

> Os layouts foram desenvolvidos no Figma e utilizados como base na implementação das páginas.

#### Páginas:

- [x] **Home** - Banner simples e chamada para cadastrar e receber notícias;
- [x] **Produtos** - Onde está a listagem de todos os produtos cadastrados;
- [x] **Sobre Nós** - Apresentação da Corebiz, e textos descrevendo seus valores e missão;
- [x] **Clientes** - Listagem de clientes cadastrados;

Repositório [aqui.](https://github.com/HC3-Grupo-15/store-front)

<h6 id="contributors"></h6>

## :bust_in_silhouette: Participantes

| Nome                    |                                                                                            Github                                                                                            | Linkedin                                                                                                                                                                                                         |
| ----------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| _Igor Youiti_           |     [![Linkedin Badge](https://img.shields.io/badge/-github-181717?style=for-the-badge&logo=Github&logoColor=white&link=https://github.com/igoryouiti/)](https://github.com/igoryouiti/)     | [![Linkedin Badge](https://img.shields.io/badge/-linkedin-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/igoryouiti/)](https://www.linkedin.com/in/igoryouiti/)         |
| _Julia Braz_            |       [![Linkedin Badge](https://img.shields.io/badge/-github-181717?style=for-the-badge&logo=Github&logoColor=white&link=https://github.com/juliabrz/)](https://github.com/juliabrz/)       | [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/juliacdbraz/)](https://www.linkedin.com/in/juliacdbraz/)       |
| _Stenio Almeida_        |       [![Linkedin Badge](https://img.shields.io/badge/-github-181717?style=for-the-badge&logo=Github&logoColor=white&link=https://github.com/stenioas/)](https://github.com/stenioas/)       | [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/stenioas/)](https://www.linkedin.com/in/stenioas/)             |
| _Mayara Becker_         |      [![Linkedin Badge](https://img.shields.io/badge/-github-181717?style=for-the-badge&logo=Github&logoColor=white&link=https://github.com/mahbecker/)](https://github.com/mahbecker/)      | [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/mayara-becker/)](https://www.linkedin.com/in/mayara-becker/)   |
| _Gabriel Brito_         |  [![Linkedin Badge](https://img.shields.io/badge/-github-181717?style=for-the-badge&logo=Github&logoColor=white&link=https://github.com/briitogabriel/)](https://github.com/briitogabriel/)  | [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/brittogabriel/)](https://www.linkedin.com/in/brittogabriel/)   |
| _Antônio Monte Christo_ |  [![Linkedin Badge](https://img.shields.io/badge/-github-181717?style=for-the-badge&logo=Github&logoColor=white&link=https://github.com/amontechristo/)](https://github.com/amontechristo/)  | [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/amontechristo/)](https://www.linkedin.com/in/amontechristo/)   |
| _Carlos Marinho_        | [![Linkedin Badge](https://img.shields.io/badge/-github-181717?style=for-the-badge&logo=Github&logoColor=white&link=https://github.com/ICarlosMarinho/)](https://github.com/ICarlosMarinho/) | [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/carloshmarinho/)](https://www.linkedin.com/in/carloshmarinho/) |
| _Carlos Roberto_        |      [![Linkedin Badge](https://img.shields.io/badge/-github-181717?style=for-the-badge&logo=Github&logoColor=white&link=https://github.com/carrobert/)](https://github.com/carrobert/)      | [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/)](https://www.linkedin.com/)                                     |
| _Bruna Freitas_         |     [![Linkedin Badge](https://img.shields.io/badge/-github-181717?style=for-the-badge&logo=Github&logoColor=white&link=https://github.com/freitasbru/)](https://github.com/freitasbru/)     | [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/freitasbru/)](https://www.linkedin.com/in/freitasbru/)         |
| _Ademir Rafael_         | [![Linkedin Badge](https://img.shields.io/badge/-github-181717?style=for-the-badge&logo=Github&logoColor=white&link=https://github.com/ademirrafaelmg/)](https://github.com/ademirrafaelmg/) | [![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=for-the-badge&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ademirrafaelmg/)](https://www.linkedin.com/in/ademirrafaelmg/) |

---

### :heart: O Grupo 15 agradece por dedicarem o seu tempo a conhecer o nosso projeto!

<img src="https://github.com/HC3-Grupo-15/assets/blob/main/About-us.PNG?raw=true"><img src="https://github.com/HC3-Grupo-15/assets/blob/main/Home2.PNG?raw=true">
