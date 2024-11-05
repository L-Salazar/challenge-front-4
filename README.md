## URL do video de demonstração realizando o chamado das API's localmente ( Java e Python (Chatbot) ):

https://youtu.be/bAYQauZpZCU

## Vercel:

https://challenge-front-4-chi.vercel.app/

## Sobre a PortoQuest

A PortoQuest tem como objetivo criar uma experiência dinâmica e recompensadora para a manutenção de veículos, utilizando gamificação para incentivar visitas regulares e premiar a lealdade dos usuários. Com um sistema de pontos, manutenções gratuitas e uma plataforma de promoção para oficinas, oferecemos uma solução completa que beneficia tanto consumidores quanto prestadores de serviços. Nosso suporte contínuo através de chatbot e notificações personalizadas via IA garantem uma comunicação eficaz e uma experiência de usuário excepcional.

### Funcionalidades

- **Gamificação para Incentivar Visitas**: Utiliza técnicas de gamificação para motivar os usuários a visitarem regularmente as oficinas mecânicas, tornando a manutenção do veículo uma experiência mais envolvente e divertida.
- **Sistema de Pontos e Recompensas**: Usuários acumulam pontos a cada visita ou serviço realizado, que podem ser trocados por descontos, manutenções gratuitas ou outras recompensas exclusivas.
- **Promoção de Oficinas Parceiras**: Oferece uma plataforma para oficinas mecânicas promoverem seus serviços, atraindo mais clientes e gerando maior visibilidade no mercado.
- **Suporte Contínuo via Chatbot**: Um chatbot integrado fornece suporte imediato aos usuários, ajudando com dúvidas, agendamentos e informações sobre serviços e promoções.
- **Notificações Personalizadas com IA**: Utilizamos inteligência artificial para enviar notificações personalizadas, como lembretes de manutenção, promoções especiais ou mensagens de fidelização, com base no histórico e comportamento dos usuários.

Essas funcionalidades visam melhorar a experiência do usuário, aumentar a fidelização e promover o crescimento das oficinas parceiras.

### Sobre as telas

- ### Inicio

Início: A tela de início do aplicativo PortoQuest apresenta um menu de navegação na parte superior, com as seguintes opções: Início, Meus pontos, Chatbot, Perfil, FAQ, e um botão destacado para Baixar Aplicativo. No canto superior direito, há uma mensagem de boas-vindas ao usuário, seguido de um ícone de perfil.

Abaixo do menu, há um título em destaque: "Confira nossos parceiros", seguido por um carrossel de imagens que exibe um ambiente de oficina, reforçando a proposta do aplicativo. Abaixo do carrossel, há uma breve descrição do propósito da PortoQuest, que inclui o uso da gamificação para recompensar a lealdade dos usuários, com foco em pontos, manutenções gratuitas, e uma plataforma de promoção para oficinas parceiras.

Essa tela inicial parece focada em apresentar as principais funcionalidades do aplicativo e destacar a importância das parcerias com as oficinas.

- ### Meus Pontos

Meus Pontos: : A tela "Meus Pontos" exibe o sistema de recompensas do usuário, destacando quantos pontos foram acumulados. Na parte superior, há um menu de navegação semelhante à tela anterior, com as opções Início, Meus pontos, Chatbot, Perfil, FAQ, e o botão de Baixar Aplicativo. No canto direito, a tela exibe uma mensagem de boas-vindas ao usuário, "Seja bem-vindo, Leonardo."

Logo abaixo, há a informação de quantos pontos o usuário possui: "Meus pontos: 1 ★". À direita, a data de vigência das recompensas é apresentada (de 01/01/2024 a 01/01/2025).

A tela utiliza um gráfico em forma de linha do tempo, mostrando o progresso do usuário nas recompensas:

Revisão Gratuita (em verde, com uma estrela) é a primeira etapa.
A seguir, aparecem as etapas de:
Troca das pastilhas de freio.
Limpeza completa do carro.
Troca dos 4 pneus.
Troca de Óleo. Cada etapa futura está representada por um círculo azul com estrelas, indicando os pontos necessários para atingir essas recompensas.
Abaixo da linha do tempo, há um botão destacado em azul com o texto "Resgatar", permitindo que o usuário troque os pontos acumulados por recompensas disponíveis.

- ### Resgate da recompensa

A tela de Resgate no aplicativo PortoQuest exibe o QR Code necessário para o usuário resgatar a recompensa. No topo, o menu de navegação permanece, junto com a mensagem de boas-vindas ao usuário. O título da tela indica o resgate de uma "Revisão Gratuita", e abaixo, o QR Code ocupa o centro da tela. O usuário é instruído a apresentar o código na oficina mecânica para resgatar o benefício. A interface é simples e focada, garantindo fácil acesso à funcionalidade de resgate.

- ### Meus Resgates

A tela Meus Resgates no aplicativo PortoQuest exibe o histórico de resgates do usuário em uma lista organizada. Cada resgate inclui o nome da recompensa (como troca de pastilha de freio, troca de óleo, e revisão gratuita), a data em que foi resgatado, e a quantidade de estrelas utilizada. O layout é simples, com uma área em destaque centralizada contendo as informações dos resgates. O menu de navegação permanece visível no topo da página, junto com a opção de sair do perfil do usuário.

- ### FAQ

A tela de FAQ no aplicativo PortoQuest apresenta uma seção de perguntas frequentes para ajudar os usuários a entender o funcionamento do aplicativo. O título "Como funciona a Porto Quest?" está em destaque no topo da página. Abaixo, as perguntas e respostas estão organizadas em um formato de accordion, onde cada item pode ser expandido ou recolhido clicando no ícone à direita. As perguntas são fictícias e os textos de exemplo em Lorem Ipsum indicam onde as informações reais serão colocadas. O layout mantém o design limpo e consistente com o restante do aplicativo, e o menu de navegação está presente no topo, facilitando a movimentação entre as seções do app.

- ### ChatBot

A tela ChatBot no aplicativo PortoQuest apresenta uma interface de conversação entre o usuário e o chatbot. As mensagens enviadas e recebidas são exibidas em balões, organizados em um layout que simula uma conversa, com as mensagens do usuário à esquerda e as respostas do chatbot à direita. O fundo azul destaca a área de chat, e o texto fictício em Lorem Ipsum serve como um placeholder para o conteúdo real das conversas. Na parte inferior da tela, há um campo com a mensagem "Pergunte ao nosso chatbot:", indicando onde o usuário pode inserir suas perguntas. O menu de navegação permanece no topo para facilitar o acesso a outras funcionalidades.

## Tabela com os endpoints

Veículo:
Endpoint: /veiculo
Método HTTP: GET
Descrição: Retorna todos os veículos cadastrados.
Status Code: Retorna 200 (OK) se houver veículos, ou 404 (Not Found) se não houver.

Endpoint: /veiculo/{id}
Método HTTP: GET
Descrição: Retorna um veículo específico pelo seu ID.
Status Code: Retorna 200 (OK) se o veículo for encontrado, ou 404 (Not Found) se o veículo não existir.

Endpoint: /veiculo
Método HTTP: POST
Descrição: Adiciona um novo veículo ao sistema.
Status Code: Retorna 201 (Created) se o veículo for adicionado com sucesso, ou 400 (Bad Request) em caso de erro.

Endpoint: /veiculo/{id}
Método HTTP: DELETE
Descrição: Exclui um veículo específico pelo seu ID.
Status Code: Retorna 200 (OK) se o veículo for excluído com sucesso, ou 404 (Not Found) se o veículo não for encontrado.

Endpoint: /veiculo/{id}
Método HTTP: PUT
Descrição: Atualiza as informações de um veículo específico pelo seu ID.
Status Code: Retorna 200 (OK) se o veículo for atualizado com sucesso, ou 404 (Not Found) se o veículo não for encontrado.

Usuário:

Endpoint: /usuario
Método HTTP: GET
Descrição: Retorna todos os usuários cadastrados.
Status Code: Retorna 200 (OK) se houver usuários, ou 404 (Not Found) se não houver.

Endpoint: /usuario/{id}
Método HTTP: GET
Descrição: Retorna um usuário específico pelo seu ID.
Status Code: Retorna 200 (OK) se o usuário for encontrado, ou 404 (Not Found) se o usuário não existir.

Endpoint: /usuario
Método HTTP: POST
Descrição: Adiciona um novo usuário ao sistema.
Status Code: Retorna 201 (Created) se o usuário for adicionado com sucesso, ou 400 (Bad Request) em caso de erro.

Endpoint: /usuario/{id}
Método HTTP: DELETE
Descrição: Exclui um usuário específico pelo seu ID.
Status Code: Retorna 200 (OK) se o usuário for excluído com sucesso, ou 404 (Not Found) se o usuário não for encontrado.

Endpoint: /usuario/{id}
Método HTTP: PUT
Descrição: Atualiza as informações de um usuário específico pelo seu ID.
Status Code: Retorna 200 (OK) se o usuário for atualizado com sucesso, ou 404 (Not Found) se o usuário não for encontrado.

Resgates Do Usuário:

Endpoint: /resgate-usuario
Método HTTP: GET
Descrição: Retorna todos os registros de resgate de usuários.
Status Code: Retorna 200 (OK) se houver registros, ou 404 (Not Found) se não houver.

Endpoint: /resgate-usuario/{id}
Método HTTP: GET
Descrição: Retorna um registro de resgate de usuário específico pelo seu ID.
Status Code: Retorna 200 (OK) se o registro for encontrado, ou 404 (Not Found) se o registro não existir.

Endpoint: /resgate-usuario
Método HTTP: POST
Descrição: Adiciona um novo registro de resgate de usuário ao sistema.
Status Code: Retorna 201 (Created) se o registro for adicionado com sucesso, ou 400 (Bad Request) em caso de erro.

Endpoint: /resgate-usuario/{id}
Método HTTP: DELETE
Descrição: Exclui um registro de resgate de usuário específico pelo seu ID.
Status Code: Retorna 200 (OK) se o registro for excluído com sucesso, ou 404 (Not Found) se o registro não for encontrado.

Endpoint: /resgate-usuario/{id}
Método HTTP: PUT
Descrição: Atualiza as informações de um registro de resgate de usuário específico pelo seu ID.
Status Code: Retorna 200 (OK) se o registro for atualizado com sucesso, ou 404 (Not Found) se o registro não for encontrado.

Recompensa:

Endpoint: /recompensas
Método HTTP: GET
Descrição: Retorna todas as recompensas cadastradas.
Status Code: Retorna 200 (OK) se houver recompensas, ou 404 (Not Found) se não houver.

Endpoint: /recompensas/{id}
Método HTTP: GET
Descrição: Retorna uma recompensa específica pelo seu ID.
Status Code: Retorna 200 (OK) se a recompensa for encontrada, ou 404 (Not Found) se a recompensa não existir.

Endpoint: /recompensas
Método HTTP: POST
Descrição: Adiciona uma nova recompensa ao sistema.
Status Code: Retorna 201 (Created) se a recompensa for adicionada com sucesso, ou 400 (Bad Request) em caso de erro.

Endpoint: /recompensas/{id}
Método HTTP: DELETE
Descrição: Exclui uma recompensa específica pelo seu ID.
Status Code: Retorna 204 (No Content) se a recompensa for excluída com sucesso, ou 404 (Not Found) se a recompensa não for encontrada.

Endpoint: /recompensas/{id}
Método HTTP: PUT
Descrição: Atualiza as informações de uma recompensa específica pelo seu ID.
Status Code: Retorna 201 (Created) se a recompensa for atualizada com sucesso, ou 400 (Bad Request) em caso de erro.

Peca:

Endpoint: /peca
Método HTTP: GET
Descrição: Retorna todas as peças cadastradas.
Status Code: Retorna 200 (OK) se houver peças, ou 404 (Not Found) se não houver.

Endpoint: /peca/{id}
Método HTTP: GET
Descrição: Retorna uma peça específica pelo seu ID.
Status Code: Retorna 200 (OK) se a peça for encontrada, ou 404 (Not Found) se a peça não existir.

Endpoint: /peca
Método HTTP: POST
Descrição: Adiciona uma nova peça ao sistema.
Status Code: Retorna 201 (Created) se a peça for adicionada com sucesso, ou 400 (Bad Request) em caso de erro.

Endpoint: /peca/{id}
Método HTTP: DELETE
Descrição: Exclui uma peça específica pelo seu ID.
Status Code: Retorna 200 (OK) se a peça for excluída com sucesso, ou 404 (Not Found) se a peça não for encontrada.

Endpoint: /peca/{id}
Método HTTP: PUT
Descrição: Atualiza as informações de uma peça específica pelo seu ID.
Status Code: Retorna 200 (OK) se a peça for atualizada com sucesso, ou 404 (Not Found) se a peça não for encontrada.

Oficina Parceira:

Endpoint: /oficinas
Método HTTP: GET
Descrição: Retorna todas as oficinas parceiras cadastradas.
Status Code: Retorna 200 (OK) se houver oficinas cadastradas, ou 404 (Not Found) se não houver.

Endpoint: /oficinas/{id}
Método HTTP: GET
Descrição: Retorna uma oficina parceira específica pelo seu ID.
Status Code: Retorna 200 (OK) se a oficina for encontrada, ou 404 (Not Found) se a oficina não existir.

Endpoint: /oficinas
Método HTTP: POST
Descrição: Adiciona uma nova oficina parceira ao sistema.
Status Code: Retorna 201 (Created) se a oficina for adicionada com sucesso, ou 400 (Bad Request) em caso de erro.

Endpoint: /oficinas/{id}
Método HTTP: DELETE
Descrição: Exclui uma oficina parceira específica pelo seu ID.
Status Code: Retorna 204 (No Content) se a oficina for excluída com sucesso, ou 404 (Not Found) se a oficina não for encontrada.

Endpoint: /oficinas/{id}
Método HTTP: PUT
Descrição: Atualiza as informações de uma oficina parceira específica pelo seu ID.
Status Code: Retorna 201 (Created) se a oficina for atualizada com sucesso, ou 400 (Bad Request) em caso de erro.

Esse formato fornece uma visão clara e organizada de cada endpoint da classe OficinaParceiraResource

Endpoint: /chabot-faq
Metodo HTTP: POST
Descrição: Espera uma pergunta e retorna a resposta com base no modelo treinado em IA
