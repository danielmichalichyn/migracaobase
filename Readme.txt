Este software serve para migrar bases de dados SQL Server 2000 para 2012 automaticamente. 
S�o premissas do software que voc� j� possua o SQL Server 2000 e o SQL Server 2012 instalado e configurado em seu servidor.
Este software ir� apenas instalar o SQL Server 2008 para realizar a convers�o da base 2000 para 2008 e ent�o do 2008 para 2012, assim finalizando a atividade.

Abaixo se encontram algumas limita��es e como executar o sistema.

Requisitos M�nimos para o sistema:
- .Net Framework 4.5 + 
- Sistema Operacional 64Bits
- M�moria Ram 2 GB
- Espa�o Dispon�vel em disco local maior que 2GB mais o tamanho da base de dados a ser realizado o processo de migra��o.


Como executar o sistema:

A aplica��o dever� ser executada via console/terminal/prompt 
Ao ser chamado o execut�vel dever� ser passado, no mesmo comando, os par�metros obrigat�rios na seguinte sequ�ncia:
	- Nome do Servidor/Inst�ncia SQL para o Backup
	- Nome da Base de dados para o Backup
	- Usu�rio da base de Backup
	- Senha da base de Backup
	- Nome do Servidor/Inst�ncia SQL para o Restore
	- Nome da Base de dados para o Restore
	- Usu�rio da base de Restore
	- Senha da base de Restore
	- Caminho para o restore alocar os arquivos(.MDF, .NDF, .LOG) da base de dados. 
		*Este par�metro n�o � obrigat�rio, caso for deixado em branco o Instalador alocar� os arquivos no diret�rio padr�o do SQL.
