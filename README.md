# Desafio Front-end Developer

## Objetivo

Desenvolver uma aplicação front-end utilizando o framework Angular 2+, consumindo a API da Trakto, para realizar a história do usuário a seguir.

## Link e descrição da vaga

https://trakto.gupy.io/jobs/4649652

## História do usuário

Como professor da Trakto Educação, eu preciso ter uma plataforma quer siga o protótipo no link https://www.figma.com/file/Ajzapgkl4vrXw8KnHlIwPh/PrototipoTraktoTV, onde eu forneço meu email e senha, e após a validação eu tenha acesso a uma tela com todos os módulos da Trakto Tv. Essa tela inicial deve ter um ícone para: Material didático; Quiz, Desenho e Youtube. Apenas o módulo "Material didático" é obrigatório, e o módulo "Desenho" é opcional e funciona como uma lousa.

O módulo de "Material didático" deve conter a lista dos meus 10 designs que foram editados recentemente e deve ter a opção de listar todos os materiais. Ao clicar na miniatura do design ou no nome do mesmo, deve-se abrir o modo de apresentação do nosso editor em uma nova aba.

Todas as informações sobre a API estão na collectio. do postman na lista de links.

**Observação 1**: Como é preciso listar os últimos materiais editados, você vai precisar entrar na plataforma (https://dashboard.trakto.io/), criar uma conta gratuita e criar alguns documentos a partir de qualquer template disponível, não é preciso customizá-los mas fique à vontade se quiser fazer.

**Observação 2**: O link do modo de apresentação dos designs é **https://editor.trakto.io/presentation/p/{ID}**,  onde **{ID}** é o atributo **ID** retornado do end-point de listagem de documentos (List all designs).

## Critérios de aceite

- O visual deve ser idêntico ao protótipo do figma;
- O projeto deve ser dedsenvolvido em Angular 2+;
- As requisições à API devem ser reais, e o candidato deve ter uma conta gratuita na trakto para usar suas credenciais para usar a API;
- O repositório deve está publicado no github e o README deve conter todas as informações necessárias para rodar a aplicação.

## Links

Para criar sua conta na trakto:

https://www.trakto.io 

Protótipo Figma:

https://www.figma.com/file/Ajzapgkl4vrXw8KnHlIwPh/PrototipoTraktoTV

Collection do Postman para referência da API:

https://github.com/trakto/desafio_frontend/blob/main/DesafioTrakto.postman_collection.json

## Entrega

Basta enviar o link do seu repositórion na Gupy. Não precisa de deploy em qualquer plataforma e não precisa ser responsivo.

## Avaliação

Desde o entendimento do projeto até os testes. O conhecimento sobre os conceitos do framework, a lógica, estruturação do projeto e a performance da aplicação serão avaliados.
