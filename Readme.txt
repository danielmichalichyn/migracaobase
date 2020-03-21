Este software serve para migrar bases de dados SQL Server 2000 para 2012 automaticamente. 
Sâo premissas do software que você já possua o SQL Server 2000 e o SQL Server 2012 instalado e configurado em seu servidor.
Este software irá apenas instalar o SQL Server 2008 para realizar a conversão da base 2000 para 2008 e então do 2008 para 2012, assim finalizando a atividade.

Abaixo se encontram algumas limitações e como executar o sistema.

Requisitos Mínimos para o sistema:
- .Net Framework 4.5 + 
- Sistema Operacional 64Bits
- Mémoria Ram 2 GB
- Espaço Disponível em disco local maior que 2GB mais o tamanho da base de dados a ser realizado o processo de migração.


Como executar o sistema:

A aplicação deverá ser executada via console/terminal/prompt 
Ao ser chamado o executável deverá ser passado, no mesmo comando, os parâmetros obrigatórios na seguinte sequência:
	- Nome do Servidor/Instância SQL para o Backup
	- Nome da Base de dados para o Backup
	- Usuário da base de Backup
	- Senha da base de Backup
	- Nome do Servidor/Instância SQL para o Restore
	- Nome da Base de dados para o Restore
	- Usuário da base de Restore
	- Senha da base de Restore
	- Caminho para o restore alocar os arquivos(.MDF, .NDF, .LOG) da base de dados. 
		*Este parâmetro não é obrigatório, caso for deixado em branco o Instalador alocará os arquivos no diretório padrão do SQL.
