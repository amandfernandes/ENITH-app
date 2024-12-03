## 🎈Requisitos em Linguagem Natural
- RN-01: Os usuários devem poder criar uma conta, fazer login, enviar e aceitar solicitações de amizade, seguir outros usuários, ver uma lista de seus amigos e seguidores, e interagir com as postagens através de curtidas e comentário.
- RN-02: O aplicativo deve oferecer modelos de rotina que os usuários podem personalizar para criar suas próprias rotinas. 
- RN-03: Os usuários devem poder definir a visibilidade de suas rotinas, criar, editar e excluir rotinas personalizadas, e publicar suas rotinas.
- RN-04: O aplicativo deve exibir um feed de notícias com as postagens de todos os usuários, dos usuários seguidos pelo usuário atual e dos amigos do usuário.
- RN-05: O aplicativo deve permitir que os usuários pesquisem rotinas, usuários ou modelos de rotina usando palavras-chave.
- RN-06: O aplicativo deve funcionar offline e enviar lembretes ou notificações para os usuários com base no horário das tarefas em suas rotinas.
- RN-07: O aplicativo deve fornecer análises e insights sobre a produtividade do usuário.
- RN-08: O aplicativo deve ser fácil de usar, com uma interface de usuário intuitiva e uma experiência de usuário agradável.
- RN-09: O aplicativo deve permitir que os usuários rastreiem seu progresso em metas de saúde e fitness ao longo do tempo, fornecendo gráficos e estatísticas visuais.
- RN-10: Os usuários devem poder criar e gerenciar listas de tarefas diárias ou semanais, com a capacidade de marcar tarefas como concluídas e definir lembretes para tarefas futuras.
- RN-11: O aplicativo deve permitir que os usuários registrem o que comeram ao longo do dia. Os usuários devem poder adicionar detalhes sobre cada item alimentar, incluindo nome, quantidade, e informações nutricionais, como calorias, proteínas, gorduras, carboidratos, vitaminas, e minerais. O aplicativo deve calcular automaticamente o total de calorias e outros valores  nutricionais com base nos itens registrados.
- RN-12: Os usuários devem poder registrar seu consumo de água diário e acompanhar sua ingestão de líquidos ao longo do dia.
- RN-13: O aplicativo deve fornecer recursos de monitoramento do sono, permitindo que os usuários registrem a qualidade e a duração de seu sono, além de receber sugestões para melhorar seus hábitos de sono.
- RN-14: Os usuários devem poder exportar e fazer backup de seus dados pessoais, garantindo a portabilidade e segurança de suas informações.
- RN-15: O aplicativo deve permitir que os usuários adicionem entradas de texto sobre cada tarefa e meta definida para o dia, registrando o que sentiram ao cumprir aquele objetivo, quais foram as dificuldades encontradas, e quaisquer outras observações relevantes.
- RN-16: Os usuários devem poder associar fotos às suas tarefas e metas pré-estabelecidas, fornecendo uma maneira visual de registrar e documentar o progresso e os resultados alcançados.
- RN-17: O aplicativo deve oferecer opções de privacidade para as entradas relacionadas à rotina diária, permitindo que os usuários decidam se desejam manter suas informações privadas, compartilhá-las com amigos selecionados ou torná-las públicas.
- RN-18: Os usuários devem poder categorizar suas entradas relacionadas à rotina diária com tags ou etiquetas personalizadas para facilitar a organização e a busca.
- RN-19: O aplicativo deve fornecer recursos de análise e insights sobre a rotina diária do usuário, incluindo estatísticas sobre a conclusão de tarefas, o cumprimento de metas e o progresso ao longo do tempo.
- RN-20: Os usuários devem poder revisitar e refletir sobre sua rotina diária por meio de uma visualização cronológica ou calendário, que mostra as tarefas concluídas, as metas alcançadas e as experiências associadas a cada dia.
- RN-21: O aplicativo deve incluir recursos de edição para as entradas relacionadas à rotina diária, permitindo que os usuários façam correções, adições ou exclusões conforme necessário;
- RN-22: Os usuários devem poder exportar suas entradas relacionadas à rotina diária em formato de arquivo para backup ou compartilhamento externo;
- RN-23: Os usuários devem poder criar tarefas e objetivos compartilhados com seus amigos, onde ambos têm uma responsabilidade mútua de cumprir a tarefa em conjunto. O usuário que cria a tarefa pode definir sua frequência (diária ou semanal) e convidar seus amigos para participarem. Uma vez aceito o convite, os amigos podem visualizar e acompanhar o progresso da tarefa compartilhada, recebendo notificações sobre atualizações e contribuindo para sua conclusão. Essa funcionalidade promove a colaboração entre os usuários, incentivando o apoio mútuo e a consecução de objetivos comuns.

## 🛠 Requisitos Técnicos

### Funcionais
- RF-01: O sistema deve permitir que o usuário se registre utilizando um endereço de e-mail e senha, ou por meio de autenticação via plataformas de mídia social.
- RF-02: O sistema deve permitir que o usuário faça login utilizando um endereço de e-mail e senha, ou por meio de autenticação via plataformas de mídia social.
- RF-03: O sistema deve disponibilizar templates de rotinas pré-definidas que possam ser utilizados como ponto de partida para a criação de rotinas personalizadas.
- RF-04: O sistema deve permitir que o usuário personalize os templates de rotinas conforme suas necessidades.
- RF-05: O sistema deve permitir que o usuário realize buscas por rotinas, outros usuários e templates de rotina, utilizando palavras-chave.
- RF-06: O sistema deve permitir que o usuário crie, edite e exclua rotinas personalizadas.
- RF-07: O sistema deve permitir que cada rotina personalizada inclua várias tarefas, cada uma com um horário definido.
- RF-08: O sistema deve permitir que o usuário visualize e edite suas rotinas sem necessidade de conexão com a internet, garantindo o funcionamento offline do aplicativo.
- RF-09: O sistema deve enviar lembretes ou notificações ao usuário com base no horário definido para cada tarefa em suas rotinas.
- RF-10: O sistema deve fornecer análises e insights sobre a produtividade do usuário, incluindo métricas como número de tarefas concluídas e tempo gasto em cada tarefa.
- RF-11: O sistema deve permitir que o usuário defina metas e tarefas diárias, com a possibilidade de acompanhar o progresso de cada objetivo.
- RF-12: O sistema deve permitir que o usuário associe sentimentos e dificuldades enfrentadas ao realizar as tarefas diárias, como parte do acompanhamento do progresso.
- RF-13: O sistema deve permitir que o usuário utilize o modelo Pomodoro para gerenciar o tempo, com sessões de trabalho de 25 minutos seguidas por intervalos de 5 minutos, e um intervalo mais longo após quatro sessões.

- RF-14: O sistema deve permitir que o usuário registre eventos diários, sentimentos e pensamentos em um diário pessoal.
- RF-15: O sistema deve permitir que o usuário associe fotos às suas entradas de diário.

- RF-16: O sistema deve permitir que o usuário envie e receba solicitações de amizade.
- RF-17: O sistema deve permitir que o usuário siga outros usuários.
- RF-18: O sistema deve permitir que o usuário visualize uma lista de seus amigos e seguidores.
- RF-19: O sistema deve permitir que o usuário defina a visibilidade de suas rotinas como pública, privada ou visível apenas para usuários selecionados.
- RF-20: O sistema deve exibir um feed de notícias com as publicações de todos os usuários.
- RF-21: O sistema deve exibir um feed de notícias com as publicações dos usuários que o usuário segue.
- RF-22: O sistema deve exibir um feed de notícias com as publicações dos usuários que são amigos do usuário.
- RF-23: O sistema deve permitir que o usuário siga outros usuários.
- RF-24: O sistema deve permitir que o usuário curta as postagens de rotina de outros usuários.
- RF-25: O sistema deve permitir que o usuário comente nas postagens de rotina de outros usuários.
- RF-26: O sistema deve permitir que o usuário publique sua rotina, incluindo texto, fotos, vídeos e links.
- RF-27: O sistema deve permitir que o usuário edite ou exclua suas próprias publicações.
- RF-28: O sistema deve permitir que o usuário crie tarefas compartilhadas e convide amigos para participar delas.

- RF-29: O sistema deve fornecer uma interface de usuário intuitiva para criar e gerenciar tarefas compartilhadas.
- RF-30: O sistema deve implementar uma lógica de permissões para garantir que apenas os participantes autorizados possam visualizar e contribuir para as tarefas compartilhadas.
- RF-31: O sistema deve enviar notificações aos participantes sobre atualizações e lembretes relacionados às tarefas compartilhadas.

- RF-32: O sistema deve permitir que o usuário registre suas refeições diárias, incluindo detalhes nutricionais como calorias, proteínas, carboidratos, entre outros.
- RF-33: O sistema deve integrar um monitoramento de atividades físicas, permitindo que o usuário registre os exercícios realizados, incluindo duração e intensidade.
- RF-34: O sistema deve permitir que o usuário acompanhe seu progresso nas atividades físicas ao longo do tempo.

- RF-35: O sistema deve implementar recursos de sincronização em tempo real, garantindo que as atualizações feitas em um dispositivo sejam imediatamente refletidas em outros dispositivos associados à mesma conta de usuário.

- RF-36: O sistema deve integrar serviços de análise de dados para gerar insights sobre o uso da plataforma, identificando padrões de comportamento dos usuários.
- RF-37: O sistema deve utilizar os dados analisados para identificar melhorias potenciais na experiência do usuário.


## Não Funcionais
- RNF-01: O sistema deve implementar técnicas de cache para otimizar o desempenho e reduzir o tempo de carregamento, especialmente para recursos frequentemente acessados, como feeds de notícias e calendários.
- RNF-02: O sistema deve utilizar tecnologias de compressão de imagem para reduzir o tamanho das fotos enviadas pelos usuários, minimizando o consumo de largura de banda e o tempo de carregamento.
- RNF-03: O sistema deve ser fácil de usar, oferecendo uma interface intuitiva e proporcionando uma experiência de usuário agradável.

- RNF-04: O sistema deve garantir compatibilidade multiplataforma, assegurando que o aplicativo funcione de maneira consistente em diferentes dispositivos móveis, incluindo iOS e Android.
- RNF-05: O sistema deve garantir que o aplicativo seja leve e responsivo, mesmo em dispositivos móveis com recursos limitados de hardware.

- RNF-06: O sistema deve implementar um sistema de armazenamento de dados escalável e resiliente, capaz de lidar com o aumento do volume de usuários e informações.
- RNF-07: O sistema deve integrar ferramentas de monitoramento de desempenho para acompanhar a utilização de recursos do servidor, identificar gargalos de desempenho e permitir ajustes conforme necessário.

- RNF-08: O sistema deve implementar testes de usabilidade e conduzir testes beta com usuários reais para garantir uma experiência de usuário otimizada.

- RNF-09: O sistema deve adotar boas práticas de segurança da informação para proteger os dados dos usuários, incluindo criptografia de dados em repouso e em trânsito.
- RNF-10: O sistema deve garantir conformidade com regulamentações de privacidade, como o GDPR e a LGPD.
- RNF-11: O sistema deve garantir alta disponibilidade e tolerância a falhas, implementando estratégias de redundância e failover para minimizar o tempo de inatividade e assegurar a continuidade do serviço.
- RNF-12: O sistema deve realizar testes de segurança regulares e análises de vulnerabilidades para identificar e corrigir potenciais brechas de segurança na aplicação.
- RNF-13: O sistema deve adotar práticas de desenvolvimento ágil e integração contínua, garantindo entregas frequentes e atualizações de software sem interrupções significativas para os usuários.


