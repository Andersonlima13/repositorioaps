
# Descrição do Ambiente de Uso

## Ambiente de Uso

A seguir, estão descritos os ambientes nos quais o sistema **UniPass** será utilizado:

1. **Ambiente do Cliente:**  
   Este ambiente é destinado aos usuários finais, que podem ser **estudantes** ou **motoristas**.  
   - **Estudantes:** Utilizam o sistema para consultar a disponibilidade de vagas no transporte, realizar reservas, acompanhar o trajeto dos ônibus em tempo real e acessar suas carteiras digitais.  
   - **Motoristas:** Acessam informações sobre itinerários, disponibilidade de vagas nos ônibus e mantêm comunicação direta com os agentes administrativos.  

   O acesso ao sistema ocorre via dispositivos móveis (smartphones e tablets) através de aplicativos para **Android** e **iOS**, ou ainda por navegadores web, como **Google Chrome, Mozilla Firefox, Microsoft Edge**, entre outros, utilizando uma conexão segura via **HTTPS**. O login é obrigatório para garantir o acesso autorizado.

2. **Ambiente Administrativo:**  
   Utilizado pelos agentes administrativos, este ambiente permite a gestão completa do sistema, incluindo:  
   - Cadastro e gerenciamento de usuários (estudantes e motoristas)  
   - Gestão de rotas e itinerários  
   - Controle de reservas de vagas  
   - Comunicação com motoristas e estudantes  

   O acesso é realizado via navegador web em desktops ou notebooks, mediante autenticação por login e senha.

3. **Ambiente de Teste:**  
   Este ambiente é reservado para desenvolvimento, validação e homologação de novas funcionalidades e correções de erros antes de serem disponibilizadas no ambiente de produção.  
   É acessível apenas para usuários autorizados, via navegador web, utilizando credenciais específicas para testes.

---

## Necessidades Principais Quanto ao Ambiente

A tabela abaixo apresenta as principais necessidades dos usuários relacionadas à qualidade, desempenho, segurança, usabilidade e confidencialidade do sistema **UniPass**, bem como suas prioridades, soluções atuais e propostas de melhoria:

| Necessidade                                                                                                                                                | Prioridade | Interesse                                                                                                                                        | Solução Atual                                                                                                                | Soluções Propostas                                                                                                                                                                                                                                                                                             |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Qualidade:** Sistema confiável, estável e livre de erros.                                                                                                | Alta       | Usuários esperam um sistema funcional, sem falhas que impactem a experiência ou funcionalidades essenciais.                                     | Testes manuais e alguns testes unitários realizados pela equipe de desenvolvimento.                                         | Implementar uma suíte de testes automatizados (unitários, integrados e end-to-end) e práticas de qualidade contínua (CI/CD).                                                                                                                                                                                   |
| **Desempenho:** Resposta rápida e eficiente, mesmo em dispositivos com menor poder de processamento.                                                      | Alta       | Garantir que o sistema responda rapidamente às ações dos usuários, sem lentidões.                                                               | Servidor dedicado e monitoramento constante.                                                                                 | Melhorias na arquitetura, utilização de cache, otimização de consultas no banco de dados e adoção de microsserviços para balancear a carga.                                                                                                                                                                   |
| **Escalabilidade:** Suporte ao crescimento no número de usuários e demandas.                                                                               | Alta       | Manter a estabilidade e o bom desempenho, mesmo em horários de pico e com aumento significativo de usuários.                                   | Uso de servidores em nuvem e distribuição de carga.                                                                         | Adotar arquiteturas serverless, autoscaling, balanceamento de carga inteligente e armazenamento escalável na nuvem.                                                                                                                                                                                           |
| **Segurança:** Proteção contra acessos não autorizados, ataques e vazamento de dados.                                                                     | Alta       | Garantia de que dados sensíveis estejam protegidos e que o sistema seja resiliente contra ameaças cibernéticas.                                | Autenticação com login e senha, criptografia de dados e controle de acesso.                                                 | Implementar autenticação multifator (MFA), OAuth, certificados SSL/TLS robustos, firewalls, monitoramento em tempo real, backup criptografado e políticas de gestão de vulnerabilidades.                                                                                                                       |
| **Usabilidade:** Interface simples, intuitiva e acessível para todos os perfis de usuário.                                                                | Moderada   | Usuários devem operar o sistema com facilidade, sem necessidade de treinamento prévio.                                                          | Interface simples e amigável.                                                                                                | Realizar testes de usabilidade com o público-alvo, seguir padrões de design UX/UI modernos e aplicar melhorias contínuas baseadas no feedback dos usuários.                                                                                                                                                   |
| **Tempo de Resposta em Tempo Real:** Atualização instantânea da ocupação das vagas e confirmação de reservas.                                             | Alta       | Estudantes precisam garantir sua reserva de vaga no transporte em tempo real, evitando duplicidade e conflitos.                                | Monitoramento constante do tempo de resposta.                                                                               | Uso de tecnologias como **WebSocket** para atualizações em tempo real, otimização de processos críticos, implementação de semáforos e controle de concorrência para garantir a integridade na reserva simultânea.                                                                                             |
| **Confidencialidade:** Garantia de privacidade e proteção dos dados pessoais e sensíveis dos usuários.                                                    | Alta       | Usuários confiam que seus dados estarão protegidos contra acessos não autorizados e uso indevido.                                              | Controle de acesso, criptografia de dados sensíveis e monitoramento por logs.                                               | Realizar auditorias periódicasanonimização de dados quando necessário e adoção de práticas robustas de segurança da informação, incluindo DLP (Data Loss Prevention) e criptografia ponta a ponta. |

---
