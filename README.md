# BicoDin
Nesse repositório encontrasse o sistema em desenvolvimento da plataforma **BicoDin** . Para o desenvolvimento da plataforma foi utilizado a ferramente Outsystems + CSS + SQL. Todos os componentes (incluindo as folhas de estilo, banco de dados, funções e fluxos das telas) só podem ser acessados através do Service Studio do Outsystems.

Foram desenvolvidas as seguintes páginas:


![](https://scontent.frec20-1.fna.fbcdn.net/v/t1.15752-9/98306577_702546377172221_7960025583037972480_n.png?_nc_cat=109&_nc_sid=b96e70&_nc_oc=AQmfA0FODI6bQxcDfRAbPmdbJb1A4J0axJOhLnjxZNYyKsjZG2j4XnrnDxuw6Q-s984&_nc_ht=scontent.frec20-1.fna&oh=f0dcc01fc498040789bb41b990a87723&oe=5EE5F7DC)


A estrutura usada no Banco de Dados pode ser visto no diagrama abaixo: 
\
![](https://scontent.frec20-1.fna.fbcdn.net/v/t1.15752-9/98182175_572155540348656_2479658089414918144_n.png?_nc_cat=111&_nc_sid=b96e70&_nc_oc=AQlCjahMiq9fhT-ox-OcZti1uvTghUqJX17iHtHhSp5EGtG91hhwQjHNDuaYD7lcqb0&_nc_ht=scontent.frec20-1.fna&oh=0687de5ac80b23f5295d71de5410be34&oe=5EE5CE24)

Para os trabalhadores autônomos e informais com dificuldades em conseguir clientes, o **BicoDin** é uma plataforma online, que reúne perfis de trabalhadores promovendo maior visibilidade e conectando-os a potenciais clientes.
Diferente de boca-a-boca e redes sociais, a nossa plataforma, que é focada em trabalhadores de baixa e média renda, apresenta o perfil profissional dos trabalhadores e tem mecanismos de verificação e avaliação que proporcionam segurança aos usuários.

Para ter acesso a códigos fontes, banco de dados, folhas de estilo e outros siga os seguintes passos:

1. Instale a ferramneta [Outsystems Service Studio](https://www.outsystems.com/downloads/) (Windows)
2. Clone esse repositório através do seguinte comando no terminal 
``git clone``
3. Com o Service Studio aberto: clique em 'Environment' -> 'Open Files' -> Selecione os arquivos clonados.

No arquivo *bicodin_DB.oml* encontrasse o banco de dados *SQL*, dá aplicação. 
No arquivo *bicodin.oml* encontrasse as funções e damais componentes necessários para o funcionamento do sistema.

Para a execução do sistema:

1. Clique no seguinte botão  ![](https://scontent.frec20-1.fna.fbcdn.net/v/t1.15752-9/98135760_526231888051970_8327538521443139584_n.png?_nc_cat=108&_nc_sid=b96e70&_nc_oc=AQn_LA8HexDiHO_DQ9tgfnhUHvLEq05vIm_8T-3TBOQpSZaFLNgjTLb4HD6Wmp-WEBQ&_nc_ht=scontent.frec20-1.fna&oh=ff37399a55b4a8aec6cba13df1f9f275&oe=5EE5DD3E), localizado no topo da página para deploy.
2. Clique no seguinte botão  ![](https://scontent.frec20-1.fna.fbcdn.net/v/t1.15752-9/98006496_260854455274121_4996876823179558912_n.png?_nc_cat=107&_nc_sid=b96e70&_nc_oc=AQn8u_F3e0zrMOgIqwZsNY3nKppTdD9vLOD_WwTYI3yw6-I8O73z29WYgu5BY-2tXT8&_nc_ht=scontent.frec20-1.fna&oh=a877894859a67baaa702b1278cd27c08&oe=5EE58FE0), localizado no topo da página para execução do sistema na nuvem Outsystems.
