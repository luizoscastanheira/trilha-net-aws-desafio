# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 01/09/2025
Empresa: Abstergo Industries
Responsável: Luiz Otávio da Silva Castanheira

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Luiz Otávio da Silva Castanheira. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implemententação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:
- Ferramenta: Elastic Cloud Computing - Amazon EC2.
- Foco da Ferramenta: Fornecer capacidade computacional e redimensionável que nos fornecerá:
-- Redução de custos devido a redução drástica de necessidade de aquisição e gerenciamento de infraestrutura de servidores locais passando para instâncias gerenciadas em nuvem;
--- CPU, Memória, Rede, Armazenamento e Sistema Operacional totalmente configuráveis e gerenciáveis em cloud;
-- Otimização de instâncias de acordo com a necessidade da empresa, com foco em armazenamento e transações online;
-- Definição de preços conforme uso;
- Descrição de caso de uso - como será a implementação:
    A implementação se dará de forma gradual, onde serão primeiro criadas, configuradas e testadas as instâncias EC2 correspondentes aos servidores locais e em seguida migrados os serviços nos quais os clientes deixarão de acessar os servidores e acessarão para os mesmos serviços os servidores já instanciados em cloud, setor a setor. 
    Teremos no mínimo duas semanas de teste e avaliação no primeiro servidor/instância EC2, incluindo teste de acesso e stress para na semana seguinte ter a validação do processo inicial de migração ou fazer ajustes e novos testes antes de continuar a migração de servidores/serviços restante.
    Esta etapa será desenvolvida pelo ADM de Sistemas e Redes em conjunto com a equipe interna de TI e o pessoal AWS.

Etapa 2:
- Amazon Elastic File System - EFS.
- Foco da ferramenta: Fornecer capacidade de armazenamento em um sistema de arquivos totalmente "elástico", escalável automáticamente conforme necessidade de uso. A mesma produzirá uma redução de custos no que tange a necessidade de aquisição e manutenção de diferentes sistemas de armazenamento e backup que passaria de local para cloud sendo parte do pacote de serviços contratados.
- Descrição de caso de uso - como será a implementação:
    Em primeiro lugar vamos fazer um processo interno de "limpar o lixo" onde cada setor deverá definir o que é fato importante ser guardado em termos de arquivos. Não nos referimos aqui aos bancos de dados, mas sim arquivos gerais da empresa que hoje estão nos servidores de arquivos centralizados na empresa e nas estações de trabalho dos colaboradores sendo vedado arquivamentos "pessoais" que não tenha relação com o trabalho.
    Após esse processo, haverá a migração dos arquivos para a nuvem sendo uma política mais rígida de cotas a ser implementada visando uma otimização do uso de espaço e evitando desperdício.
    Esta etapa será desenvolvida pelo ADM de Sistemas e Redes em conjunto com a equipe interna de TI e o pessoal AWS.

Etapa 3:
- Amazon Relation Database Service - Amazon RDS
- Foco da ferramenta: Fornecer serviços de Bancos de Dados Relacional com fácil gerenciamento e otimização, backps, redundância, failover e recuperação de desastres;
- O uso do RDS facilitará a manutenção de grandes bases de dados, hoje gerenciadas em servidores locais e com capacidade de escalonamento limitada por orçamento e recusos tecnicos. Ao migrar para cloud haverá redução de custos no que tange a já referida capacidade de escalonamento bem como com a prevenção de perdas e sistemas de beckup. 
- Descrição de caso de uso - como será a implementação:
    É definitivamente um dos processo mais delicados de toda a migração para clound, realizar a migração do Banco de Dados do servidor local para o serviço correspondente na nuvem AWS. Esta é uma etapa que requer muita atenção.
    Deverá primeiro certificar-se da existência de um backup de todo banco de dados e em seguida iniciar o processo de migração com acompanhamento da equipe especializada da fornecedora do serviço que além de acompanhar a migração, dará o treinamento necessário à equipe de TI interna.
    Esta etapa será desenvolvida pelo DBA em conjunto com a equipe interna de TI e o pessoal AWS.

## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado a redução geral de custos de aquisição, gerenciamento e manutenção de hardware bem como o mesmo efeito no gerenciamento de serviços, sendo parte dos recursos economizados liberados para foco em segurança, treinamento e capacidade de rede/conectividade*, o que aumentará a eficiência e a produtividade da empresa. 
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias complementares às inicialmente adotas no projeto (por exemplo, complementar o Amazon EC2 com o Amazon EC2 AutoScalling) que possam melhorar ainda mais os preocesso da empresa.

## Anexos
Sem necessidade de anexos no momento.

Assinatura do Responsável pelo projeto:
Luiz Otávio da Silva Castanheira