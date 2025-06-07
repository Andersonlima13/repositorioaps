### Disponibilidade

- **[RNF001]** - O sistema deve ser desenvolvido de forma que possa ser implantado em qualquer plataforma.

- **[RNF002]** - O sistema deve ser desenvolvido de forma que possa ser executado em qualquer dispositivo e com sincronização dos dados com o servidor no sistema de catracas.

- **[RNF003]** - O sistema deve ser ter um tempo de resposta eficiente de no maximo 4 segundos ao aproximar o cartão ou dispositivo móvel na catraca.

- **[RNF004]** - O sistema deve estar disponível 24 horas por dia, 7 dias por semana, 365 dias por ano.

- **[RNF005]** - O sistema deve ser desenvolvido de forma que possa ser escalável, ou seja, deve ser possível aumentar a capacidade de armazenamento de dados e de processamento de requisições sem que haja perda de desempenho.

- **[RNF006]** - O sistema deve suportar multiplas requisições simultâneas em horarios de pico , sem problemas de time-out.

- **[RNF007]** - O sistema deve apresentar funcionamento mesmo sem acesso a internet, guardando algumas informações em memória cache.

### Privacidade e segurança
- **[RNF008]** - O sistema deve ser desenvolvido de forma que os dados dos clientes sejam protegidos e não sejam acessíveis por terceiros.

- **[RNF009]** - O sistema deve atender aos requisitos de privacidade da LGPD (Lei Geral de Proteção de Dados).

- **[RNF010]** - O sistema deve ser desenvolvido de forma que os dados pessoais dos clientes sejam criptografados, como - endereço de e-mail, senha, nome completo, cidade e estado. A criptografia deverá ser realizada com o - algoritmo SHA-512, e deve impossibilitar a recuperação dos dados originais.

- **[RNF011]** - O sistema deve cont- ar com um web-firewalls que impeçam ações maliciosas dentro da aplicação.

- **[RNF012]** - O sistema deve garantir que apenas usuários previamente cadastrados possuam acesso.

### Usabilidade
- **[RNF013]** - O sistema deve ser desenvolvido de forma que seja fácil de usar e de fácil aprendizado, de forma que os usuários não precisem de treinamento-  para utilizá-lo.

- **[RNF014]** - O sistema deve ser desenvolvido de forma que possa ser acessado por pessoas com deficiência visual, auditiva e física.

- **[RNF015]** - O sistema deve possuir interface simplificada, no padrão de aplicativos utilizados pelo publico alvo da aplicação.

### Suportabilidade
- **[RNF016]** - O sistema deve ser desenvolvido de forma que possa ser executado nos três principais navegadores da web: Google Chrome, Mozilla Firefox e Microsoft Edge através de um computador com sistema operacional Windows, Linux ou Mac OS, bem como tablets e smartphones com sistema operacional Android ou iOS.

- **[RNF017]** - O sistema deve ser desenvolvido de forma que possa ser executado em aplicativos nativos para Android e iOS.

- **[RNF018]** - O sistema deve ter uma exigência mínima de cpu e gpu do aparelho móvel.

- **[RNF019]** - O sistema deve ser otimizado para ter um baixo consumo de mémoria Ram e rom do aparelho, exigindo o minimo de 1gb Ram e 8gb de Rom

- **[RNF020]** - O sistema deve ser compatível com versões 6.0 do android em diante, e versão 10.0.0 do IOS em diante

- **[RNF021]** - O sistema deve apresentar design responsivo e adaptavévl para qualquer aparelho ou dispositivo similar.

### Interoperabilidade
- **[RNF022]** - O sistema deve ser desenvolvido de forma que possa ser integrado com a API do Google para autenticação de usuários.

- **[RNF023]** - O sistema deve ser integrado com o sistema de catracas, de modo que não haja problemas de autenticacação

- **[RNF024]** - O sistema deve levar no maximo 3.5 segundos para sincronizar o cartão físico ou disposito móvel com o sistema de catracas

### Manutenibilidade
- **[RNF025]** - O sistema deve ser desenvolvido de forma que possa ser facilmente atualizado e mantido, preferencialmente, de maneira automatizada.

- **[RNF026]** - O sistema deve ser desenvolvido de forma que possa ser facilmente testado e validado, de forma manual e automatizada.

- **[RNF027]** - O sistema deve ser documentado de forma que possa ser facilmente compreendido por terceiros e para facilitar a manutenção do sistema

- **[RNF028]** - O sistema deve ser desenvolvido seguindo os padrões estabelecidos pelo clean code

### Desempenho
- **[RNF029]** - O sistema deve ser desenvolvido de forma que possa ser executado em qualquer dispositivo com conexão à internet, com velocidade de conexão de no mínimo 1 Mbps com tempo de resposta de no máximo 5 segundos.

- **[RNF030]** - O sistema deve ser otimizado para apresentar baixo consumo de memória e processamento, visando melhor desempenho.

- **[RNF031]** - O sistema deve ter um baixo consumo de dados móveis, utilizando de tecnicas como o caching de dados

### Implementação
- **[RNF032]** - O sistema deve ser desenvolvido com APIs de acesso aos dados, para que possa ser integrado com outros sistemas.

- **[RNF033]** - O sistema deve ser integrado com uma API do google maps, para mapeamento das rotas itinerárias.

- **[RNF034]** - O sistema deve ser envolvido em um banco de dados hospedado em nuvem, com balanceamento de carga dos dados

- **[RNF035]** - O sistema deve implementar sockets de comunicação para sincronizar com o sistema na catraca.
