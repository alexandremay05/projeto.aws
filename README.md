# projeto.aws
projeto AWS para expandir vendas de farmácia
# RELATÃ“RIO DE IMPLEMENTAÃ‡ÃƒO DE SERVIÃ‡OS AWS

Data: [15/04/2026]
Empresa: Abstergo Industries 
ResponsÃ¡vel: [alexandre debacker]

## IntroduÃ§Ã£o
Este relatÃ³rio apresenta o processo de implementaÃ§Ã£o de ferramentas na empresa [alexandre:farmacias], realizado por [alexandre debacker]. O objetivo do projeto foi elencar 3 serviÃ§os AWS, com a finalidade de realizar diminuiÃ§Ã£o de custos imediatos.

## DescriÃ§Ã£o do Projeto
O projeto de implementaÃ§Ã£o de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especÃ­ficos. A seguir, serÃ£o descritas as etapas do projeto:

Etapa 1: 
- [Nome da ferramenta:AWS Compute Optimizer]
- [Foco da ferramenta:Este serviço utiliza aprendizado de máquina para analisar o histórico de utilização dos seus recursos. Ele identifica desperdícios de forma automática.]
- [DescriÃ§Ã£o de caso de uso:Ação Imediata: Indica quais instâncias EC2 ou bancos de dados RDS estão "superdimensionados" (maiores do que o necessário).
Redução de Custo: Sugere o tamanho ideal da instância, permitindo o downsizing imediato para tipos mais baratos.
Destaque: É gratuito para métricas padrão de instâncias EC2.
]

Etapa 2: 
- [Nome da ferramenta: AWS Budgets]
- [Foco da ferramenta:A primeira regra para economizar é não ter surpresas. O AWS Budgets permite que você tome ações automáticas antes que a conta chegue.]
- [DescriÃ§Ã£o de caso de uso:Ação Imediata: Configurar alertas de previsão que avisam quando o gasto estimado do mês exceder o valor definido.
Controle Rigoroso: Você pode configurar "Budget Actions" para aplicar políticas do IAM ou até interromper recursos se o limite for atingido.
Destaque: Permite visualizar o uso de Reserved Instances (RI) e Savings Plans para garantir que você não está perdendo dinheiro com descontos não utilizados.
]

Etapa 3: 
- [Nome da ferramneta:AWS Instance Scheduler]
- [Foco da ferramenta:Muitos custos vêm de ambientes de desenvolvimento ou teste que ficam ligados 24/7 sem necessidade.]
- [DescriÃ§Ã£o de caso de uso:Ação Imediata: Automatiza o início e a parada de instâncias EC2 e RDS.
Redução de Custo: Configurar para desligar recursos às 20h e ligar às 08h em dias úteis pode reduzir o custo desses recursos em até 70%.
Destaque: Implementado via CloudFormation, é uma solução de baixo esforço e alto impacto no faturamento mensal.
]



## ConclusÃ£o
A implementaÃ§Ã£o de ferramentas na empresa *[alexandre:farmacias] tem como esperado [benefÃ­cios das ferramentas:Implementar uma estratégia de contenção de gastos na infraestrutura AWS através de três frentes de ação: Otimização de Recursos, Automação de Disponibilidade e Governança Orçamentária. O foco é a redução de custos operacionais sem comprometer a performance ou a disponibilidade das cargas de trabalho críticas.]*, o que aumentarÃ¡ a eficiÃªncia e a produtividade da empresa. Recomenda-se a continuidade da utilizaÃ§Ã£o das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.



[Nome do ResponsÃ¡vel pelo Projeto:Alexandre Debacker]
