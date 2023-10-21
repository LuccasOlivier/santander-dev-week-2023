# Santander Dev Week 2023

Java RESTful API criada para a Santander Dev Week.

## Implementações Realizadas por mim:

Como participante ativo do curso Fullstack Java + Angular do Santander Dev Week 2023, tive o prazer de contribuir com várias implementações valiosas para este projeto. Abaixo, descrevo as principais alterações que introduzi:

### Criação do Endpoint para Alteração de Senha

Adicionei um novo endpoint chamado /users/change-password para possibilitar que os usuários atualizem suas senhas. Essa funcionalidade é essencial para melhorar a segurança e a usabilidade de nossa aplicação.

### Criação de uma Classe ChangePasswordRequest

Desenvolvi uma nova classe denominada ChangePasswordRequest, projetada para representar os dados necessários para efetuar uma alteração de senha. Esses dados incluem o ID do usuário, a senha atual e a nova senha.

### Atualização do UserController

Aprimorei o UserController ao adicionar um novo método responsável por lidar com as solicitações de alteração de senha. Esse método aceita um objeto ChangePasswordRequest como entrada e efetua o processamento necessário para a alteração de senha.

### Atualização do UserService

Estendi o UserService ao incluir um novo método que executa a lógica relacionada à alteração de senha, com base nas informações fornecidas no objeto ChangePasswordRequest.

### Atualização do UserServiceImpl

Na classe UserServiceImpl, implementei a lógica de alteração de senha. Agora, o serviço verifica a senha atual do usuário, executa a atualização e lida com qualquer possível falha na alteração de senha.

### Mensagens Adicionadas

Inseri mensagens em inglês para notificar os usuários sobre o resultado das alterações de senha:
- "Password changed successfully!" (Senha alterada com sucesso!)
- "Password change failed. Please check the current password." (Falha na alteração de senha. Verifique a senha atual.)

Continuarei implementando mais recursos e melhorias no projeto! 

## IMPORTANTE

Este projeto foi construído com um viés totalmente educacional para a DIO. Por isso, disponibilizamos uma versão mais robusta dele no repositório oficial da DIO:

### [digitalinnovationone/santander-dev-week-2023-api](https://github.com/digitalinnovationone/santander-dev-week-2023-api)

Lá incluímos todas os endpoints de CRUD, além de aplicar boas práticas (uso de DTOs e refinamento na documentação da OpenAPI). Sendo assim, caso queira um desafio/referência mais completa é só acessar 👊🤩
