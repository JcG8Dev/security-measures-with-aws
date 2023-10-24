Relatório de Implementação de Serviços AWS

Data: 24/10/2023
Empresa: Abstergo Industries
Responsável: Josiane Cristina Gonçalves

Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Josiane Cristina Gonçalves. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

Medida 1: - Amazon GuardDuty

- Detecção de Ameaças em Tempo Real: O Amazon GuardDuty é um serviço de detecção de ameaças que monitora continuamente a atividade da conta da AWS e o tráfego de rede para identificar possíveis ameaças em tempo real.

- Redução de Riscos de Segurança: Ele ajuda a reduzir os riscos de segurança, identificando atividades suspeitas, como tentativas de acesso não autorizado, comportamento anômalo e atividades maliciosas.

- Integração com outros serviços: GuardDuty pode ser integrado facilmente com outros serviços de segurança da AWS, como AWS CloudTrail e AWS Identity and Access Management (IAM).

O Amazon GuardDuty é uma ferramenta essencial para a detecção proativa de ameaças, o que pode ajudar a proteger os dados sensíveis da Abstergo, garantindo a conformidade regulatória e a segurança da empresa.

Implementação:

- Ative o Amazon GuardDuty em sua conta AWS e selecione as regiões que deseja monitorar.

- Configure notificações e alarmes para alertas de segurança.

- Analise os resultados das descobertas de ameaças em seu painel para responder a incidentes de segurança em tempo hábil.

Medida 2: AWS Identity and Access Management (IAM)

- Controle de Acesso: O IAM permite definir e gerenciar controles planejados para recursos na AWS, controlando quem tem acesso a quais recursos.

- Políticas de Segurança: Você pode criar políticas de segurança personalizadas para aplicar os princípios do menor privilégio, garantindo que os usuários tenham acesso apenas quando necessário.

- Auditoria de Acesso: O IAM permite rastrear quem fez o quê e quando, forneceu informações elaboradas para fins de auditoria.

A utilização adequada do AWS IAM é fundamental para estabelecer uma estrutura de controle de acesso robusta e garantir que os recursos e os dados da Abstergo sejam protegidos contra acesso não autorizado. 

Implementação:

- Configurar usuários, grupos e funções no IAM, atribuindo a cada uma das especificações específicas.

- Aplicar políticas de segurança que definem ações permitidas ou negadas em recursos da AWS.

- Monitore e revise periodicamente as configurações do IAM para garantir que apenas pessoas autorizadas tenham acesso aos recursos da empresa.

Medida 3: Logs de fluxo da Amazon VPC com Amazon VPC

- Isolamento de Rede: O Amazon VPC permite a criação de redes virtuais isoladas para os recursos da AWS, criando barreiras de segurança entre diferentes componentes da infraestrutura.
  
- Monitoramento de Tráfego: Os Amazon VPC Flow Logs permitem registrar informações sobre o tráfego de rede, incluindo origem, destino, portas e protocolos, para análise e monitoramento de segurança.

- Detecção de Anomalias: Analisando os registros de fluxo, é possível detectar atividades de redes suspeitas, como tentativa de acesso não autorizado.

Com a combinação do Amazon VPC e dos Amazon VPC Flow Logs, a Abstergo pode garantir a segregação eficaz de recursos e monitorar a atividade de rede para proteger contra ameaças de segurança, garantindo que apenas o tráfego autorizado seja permitido.

Implementação:

- Configure sua VPC para isolar recursos em redes virtuais privadas.

- Ativo os Amazon VPC Flow Logs para registrar ou tráfego de rede dentro da VPC.

- Analisar os logs para identificar anomalias e atividades suspeitas, permitindo ações de segurança proativas.

Conclusão

A implementação de ferramentas na empresa Abstergo tem como esperado o aumento da segurança, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Anexos

https://docs.aws.amazon.com/guardduty/latest/ug/what-is-guardduty.html

https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html

https://docs.aws.amazon.com/network-firewall/latest/developerguide/what-is-aws-network-firewall.html

Assinatura do Responsável pelo Projeto:

Josiane Cristina Gonçalves

