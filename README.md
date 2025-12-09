🚀 Tutorial de Instalação do XTREAM SERVER OPENSOURCE 🇧🇷
Este tutorial irá guiá-lo pelo processo de instalação e configuração do XTREAM SERVER OPENSOURCE no seu servidor.

Passo 1: Preparar o Ambiente
Certifique-se de ter um servidor com as seguintes tecnologias instaladas:

Apache
PHP 8.x
MySQL ou MariaDB
Passo 2: Importar o Banco de Dados
Localize o arquivo SQL do banco de dados dentro da pasta /Banco de dados.

Passo 3: Configurar os Detalhes do Banco de Dados
Acesse o arquivo de configuração do banco de dados:

Navegue até a pasta /api/controles/ no diretório onde você extraiu os arquivos. Abra o arquivo db.php com um editor de texto.

Configure os dados do banco de dados: No arquivo db.php, você verá uma função para definir os dados de conexão com o banco de dados. Edite os seguintes campos para refletir as configurações do seu banco de dados:

$endereco = "localhost";

$banco = "xtserveropensource"; // nome do seu banco de dados

$dbusuario = "root"; // usuario do seu banco de dados

$dbsenha = "032530"; // senha do seu banco de dados

dados de acesso
usuario: admin
senha: admin
