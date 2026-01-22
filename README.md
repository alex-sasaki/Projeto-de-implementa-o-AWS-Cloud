# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 22 de Janeiro de 2026
**Empresa:** Abstergo Industries 
**Responsável:**  Alex Sasaki

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Alex Sasaki**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Etapa 1:** * **Nome da ferramenta:** AWS Trusted Advisor
* **Foco da ferramenta:** Otimização de custos e melhores práticas.
* **Descrição de caso de uso:** Utilizado para identificar recursos ociosos, como instâncias EC2 com baixa utilização, volumes EBS não anexados e endereços Elastic IP não utilizados, permitindo a exclusão imediata desses ativos que geram cobranças desnecessárias.

**Etapa 2:** * **Nome da ferramenta:** Amazon S3 Intelligent-Tiering
* **Foco da ferramenta:** Gestão automática de armazenamento.
* **Descrição de caso de uso:** Implementado para mover automaticamente objetos armazenados no S3 para níveis de acesso mais baratos quando os padrões de acesso mudam, sem impacto na performance. Isso elimina a necessidade de análise manual de dados e reduz custos de armazenamento de longo prazo de forma imediata.

**Etapa 3:** * **Nome da ferramenta:** AWS Instance Scheduler
* **Foco da ferramenta:** Automação de instâncias.
* **Descrição de caso de uso:** Configurado para iniciar e interromper automaticamente instâncias de EC2 e RDS em ambientes de desenvolvimento e teste fora do horário comercial (noites e finais de semana), garantindo que a empresa pague apenas pelas horas em que os recursos estão sendo efetivamente utilizados.

## Conclusão
A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado **uma redução média de 20% a 30% na fatura mensal da AWS através da eliminação de desperdícios e automação de recursos**, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

* Planilha de previsão de economia mensal (Cost Explorer).
* Manual de configuração das janelas do Instance Scheduler.
* Relatório de auditoria do AWS Trusted Advisor.

**Assinatura do Responsável pelo Projeto:**

__________________________________
**Alex Sasaki**
