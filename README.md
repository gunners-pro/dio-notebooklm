# Projeto DIO - NotebookLM

## Tema
Microsoft Azure Database Administrator

## Objetivo
Usar IA como apoio para estudos e revisão de conceitos.

## Fontes
- https://learn.microsoft.com/pt-br/credentials/certifications/azure-database-administrator-associate/?practice-assessment-type=certification
- https://www.youtube.com/watch?v=7qEXpbl7yhg

## Prompts usados
1. Faça um breve resumo sobre o que é a certicação Microsoft Azure Database Administrator.
2. Passos para a instalação do sql server.


## Miniguia
A certificação Microsoft Certified: Azure Database Administrator Associate é uma credencial de nível intermediário destinada a profissionais que administram infraestruturas de banco de dados SQL Server
,
. O objetivo central dessa certificação é validar a capacidade do administrador em gerenciar bancos de dados relacionais em ambientes de nuvem, locais e híbridos, utilizando as ofertas de banco de dados relacional do Microsoft PaaS (Plataforma como Serviço)
,
.
Os principais pontos que definem essa certificação incluem:
Tecnologias Abrangidas: O administrador deve ter conhecimento em Banco de Dados SQL do Azure, Instância Gerenciada de SQL do Azure, SQL Server em Máquinas Virtuais do Azure e SQL Server local
.
Responsabilidades do Profissional: O detentor desta certificação é responsável pelo gerenciamento, disponibilidade, segurança e otimização de desempenho das soluções de banco de dados
. Isso inclui a implementação de estratégias de migração e a automação de tarefas diárias utilizando ferramentas como o Transact-SQL (T-SQL)
,
.
Habilidades Avaliadas no Exame (DP-300): O exame de certificação foca em planejar e implementar recursos de plataforma de dados, configurar ambientes seguros, monitorar e otimizar recursos, além de planejar e configurar ambientes de Alta Disponibilidade e Recuperação de Desastres (HA/DR)
,
.
Manutenção da Credencial: A certificação tem uma frequência de renovação de 12 meses, que pode ser realizada sem custo através de avaliações online no Microsoft Learn
,
.

Para instalar e configurar o SQL Server e o SQL Server Management Studio (SSMS) de acordo com as recomendações mais recentes, siga este passo a passo baseado nas fontes:
1. Download dos Arquivos Oficiais
Acesse o site oficial da Microsoft para garantir que está baixando o pacote oficial e gratuito
.
Versão Recomendada: Escolha o SQL Server 2022 Developer. Embora versões mais recentes (como a 2025) possam estar disponíveis, a 2022 é considerada a mais estável e completa para desenvolvedores
.
Interface (SSMS): Baixe também o SQL Server Management Studio (SSMS), que é a interface necessária para gerenciar o banco de dados e criar tabelas
.
2. Instalação do SQL Server
Execute o instalador do SQL Server como administrador
.
Tipo de Instalação: Escolha a opção Personalizado (Custom). Isso permitirá baixar a mídia completa e configurar detalhes importantes
.
Nova Instalação: Na tela seguinte, selecione "Instalação" e depois "Nova instalação autônoma do SQL Server"
.
Dica do Firewall: Se o instalador der um erro no Firewall do Windows, desative-o temporariamente apenas durante a instalação para evitar bloqueios
.
Seleção de Recursos: Recomenda-se marcar "Selecionar tudo" para garantir que todas as funcionalidades necessárias para o funcionamento perfeito sejam instaladas
.
3. Configurações Críticas do Servidor
Instância: Pode-se utilizar a instância padrão (MSSQLSERVER)
.
Modo de Autenticação: Esta é uma das etapas mais importantes. Selecione o Modo Misto. Isso permite conectar-se tanto pela autenticação do Windows quanto por usuário e senha (criando o usuário administrador SA)
.
Usuário Atual: Não esqueça de clicar em "Adicionar usuário atual" para garantir que você tenha permissões de administrador
.
4. Instalação do Management Studio (SSMS)
Após finalizar a instalação do servidor, execute o instalador do SSMS
.
O processo é simples: basta clicar em "Instalar" e aguardar. Certifique-se de estar conectado à internet, pois o instalador baixa componentes em tempo real
.
5. Primeiro Acesso e Configuração de Conexão
Ao abrir o SSMS, para conectar-se ao servidor local, você pode usar o nome do seu computador ou simplesmente digitar um ponto (.) no campo "Nome do servidor"
.
Certificado de Segurança: Para evitar erros de conexão, é obrigatório marcar a opção "Habilitar certificado do servidor confiável" (Trust server certificate) nas opções de conexão
.
Após esses passos, o ambiente estará pronto para a criação de bancos de dados e consultas utilizando o Transact-SQL (T-SQL)
.

## Conclusão
O projeto mostrou como a IA pode ajudar na organização de estudos.
