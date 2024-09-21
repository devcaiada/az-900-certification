# Microsoft Azure Essentials

![capa](https://github.com/devcaiada/az-900-certification/blob/main/assets/azure-capa.png?raw=true)

# Localizando Serviços por Categoria

### 1. Acesse o Portal do Azure:

- Navegue até o [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/) e faça login com suas credenciais da conta Microsoft.

### 2. Acesse o Menu “Criar um recurso”:

- Após o login, no painel do Azure, clique em “Criar um recurso” localizado no menu lateral esquerdo. Esse menu é o ponto de partida para adicionar novos serviços ao seu ambiente do Azure.

### 3. Navegue pelas Categorias:

- Na página “Criar um recurso”, você verá uma barra lateral com várias categorias como:
  - Computação
  - Redes
  - Armazenamento
  - Banco de Dados
  - Web
  - IA + Machine Learning
  - Segurança
  - DevOps
  - Migração

![categorias](https://github.com/devcaiada/az-900-certification/blob/main/assets/categorias.png?raw=true)

- Clique em qualquer uma dessas categorias para visualizar os serviços disponíveis dentro de cada uma1.

### 4. Use a Barra de Pesquisa:

- Se você já tem uma ideia do serviço que deseja, use a barra de pesquisa no topo da página “Criar um recurso” para localizar diretamente um serviço. Basta digitar o nome ou palavra-chave relacionada.

### 5. Filtrando Serviços por Categoria:

- Na mesma página, ao clicar em uma categoria, você pode aplicar filtros adicionais, como tipo de serviço, preço e tipo de oferta. Isso ajuda a refinar sua pesquisa e encontrar exatamente o que você precisa.

### 6. Explorar o Marketplace:

- O Azure Marketplace é outra ótima ferramenta para explorar serviços de terceiros e soluções de software, todos organizados por categoria. Acesse-o também pela opção “Marketplace” no menu principal do portal.

### 7. Criar e Configurar o Serviço:

- Ao encontrar o serviço desejado, clique nele para começar o processo de configuração. Siga as instruções na tela para configurar e provisionar o serviço no seu ambiente Azure.

<br></br>

# Criando Máquinas Virtuais na Azure

![virtual-machine](https://github.com/devcaiada/az-900-certification/blob/main/assets/virtual-machine.jpg?raw=true)

### 1. Acesse o Portal do Azure:

- Vá para o [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/) e faça login com suas credenciais da conta Microsoft.

### 2. Inicie o Processo de Criação:

- No painel do Azure, clique em “Criar um recurso” no menu lateral esquerdo.
- Na barra de pesquisa, digite “Máquina Virtual” e selecione “Máquinas Virtuais” nos resultados.

### 3. Configuração da Máquina Virtual:

- Clique em “Criar” e depois em “Máquina virtual do Azure”.
- Preencha os detalhes da instância:
  - **Nome**: Escolha um nome para sua VM.
  - **Região**: Selecione a região onde a VM será hospedada.
  - **Imagem**: Escolha o sistema operacional (por exemplo, Windows Server 2022).
  - **Tamanho**: Selecione o tamanho da VM com base nas suas necessidades de CPU e memória.

### 4. Configuração da Conta de Administrador:

- Insira um nome de usuário e uma senha para a conta de administrador da VM.

### 5. Configuração de Rede:

- Em “Regras de porta de entrada”, selecione as portas que deseja abrir (por exemplo, RDP para Windows ou SSH para Linux).

### 6. Revisar e Criar:

- Clique em “Revisar + criar” na parte inferior da página.
- Após a validação, clique em “Criar” para iniciar a implantação da VM.

### 7. Conectar à Máquina Virtual:

- Após a implantação, vá para o recurso da VM.
- Clique em “Conectar” e selecione “RDP” (para Windows) ou “SSH” (para Linux).
- Baixe o arquivo RDP ou use o comando SSH fornecido para se conectar à VM.

Seguindo esses passos, você conseguirá criar e acessar uma máquina virtual no Azure.

<br></br>

# Configurando uma instância de Banco de Dados na Azure

O Microsoft Azure oferece diversas opções para a criação de bancos de dados na nuvem. Um dos serviços mais populares é o Azure SQL Database, um serviço de banco de dados relacional gerenciado. Abaixo está um passo a passo detalhado para criar uma instância de banco de dados no Azure.

### 1. Acesse o Portal do Azure
 - Vá até o [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/).
 - Faça login com sua conta Microsoft ou crie uma, se ainda não tiver.

### 2. Navegue até a Seção de Serviços de Banco de Dados
 - No painel esquerdo, clique em "**Criar um recurso**".
 - Em **Banco de Dados**, selecione a opção "**SQL Database**" ou outro serviço de banco de dados que você deseja, como **Azure Database for MySQL** ou **Azure Database for PostgreSQL**.

### 3. Configurar o Servidor SQL
 - Na tela de criação do banco de dados, preencha os campos necessários:
    - **Assinatura**: Escolha a assinatura do Azure (se você tiver mais de uma).
    - **Grupo de Recursos**: Selecione um grupo de recursos existente ou crie um novo. Os grupos de recursos ajudam a organizar e gerenciar todos os recursos relacionados ao banco de dados.
    - **Nome do Banco de Dados**: Escolha um nome único para o banco de dados.
    - **Servidor**: Você precisa criar ou selecionar um servidor SQL existente. Clique em "**Criar Novo**" para configurar um servidor:
      - **Nome do servidor**: Escolha um nome exclusivo.
      - **Localização**: Escolha a região mais próxima ou que faça sentido para seu projeto.
      - **Administração do Servidor**: Defina um nome de administrador e senha para a instância do servidor.

### 4. Configurar a Camada de Preço
 - O Azure SQL Database oferece diferentes **camadas de desempenho**:
    - **Uso Básico**: Para cargas de trabalho leves, como desenvolvimento e teste.
    - **Uso Geral (Standard)**: Para cargas de trabalho de produção de uso moderado.
    - **Uso Crítico (Premium)**: Para aplicações que exigem alta disponibilidade e desempenho constante.
 - Escolha a camada que melhor se adequa ao seu projeto e defina a quantidade de recursos (como vCores e armazenamento).

### 5. Configurações Adicionais (Opcional)
 - Você pode ajustar configurações avançadas, como habilitar ou não a replicação geográfica, configurar backups automáticos e definir políticas de segurança.
 - Selecione a **autenticação** que deseja utilizar: **SQL Authentication** ou **Azure Active Directory**.

### 6. Criar o Banco de Dados
 - Após definir todas as configurações, clique em **Revisar + Criar**.
 - O Azure irá validar as configurações. Se estiver tudo certo, clique em **Criar**.

### 7. Acessar o Banco de Dados
 - Uma vez que a instância estiver provisionada (o que pode levar alguns minutos), você pode acessar o banco de dados diretamente no portal.
 - Para conectar seu banco de dados, você pode usar ferramentas como **Azure Data Studio**, **SQL Server Management Studio (SSMS)** ou até mesmo programaticamente via uma aplicação.

### 8. Configurar Regras de Firewall
 - Para permitir conexões ao banco de dados de fora da rede do Azure, você precisa configurar as **Regras de Firewall**:
    - No portal do Azure, navegue até a instância do banco de dados.
    - No menu à esquerda, selecione **Configurações do Firewall** e **Rede Virtual**.
    - Adicione o endereço IP de sua máquina local (ou de onde você deseja permitir acesso) e salve as alterações.

### 9. Testar a Conexão
 - Use uma ferramenta como **SSMS ou Azure Data Studio** para testar a conexão. Insira o nome do servidor, o nome de usuário e a senha que você configurou na criação do servidor SQL.
 - Certifique-se de que o firewall do banco de dados esteja configurado corretamente para permitir acesso ao endereço IP da sua máquina.

### 10. Gerenciar e Monitorar
 - Uma vez que o banco de dados está rodando, você pode monitorar seu desempenho diretamente pelo **Azure Monitor**, ajustar parâmetros de escalabilidade, configurar backups e gerenciar usuários.
