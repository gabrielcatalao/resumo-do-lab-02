# Resumo do Lab 02

Este repositório foi criado para montar um resumo do que foi estudado no módulo: Benefícios da Computação em Nuvem.

O módulo levantou os seguintes temas:

- Disponibilidade e Escalabilidade
- Confiabilidade e Previsibilidade
- Segurança e Governança
- Gerenciamento

### Disponibilidade 
Diz respeito a garantir a máxima disponibilidade do serviço. Esssa disponibilidade é garantiada em contrato a través do SLA contratado no momento da criação da arquitedura do ambiente.

### Escalabilidade
Garante o dimensionamento do ambiente de forma elástica, podendo aumentar ou reduzir os recursos de acodo com a necessidade. Essa escalabilidade pode ser *Vertical* ou *Horizontal*.
  - Vertical - Possibilidade de aumentar ou diminuir a capacidade de um recurso, ex. CPU, RAM ou Armazenamento.
  - Horizontal - Possibilidade de aumentar ou diminuir recursos, ex. VMs, Container. Essa expansão pode acontecer de forma manual ou automática.

### Confiabilidade 
Um design descentralizado somado com o dimencionamento de um SLA de acondo com a demanda, gera um ambiente confiavel e resiliente, garantindo a recuperação em momento de falha e continuidade de funcionamento.

### Previsibilidade
A previsibilidade na nuvem pode ser focada na previsibilidade de *desempenho* e de *custo*, assim, permitindo que avancemos com confiança. 
  - Desempenho - Previsibilidade dos recursos necessários. Alguns conceitos da nuvem que dão suporte a previsibilidade de desempenho são: dimensionamento automático, balanceamento de carga e alta disponibilidade.
  - Custo - Previsibilidade de custo está ligado em prever ou projetar os gastos com a nuvem, podendo acompanhar e monitorar em tempo real os recursos, garantindo que esteja sendo usando da forma mais eficiente, assim podendo prever custos futuros e ajusta-los conforme a necessidade. Algumas ferramentas como a Calculadora de Preços e o TCO (Custo Total de Propriedade) estão disponivéis para auxiliar na previsibilidade.

### Segurança
O topico de segurança diz respeito a segurança de recursos e a garantia de que tudo esteja no ar e funcionando.Prevenção de ataques internos e externos. Permite utilizar ferramentas para realizar patches e manutençãoes de forma automática por meio de plataformas e softwares como serviços. O provedor tem a responsabilidade de prover essas ferramentas, mas a responsabilidade de aplicar é do cliente.

### Governança 
Auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com os padrões corporativos internos, assim oferecendo estratégias de mitigação e resolução de problemas. Trabalha em conjunto com a segurança, o resultado das regras criadas pela segurança são os padrões geridos pela governança. Pela cloud podemos utilizar regras prontas e criar regras que possam atender os padrões de mercado e os padrões individueais de cada empresa.

### Gerenciamento 
Temos duas frente para o tópico de gerenciamento, o *gerenciamento da nuvem* e o *gerenciamento em nuvem*.
  - Gerenciamento da nuvem - Diz respeito ao gerenciamento dos recusos. Escalabilidade, implantação de recursos, monitoramento de recursos, alertas automáticos com base em métricas preestabelecidas, entre outros.
  - Gerenciamento em nuvem - Outro tipo de gerenciamento é a forma que o gerenciamento da nuvem é feito, quais formas podemos gerenciar o ambiente e seus recursos. Via CLI, portal web, via powershell e também por APIs.
