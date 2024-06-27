# ProjetoGlobo

Neste projeto, foi desenvolvida uma solução abrangente no Salesforce, incluindo a criação de objetos personalizados, relacionamentos, campos personalizados, um aplicativo, endpoints, testes unitários e um screen flow.

Objetos Personalizados:
Foram criados os objetos "Pais" para armazenar informações de países e "Pedido" com campos como Número do Pedido, Data, Descrição e Valor Total. O objeto Pedido possui relacionamentos com Produto (lookup) e Conta (mestre-detalhes), permitindo a totalização de pedidos na Conta.

Relacionamentos:
Estabeleci um relacionamento lookup entre Pedido e Produto e um relacionamento mestre-detalhes entre Pedido e Conta para possibilitar a criação de campos de resumo em Conta.

Campos Personalizados:
Foram adicionados novos campos personalizados na Conta conforme necessário.

Aplicativo Globo:
Foi criado um aplicativo chamado Globo, incluindo as abas: Início, Pedido, Conta, Produto, Lead e Oportunidade.

Endpoint para Upsert em Conta: 
Foi desenvolvido um endpoint para realizar upsert (inserção ou atualização) em Conta, juntamente com testes unitários para garantir a funcionalidade.

Inserção em Pedido:
Foi Implementado a lógica de inserção de registros no objeto Pedido, também com testes unitários.

Screen Flow para Alteração de Email:
Foi Criado um screen flow para alteração de email, oferecendo a opção de desativar o envio de emails.

Usuário Avaliador:
Foi criado um usuário administrador com o email administradorGK@hotmail.com e a senha 3Ks&7d!eJf@1, garantindo que este usuário tenha acesso às configurações implementadas.
