# Media Challenge

## Objetivo

Nosso objetivo é conhecer melhor as suas habilidades técnicas.

Conhecendo você melhor, poderemos selecionar quais desafios já podemos passar para você e quais precisaremos preparar você melhor para enfrentá-los.

## Requisitos da entrega

### Nesta estapa esperamos que você construa o código que contemple as seguintes operações expostas como endpoints REST para:

- Cadastrar usuário
- Cadastrar media (foto, vídeo, áudio, texto, arquivo)
- Consultar usuário pelo nome completo
- Consultar usuário pelo identificador
- Consultar media pelo nome
- Consultar media pelo identificador
- Remover usuário
- Remover media
- Alterar os dados do usuário
- Alterar os dados da media

### Considere o cadastro com dados básicos:

- Usuário: nome completo, nome de usuário, email, telefone, sexo, data de nascimento, idade.
- Media: tipo, nome, descrição, latitude, longitude, data de criação, data de upload, data da publicação.
 
### Especificações das medias:

  - Foto: 
    - Máximo de 8 MB
    - Formatos: JPEG, PNG, BMP, e GIFs não animados.

### Documentação:

- Documentação das APIs;
- Documentação com instruções de uso;

### Extras:

- Desenvolver funcionalidade de likes para as medias;
- Desenvolver funcionalidade de comentários para as medias;
- Consultar usuário pelo nome de usuário (username);
- Desenvolver funcionalidade de marcação de usuários para as medias;
  - Usuários internos.
  - Usuários externos (link).
- Desenvolver aplicação para consumir os serviços (web/mobile/pwa/twa);
  - A aplicação deve listar as medias dos usuários de várias formas:
    - Listar medias do usuário como um feed;
    - Listar por data da criação da media;
    - Listar por proximidade utilizando a geolocalização;
    - Exibir medias em um mapa por geolocalização;
- Utilizar recursos on cloud;
- Implementar cadastro e login;
- Implementar foto perfil do usuário.
- Implementar social login (Google/Facebook, etc);
- Implementar social share;
- Implementar CI/CD.

## Cenário

No nosso dia-a-dia trabalhamos com o desenvolvimento de microserviços desenvolvidos utilizando Spring Boot. Buscamos automação dos processos de garantia da qualidade, testes, deployment e release.

## Critérios
### Avaliação

A avaliação será feita da seguinte forma:

- Vamos analisar e compilar o seu código;
- Rodar sua aplicação e executar testes para validar o atendimento funcional dos items acima;
- Verificar se o seu código é limpo (Clean Code), fácil de entender e de dar manutenção;
- Vamos simular e fazer uma revisão do seu código, olhando o código junto com você para discutirmos sobre suas decisões de implementação, os pontos positivos e negativos;
- O saldo entre o que for positivo e o que for negativo vai determinar a recomendação do ponto de vista técnico, se faltar pouco para atingir uma recomendação positiva, daremos um prazo para você corrigir e retornar;

### Requisitos Obrigatórios:

- Operações acima funcionando sem erros
- Código válido, estruturado e organizado para que possamos testar sua aplicação
- Utilização de Java8, spring boot, maven, suporte às IDEs IntelliJ e Eclipse o resto é por sua conta escolher.

### Dicas:

- Tenha em mente que a pessoa que irá executar o código não vai ter sua ajuda em caso de alguma dúvida;
- Procure fazer uma entrega simples mas consistente, usando a experiência e conhecimento adquiridos durante sua carreira;
- Não se preocupe em entregar algo extremamente completo ou rebuscado, não vamos usar este código em produção;
- Tudo será avaliado, dê o seu melhor!
- Evite fazer Pull Request ou Fork deste repositório.
