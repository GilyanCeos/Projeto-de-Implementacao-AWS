# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 25/08/2025 | 
Empresa: Abstergo Industries | 
Responsável: Gilyan Santos

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Gilyan Santos. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de *realizar diminuição de custos imediatos* e preparar a empresa para atuar como hub de distribuição no setor farmacêutico.

## Descrição do projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos.
A seguir, serão descritas as etapas do projeto:

### Etapa 1

**Amazon EC2**

**Foco**: Hospedagem de sistemas internos e infraestrutura escalável.

**Caso de uso**: A empresa atualmente utiliza servidores locais para rodar sistemas de gestão de estoque e pedidos. Com o Amazon EC2, será possível migrar esses sistemas para a nuvem, reduzindo custos com hardware físico, manutenção e energia elétrica. A escalabilidade permitirá adequar os recursos de acordo com a demanda, evitando desperdícios.

### Etapa 2

**Amazon RDS**

**Foco**: Banco de dados relacional gerenciado.

**Caso de uso**: Todos os dados de clientes, farmácias parceiras, pedidos e produtos serão centralizados em um banco de dados seguro e de alta disponibilidade. O Amazon RDS elimina custos com licenciamento e manutenção de servidores de banco de dados locais, além de garantir backups automáticos e escalabilidade de forma simplificada.

### Etapa 3

**Amazon S3**

**Foco**: Armazenamento seguro e escalável de arquivos e documentos.

**Caso de uso**: A empresa precisa armazenar e compartilhar documentos como bulas, catálogos de produtos, relatórios fiscais e arquivos de auditoria. O Amazon S3 oferecerá alta durabilidade (99,999999999%), baixo custo por GB e acesso facilitado, eliminando a necessidade de servidores de arquivos físicos.

## Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado:
- Redução de custos imediatos com infraestrutura física, energia e manutenção;
- Maior escalabilidade e flexibilidade operacional;
- Segurança avançada no armazenamento e gerenciamento de dados;
- Preparação da empresa para expansão como hub de distribuição no setor farmacêutico.
- Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias AWS, como serviços de análise de dados (Amazon QuickSight) e automação de processos logísticos (AWS Lambda), que podem otimizar ainda mais os processos da empresa.

## Anexos

### Anexo 1 – Comparativo de Custos (On-premises vs AWS)

| Item                                | Infraestrutura Local (on-premises)                                         | AWS (EC2, RDS, S3)                                    | Ganhos                                         |
| ----------------------------------- | -------------------------------------------------------------------------- | ----------------------------------------------------- | ---------------------------------------------- |
| **Servidores físicos**              | Aquisição de hardware (média R\$ 120.000 a cada 5 anos) + manutenção anual | Instâncias EC2 pagas sob demanda ou reservadas        | Redução de até 60% em custos de TI             |
| **Banco de Dados**                  | Licenciamento + equipe dedicada para manutenção                            | Amazon RDS gerenciado (licença e manutenção inclusas) | Redução de até 50% em custos de banco de dados |
| **Armazenamento de arquivos**       | Servidores de rede + backup em fitas/HDs externos                          | Amazon S3 com alta durabilidade e baixo custo por GB  | Redução de até 70% em armazenamento e backup   |
| **Energia elétrica e refrigeração** | Alto consumo mensal em data center próprio                                 | Eliminado (infraestrutura em nuvem)                   | Economia de energia e espaço físico            |

### Anexo 2 – Arquitetura Simplificada do Projeto

| Usuários internos da Abstergo acessam sistemas pelo navegador ou aplicativo → conectados a instâncias EC2 (ERP e pedidos).

| Banco de dados centralizado no Amazon RDS → integrado aos sistemas de estoque, clientes e farmácias.

| Arquivos e relatórios armazenados no Amazon S3 → acessíveis com segurança para gestores e parceiros.

### Anexo 3 – Benefícios Imediatos Identificados

**Amazon EC2**:
- Eliminação da necessidade de compra de novos servidores físicos.
- Redução de tempo para provisionar novos ambientes (de semanas para minutos).

**Amazon RDS**:
- Backup automático e replicação, garantindo continuidade do negócio.
- Suporte multi-AZ (alta disponibilidade sem investimento em servidores extras).

**Amazon S3**:
- Armazenamento praticamente ilimitado.
- Custos extremamente baixos (a partir de US$ 0,023 por GB/mês).

### Anexo 4 – Roadmap de Expansão Futuro (Próximos Passos)

**Curto prazo** (0-6 meses):
- Migração de sistemas internos para EC2.
- Centralização do banco de dados em RDS.
- Implementação do repositório de documentos no S3.

**Médio prazo** (6-12 meses):
- Implementar AWS CloudWatch para monitoramento de desempenho.
- Uso de AWS Backup para compliance e auditorias farmacêuticas.

***Longo prazo** (12-24 meses):
- Integração de AWS Lambda para automação de processos logísticos.
- Uso de Amazon QuickSight para relatórios analíticos e insights de vendas.

### Anexo 5 – Estudo de Caso Similar (Farmacêutica)

Empresas do setor farmacêutico que migraram para AWS relatam:
- Redução de até 40% em custos de TI no primeiro ano.
- Maior resiliência em auditorias regulatórias devido ao compliance da AWS (HIPAA, GDPR, LGPD).
- Escalabilidade em picos sazonais, como campanhas de vacinação ou promoções.



## Assinatura do responsável pelo projeto:
### *Gilyan Santos*