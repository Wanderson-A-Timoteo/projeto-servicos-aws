# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data**: 30/09/2024  
**Empresa**: Abstergo Industries  
**Responsável**: Wanderson Timóteo  

## Introdução
Este relatório apresenta o processo de implementação inicial de serviços AWS na empresa Abstergo Industries, conduzido por Wanderson Timóteo. A Abstergo Industries, uma empresa farmacêutica que atua como hub de distribuição para outras empresas e farmácias, busca expandir sua infraestrutura utilizando serviços de cloud computing da AWS. O foco desta implementação é criar uma base tecnológica escalável e segura, facilitando a operação como revendedora para diversas empresas.

## Descrição do Projeto
O projeto foi dividido em 3 etapas principais, cada uma apresentando uma ferramenta AWS crítica para os objetivos da Abstergo Industries.

### Etapa 1: Amazon EC2
- **Foco da ferramenta**: Provisão de servidores escaláveis para aplicações e sistemas internos.
- **Descrição de caso de uso**: A Abstergo Industries precisará de servidores robustos para gerenciar pedidos e o fluxo de distribuição para suas empresas parceiras. O Amazon EC2 permitirá a criação de instâncias escaláveis, fornecendo capacidade de computação conforme a demanda cresce. Essa etapa inclui a implantação de servidores web e servidores de banco de dados internos para gerir o sistema de estoque e pedidos da Abstergo Industries.

### Etapa 2: Amazon RDS (Relational Database Service)
- **Foco da ferramenta**: Banco de dados gerenciado e escalável.
- **Descrição de caso de uso**: Para manter um sistema de controle de estoque e vendas eficiente, a empresa precisará de um banco de dados seguro e de alta disponibilidade. O Amazon RDS será utilizado para hospedar um banco de dados relacional, como PostgreSQL ou MySQL, para armazenar informações sobre produtos, fornecedores e clientes, além de facilitar consultas rápidas e consistentes.

### Etapa 3: Amazon S3 (Simple Storage Service)
- **Foco da ferramenta**: Armazenamento de objetos seguro e escalável.
- **Descrição de caso de uso**: O Amazon S3 será utilizado para armazenar grandes volumes de documentos e registros, como catálogos de produtos, notas fiscais e históricos de transações. Sua capacidade de escalabilidade e segurança tornará mais eficiente o armazenamento de dados críticos, sem a necessidade de gerenciar infraestrutura física de armazenamento.

## Conclusão
A implementação inicial dos serviços Amazon EC2, Amazon RDS e Amazon S3 na Abstergo Industries proporcionará os seguintes benefícios:
- **Escalabilidade**: A infraestrutura da empresa poderá crescer junto com a demanda de distribuição de produtos para farmácias e outras empresas.
- **Segurança**: Com serviços gerenciados, a Abstergo terá acesso a camadas de segurança embutidas em cada serviço, garantindo que os dados de clientes e transações estejam protegidos.
- **Custo-benefício**: A utilização do modelo de pagamento conforme o uso da AWS reduzirá os custos operacionais, permitindo que a empresa invista em tecnologia de acordo com sua necessidade real.

Recomenda-se que a empresa continue explorando os serviços AWS, como AWS Lambda e Amazon CloudFront, para otimizar ainda mais suas operações e oferecer uma melhor experiência para seus parceiros e clientes.

## Anexos
1. [Manual de uso do Amazon EC2]
2. [Guia de implementação do Amazon RDS]
3. [Plano de escalabilidade do Amazon S3]

**Assinatura do Responsável pelo Projeto**:  
Wanderson Timóteo
