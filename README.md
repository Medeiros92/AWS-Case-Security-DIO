# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

**Data:** 22/07/2024 
**Empresa:** Abstergo Industries  
**Responsável:** Thales Medeiros

---

#### Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Thales Medeiros. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto com os serviços da AWS, com a finalidade de aumentar a segurança na empresa.

---

#### Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

---

**Medida 1: AWS Identity and Access Management (IAM)**

**Descrição do caso de uso:**  
AWS IAM permite gerenciar o acesso aos serviços e recursos da AWS de maneira segura. Com o IAM, é possível criar e gerenciar usuários e grupos, além de usar permissões para permitir ou negar acesso aos recursos da AWS.

**Etapas da Implementação:**
1. Criação de políticas de segurança detalhadas para controlar o acesso aos recursos.
2. Configuração de roles para serviços específicos, garantindo que apenas entidades autorizadas possam acessar determinados recursos.
3. Implementação de autenticação multifator (MFA) para todos os usuários administrativos.

**Benefícios:**  
A utilização do IAM permite um controle granular sobre quem tem acesso a quais recursos, reduzindo significativamente o risco de acesso não autorizado e melhorando a segurança geral do ambiente.

---

**Medida 2: AWS CloudTrail**

**Descrição do caso de uso:**  
AWS CloudTrail permite monitorar e registrar a atividade da conta da AWS. Ele fornece um histórico dos eventos da conta da AWS, incluindo ações realizadas por meio do console da AWS, AWS SDKs, ferramentas de linha de comando e outros serviços da AWS.

**Etapas da Implementação:**
1. Ativação do AWS CloudTrail em todas as regiões para garantir uma cobertura completa dos eventos.
2. Configuração de logs para serem armazenados de forma segura no Amazon S3 com criptografia.
3. Implementação de alarmes no Amazon CloudWatch para monitorar atividades suspeitas ou não autorizadas.

**Benefícios:**  
O uso do CloudTrail proporciona visibilidade completa sobre as ações realizadas na infraestrutura AWS, facilitando auditorias de segurança, detecção de atividades anômalas e resposta a incidentes de segurança.

---

**Medida 3: AWS Trusted Advisor**

**Descrição do caso de uso:**  
AWS Trusted Advisor é uma ferramenta que ajuda a otimizar a infraestrutura da AWS em termos de segurança, desempenho, custo e tolerância a falhas. Ele fornece recomendações para melhorar a segurança e a eficiência dos recursos da AWS.

**Etapas da Implementação:**
1. Ativação do AWS Trusted Advisor para revisar a infraestrutura atual.
2. Avaliação das recomendações de segurança fornecidas pelo Trusted Advisor.
3. Implementação das recomendações de segurança, como a ativação de MFA para todas as contas, revisão de permissões de segurança e melhoria das configurações de segurança.

**Benefícios:**  
A utilização do AWS Trusted Advisor permite identificar rapidamente problemas de segurança e implementar as melhores práticas recomendadas, aumentando a segurança geral e a eficiência da infraestrutura da AWS.

---

#### Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado melhorar significativamente a segurança do ambiente da AWS, aumentando a visibilidade, o controle e a capacidade de resposta a incidentes. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

---

#### Anexos

1. [Manual de Políticas do IAM](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/)
2. [Guia de Configuração do CloudTrail](https://docs.aws.amazon.com/pt_br/awscloudtrail/latest/userguide/)
3. [Documentação do AWS Trusted Advisor e Recomendações de Segurança](https://docs.aws.amazon.com/pt_br/awssupport/latest/user/trusted-advisor.html)

---

**Assinatura do Responsável pelo Projeto:**

Thales Medeiros
