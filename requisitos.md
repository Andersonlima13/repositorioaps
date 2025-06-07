Os requisitos não-funcionais são descritos a seguir.

## Disponibilidade

- **[RNF001]** - O sistema deve ser desenvolvido de forma que possa ser implantado em qualquer plataforma.
- **[RNF011]** - O sistema deve ser desenvolvido de forma que possa ser executado em qualquer dispositivo e com sincronização dos dados com o servidor no sistema de catracas.
- **[RNF015]** - O sistema deve ser ter um tempo de resposta eficiente de no maximo 4 segundos ao aproximar o cartão ou dispositivo móvel na catraca.
- **[RNF012]** - O sistema deve estar disponível 24 horas por dia, 7 dias por semana, 365 dias por ano.
- **[RNF013]** - O sistema deve ser desenvolvido de forma que possa ser escalável, ou seja, deve ser possível aumentar a capacidade de armazenamento de dados e de processamento de requisições sem que haja perda de desempenho.
- **[RNF013]** - O sistema deve suportar multiplas requisições simultâneas em horarios de pico , sem problemas de time-out.
- **[RNF014]** - O sistema deve apresentar funcionamento mesmo sem acesso a internet, guardando algumas informações em memória cache.


## Privacidade e segurança

- **[RNF002]** - O sistema deve ser desenvolvido de forma que os dados dos clientes sejam protegidos e não sejam acessíveis por terceiros.
- **[RNF003]** - O sistema deve atender aos requisitos de privacidade da LGPD (Lei Geral de Proteção de Dados).
- **[RNF014]** - O sistema deve ser desenvolvido de forma que os dados pessoais dos clientes sejam criptografados, como endereço de e-mail, senha, nome completo, cidade e estado. A criptografia deverá ser realizada com o algoritmo SHA-512, e deve impossibilitar a recuperação dos dados originais.
- **[RNF015]** - O sistema deve contar com um web-firewalls que impeçam ações maliciosas dentro da aplicação.
- **[RNF015]** - O sistema deve garantir que apenas usuários previamente cadastrados possuam acesso.

## Usabilidade

- **[RNF004]** - O sistema deve ser desenvolvido de forma que seja fácil de usar e de fácil aprendizado, de forma que os usuários não precisem de treinamento para utilizá-lo.
- **[RNF019]** - O sistema deve ser desenvolvido de forma que possa ser acessado por pessoas com deficiência visual, auditiva e física.
- **[RNF020]** -  O sistema deve possuir interface simplificada , no padrão de aplicativos utilizados pelo publico alvo da aplicação.

## Suportabilidade

- **[RNF005]** - O sistema deve ser desenvolvido de forma que possa ser executado nos três principais navegadores da web: Google Chrome, Mozilla Firefox e Microsoft Edge através de um computador com sistema operacional Windows, Linux ou Mac OS, bem como tablets e smartphones com sistema operacional Android ou iOS.
- **[RNF006]** - O sistema deve ser desenvolvido de forma que possa ser executado em aplicativos nativos para Android e iOS.
- **[RNF007]** - O sistema deve ter uma exigência mínima de cpu e gpu do aparelho móvel.
- **[RNF008]** - O sistema deve ser otimizado para ter um baixo consumo de mémoria Ram e rom do aparelho, exigindo o minimo de 1gb Ram e 8gb de Rom
- **[RNF009]** - O sistema deve ser compatível com versões 6.0 do android em diante, e versão 10.0.0 do IOS em diante
- **[RNF009]** - O sistema deve apresentar design responsivo e adaptavévl para qualquer aparelho ou dispositivo similar.
- 
## Interoperabilidade

- **[RNF007]** - O sistema deve ser desenvolvido de forma que possa ser integrado com a API do Google para autenticação de usuários.
- **[RNF007]** - O sistema deve ser integrado com o sistema de catracas, de modo que não haja problemas de autenticacação
- **[RNF007]** - O sistema deve levar no maximo 3.5 segundos para sincronizar o cartão físico ou disposito móvel com o sistema de catracas 

  
## Manutenibilidade

- **[RNF008]** - O sistema deve ser desenvolvido de forma que possa ser facilmente atualizado e mantido, preferencialmente, de maneira automatizada.
- **[RNF009]** - O sistema deve ser desenvolvido de forma que possa ser facilmente testado e validado, de forma manual e automatizada.
- **[RNF016]** - O sistema deve ser documentado de forma que possa ser facilmente compreendido por terceiros e para facilitar a manutenção do sistema
- **[RNF016]** - O sistema deve ser desenvolvido seguindo os padrões estabelecidos pelo clean code

## Desempenho

- **[RNF010]** - O sistema deve ser desenvolvido de forma que possa ser executado em qualquer dispositivo com conexão à internet, com velocidade de conexão de no mínimo 1 Mbps com tempo de resposta de no máximo 5 segundos.
- **[RNF010]** - O sistema deve ser otimizado para apresentar baixo consumo de memória e processamento, visando melhor desempenho.
- **[RNF012]** - O sistema deve ter um baixo consumo de dados móveis, utilizando de tecnicas como o caching de dados

## Implementação

- **[RNF015]** - O sistema deve ser desenvolvido com APIs de acesso aos dados, para que possa ser integrado com outros sistemas.
- **[RNF019]** - O sistema deve ser integrado com uma API do google maps , para mapeamento das rotas itinerárias.
- **[RNF017]** - O sistema deve ser envolvido em um banco de dados hospedado em nuvem , com balanceamento de carga dos dados
- **[RNF018]** - O sistema deve implementar sockets de comunicação para sincronizar com o sistema na catraca.

## Implantação

- **[RNF017]** - O sistema deve ser desenvolvido de forma que possa ser implantado em qualquer plataforma de software atualizada. (excluir)
- **[RNF018]** - O sistema deve ser desenvolvido de forma que possa ser implantado em plataformas de hardware x64 e ARM64, com arquitetura mínima de 64 bits. (excluir)
- **[RNF020]** - O sistema deve ser verificado quanto ao desempenho mínimo tolerado dos lados servidor e clientes. As especificações sobre pré-requisitos de hardware e  software para a execução do sistema devem ser apresentadas em uma página de pré-requisitos, que deve ser acessível a partir do rodapé do site. (excluir)
- **[RNF021]** - O sistema deve ser desenvolvido de forma que possa ser implantado em qualquer navegador web.

