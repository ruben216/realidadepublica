# Portal Realidade Publica

## Método de extração dos dados 

O portal de transparência disponibiliza APIs no padrão Rest, que podem ser consumidas para download de conteúdos. Os detalhes podem ser conferidos nessa seção:
https://portaldatransparencia.cgu.gov.br/api-de-dados . E os swaggers de todos os serviços estão disponíveis nesse [link](http://api.portaldatransparencia.gov.br/swagger-ui.html#/Emendas%20parlamentares/emendasUsingGET).

Para enviar requests, é necessário realizar o seguinte passo-a-passo:

1. Criar uma conta em https://acesso.gov.br/
2. Realizar o download do app gov.br , disponível para Android e iOS. Importante: As notificações devem ser permitidas, pois serão enviados tokens para autenticação de dois fatores.
3. Acessar o app e avançar o nível da sua conta até **Prata** . 
4. Acessar http://portaldatransparencia.gov.br/api-de-dados/cadastrar-email e realizar o login de dois fatores. 
   Nesse momento é gerada a chave de acesso à API.

Feito isso, estamos prontos para enviar requisições ao portal! 
Existem diversas maneiras de consumir esses dados, e nessa seção são disponibilizados alguns exemplos http://www.portaldatransparencia.gov.br/pagina-interna/603579-api-de-dados-exemplos-de-uso

Neste momento, iremos focar somente nos dados, e não em "como" extraí-los. Para isso, vamos realizar o download diretamente através do aplicativo Postman (https://www.postman.com/downloads/).


## Collab do time

[Notebook Collab](Notebook.ipynb)

## Inspirações

- https://www.kaggle.com/cmcoutosilva/an-lise-de-correspond-ncia-c-mara-dos-deputados
- https://escoladedados.org/tutoriais/explorando-as-despesas-do-governo-federal-via-api/
- https://colab.research.google.com/drive/1_ySD8ppLsFAQ3F5AhuGCNpOF41pHVyXy?usp=sharing






