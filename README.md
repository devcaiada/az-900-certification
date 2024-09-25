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

![database](https://github.com/devcaiada/az-900-certification/blob/main/assets/sqlazure_img08-1.jpg?raw=true)

### 1. Acesse o Portal do Azure

- Vá até o [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/).
- Faça login com sua conta Microsoft ou crie uma, se ainda não tiver.

### 2. Navegue até a Seção de Serviços de Banco de Dados

- No painel esquerdo, clique em "**Criar um recurso**".
- Em **Banco de Dados**, selecione a opção "**SQL Database**" ou outro serviço de banco de dados que você deseja, como **Azure Database for MySQL** ou **Azure Database for PostgreSQL**.

![sql](https://github.com/devcaiada/az-900-certification/blob/main/assets/select-deployment.png?raw=true)

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

<br></br>

# Construindo Arquiteturas no Azure

### 1. Acesse o Portal do Azure:

- Entre no [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/).

### 2. Navegue até Grupos de Recursos:

- No menu à esquerda, selecione **Grupos de Recursos**.

![resource_g](https://github.com/devcaiada/az-900-certification/blob/main/assets/resource%20group%201.png?raw=true)

### 3. Criar um Novo Grupo de Recursos:

- Clique em Criar.
- Preencha os seguintes campos:
  - **Assinatura**: Selecione sua assinatura do Azure.
  - **Grupo** de Recursos: Insira um nome para o novo grupo de recursos.
  - **Região**: Escolha uma localização do Azure, como “EUA Central”.
- Clique em **Examinar + Criar** e depois em **Criar**.

### 4. Verificar a Criação:

- Após alguns segundos, o grupo de recursos será criado. Você pode atualizá-lo na lista de grupos de recursos ou clicar na notificação para abrir o grupo recém-criado.

## Gerenciar Permissões

![permission](https://github.com/devcaiada/az-900-certification/blob/main/assets/resource%20group.png?raw=true)

### 1. Acessar Controle de Acesso (IAM):

- Dentro do grupo de recursos, selecione **Controle de Acesso (IAM)** no menu à esquerda.

### 2. Adicionar uma Função:

- Clique em **Adicionar** e depois em **Adicionar atribuição de função**.
- Escolha a função desejada (por exemplo, **Contribuidor**).
- Selecione o usuário ou grupo que receberá essa função.
- Clique em **Salvar** para aplicar as permissões.

## Aplicar Bloqueios

### 1. Acessar Configurações de Bloqueio:

- No menu do grupo de recursos, selecione **Bloqueios**.

### 2. Adicionar um Bloqueio:

- Clique em **Adicionar**.
- Preencha os seguintes campos:
  - **Nome**: Insira um nome para o bloqueio.
  - **Tipo de Bloqueio**: Escolha entre **Excluir** (impede a exclusão) ou **Somente leitura** (impede alterações).
  - **Notas**: Adicione qualquer informação adicional, se necessário.
- Clique em **OK** para aplicar o bloqueio.

<br></br>

# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

## Passo 1: Criar uma Máquina Virtual

### 1. **Acesse o Portal do Azure**: Entre no [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/).

### 2. **Criar um Recurso**: Clique em “Criar um recurso” e selecione “Máquina Virtual”.

### 3. **Configurações Básicas**:

- **Assinatura**: Selecione sua assinatura do Azure.
- **Grupo de Recursos**: Escolha um grupo de recursos existente ou crie um novo.
- **Nome da Máquina Virtual**: Dê um nome à sua VM.
- **Região**: Escolha a região onde a VM será hospedada.
- **Imagem**: Selecione o sistema operacional desejado (Windows ou Linux).
- **Tamanho**: Escolha o tamanho da VM com base nas suas necessidades de CPU e memória.

![vms](https://github.com/devcaiada/az-900-certification/blob/main/assets/VMs.jpg?raw=true)

## Passo 2: Configurar Recursos

### 1. Discos:

- **Disco do Sistema Operacional**: Escolha o tipo de disco (SSD ou HDD).
- **Discos de Dados**: Adicione discos adicionais conforme necessário.

### 2. Rede:

- **Rede Virtual**: Selecione uma rede virtual existente ou crie uma nova.
- **Sub-rede**: Escolha uma sub-rede.
- **Endereço IP Público**: Configure um endereço IP público se necessário.
- **Grupo de Segurança de Rede**: Configure regras de firewall para controlar o tráfego de entrada e saída.

## Passo 3: Dimensionamento

### 1. Dimensionamento Vertical:

- **Aumentar/Reduzir Tamanho**: Você pode redimensionar a VM para um tamanho maior ou menor conforme necessário. Isso pode ser feito na seção “Tamanho” da VM no portal do Azure.

### 2. Dimensionamento Horizontal:

- **Conjuntos de Dimensionamento de Máquinas Virtuais**: Use conjuntos de dimensionamento para criar e gerenciar um grupo de VMs idênticas. Isso permite que você escale automaticamente o número de VMs com base na demanda.

## Passo 4: Configurações Avançadas

### 1. Monitoramento:

- **Diagnóstico de Inicialização**: Ative o diagnóstico de inicialização para solucionar problemas de inicialização.
- Monitoramento de Desempenho: Use o Azure Monitor para acompanhar o desempenho da VM.

### 2. Automação:

- **Scripts de Inicialização**: Adicione scripts de inicialização para configurar a VM automaticamente ao iniciar.

## Passo 5: Revisar e Criar

#### 1. **Revisar**: Verifique todas as configurações.

#### 2. **Criar**: Clique em “Criar” para provisionar a VM.

<br></br>

# Armazenamento e Migração de Dados na Azure

Vamos criar um passo a passo para criar uma conta de armazenamento no Azure e falar sobre os serviços de transferência de dados, como o AzCopy.

## 1. Acesse o Portal do Azure:

- Vá para o [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/) e faça login com sua conta.

![menu_storage](https://github.com/devcaiada/az-900-certification/blob/main/assets/Menu-storage.jpg?raw=true)

## 2. Criar uma Nova Conta de Armazenamento:

- No menu à esquerda, selecione “Contas de armazenamento”.
- Clique em “Criar” para iniciar o processo de criação.

![create_button](https://github.com/devcaiada/az-900-certification/blob/main/assets/create-button.jpg?raw=true)

- Preencha os detalhes necessários:
  - Assinatura: Selecione sua assinatura do Azure.
  - Grupo de Recursos: Escolha um grupo de recursos existente ou crie um novo.
  - Nome da Conta de Armazenamento: Insira um nome único para sua conta.
  - Região: Selecione a região onde deseja criar a conta.
  - Desempenho: Escolha entre Standard ou Premium, dependendo de suas necessidades.
  - Replicação: Selecione a opção de replicação desejada (LRS, GRS, RA-GRS, etc.).

![basic](https://github.com/devcaiada/az-900-certification/blob/main/assets/basic.jpg?raw=true)

## 3. Configurações Adicionais:

- Configure as opções adicionais conforme necessário, como redes virtuais, tags, etc.
- Clique em “Revisar e criar” e depois em “Criar” para finalizar a criação da conta.

<br></br>

# Serviços de Transferência e Migração de Dados

## 1. AzCopy:

![azcopy](https://github.com/devcaiada/az-900-certification/blob/main/assets/azcopy.jpg?raw=true)

- AzCopy é uma ferramenta de linha de comando que permite copiar dados de e para contas de armazenamento do Azure de forma eficiente.
- Instalação: Baixe e instale o AzCopy a partir do site oficial.

### Uso Básico:

- Para copiar um arquivo local para um contêiner de blob:

```
azcopy copy 'C:\local\path\to\file.txt' 'https://<storage-account-name>.blob.core.windows.net/<container-name>/file.txt'
```

- Para copiar um blob para um arquivo local:

```
azcopy copy 'https://<storage-account-name>.blob.core.windows.net/<container-name>/file.txt' 'C:\local\path\to\file.txt'
```

## 2. Azure Data Factory:

- Azure Data Factory é um serviço de integração de dados baseado em nuvem que permite criar, agendar e orquestrar fluxos de trabalho de dados.
- Ele suporta a movimentação de dados entre uma variedade de fontes de dados, incluindo armazenamento do Azure, bancos de dados SQL, e muito mais.

## 3. Azure Storage Explorer:

- Azure Storage Explorer é uma ferramenta gráfica que facilita a gestão de dados no armazenamento do Azure.
- Permite visualizar, carregar, baixar e gerenciar blobs, arquivos, filas e tabelas.

<br></br>

# Identidade, Acesso e Segurança na Azure

## Acessar o Microsoft Entra ID

![entra-id](https://github.com/devcaiada/az-900-certification/blob/main/assets/Microsoft-Entra-ID-1.png?raw=true)

### 1. Entrar no Portal do Azure:

- Acesse o [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/).
- No menu lateral, selecione **Microsoft Entra ID**.

### 2. Gerenciar Funções e Administradores

1.  Visualizar Funções:

- No painel do **Microsoft Entra ID**, selecione **Funções e Administradores**.
- Aqui, você pode ver todas as funções disponíveis. Clique em uma função para ver os detalhes e os membros atribuídos.

2.  Adicionar Administradores:

- Para adicionar um novo administrador, selecione a função desejada e clique em **Adicionar membro**.
- Procure e selecione o usuário que deseja adicionar.

### 3. Configurar Redefinição de Senha Self-Service (SSPR)

1.  Ativar SSPR:

- No painel do Microsoft Entra ID, selecione **Redefinição de senha**.
- Ative a opção **Self-service password reset**.

![ssrp](https://github.com/devcaiada/az-900-certification/blob/main/assets/self%20service%20reset.png?raw=true)

2.  Configurar Métodos de Autenticação:

- Defina os métodos de autenticação que os usuários devem usar para redefinir suas senhas, como e-mail, telefone ou perguntas de segurança.
- Salve as configurações.

### 4. Criar Novo Usuário ou Convidar Usuário Externo

1.  Criar Novo Usuário:

- No painel do Microsoft Entra ID, selecione **Usuários**.
- Clique em **Novo usuário** e preencha as informações necessárias, como nome, nome de usuário e grupo de funções.
- Salve o novo usuário.

2.  Convidar Usuário Externo:

- No painel do Microsoft Entra ID, selecione **Usuários**.
- Clique em **Novo usuário** e selecione **Convidar usuário**.
- Insira o e-mail do usuário externo e configure as permissões e grupos aos quais ele terá acesso.
- Envie o convite.

### 5. Utilizar o Microsoft Defender for Cloud como Validador de Segurança

1.  Configurar o **Microsoft Defender for Cloud**:

- No Portal do Azure, navegue até **Microsoft Defender for Cloud**.
- Ative o Microsoft Defender for Cloud para suas assinaturas e recursos.

2.  Monitorar e Validar Segurança:

- O Microsoft Defender for Cloud fornece uma visão geral da postura de segurança da sua organização.
- Ele identifica vulnerabilidades e recomendações de segurança para proteger seus recursos.
- Utilize as recomendações para melhorar a segurança e conformidade dos seus recursos na Azure.

### EXTRA

- **Os usuários são excluídos permanentemente de forma automática 30 dias após serem deletados.**

<br></br>

# Otimizando Custos no Azure com a Calculadora TCO

### 1. Acesse a Calculadora TCO: Vá para a [Calculadora TCO do Azure](https://azure.microsoft.com/pt-br/pricing/tco/calculator/).
 - **Insira os Detalhes da Infraestrutura Atual**: Adicione informações sobre seus servidores, armazenamento, rede e outros componentes de TI que você está usando atualmente.
 - **Configurar o Ambiente do Azure**: Selecione os serviços do Azure que você planeja usar para substituir sua infraestrutura atual.
 - **Comparar Custos**: A calculadora irá comparar os custos atuais com os custos estimados no Azure, mostrando as possíveis economias.

## Dicas para Otimizar Custos no Azure

 - **Desligue Recursos Não Utilizados**: Identifique e desligue máquinas virtuais (VMs) e outros recursos que não estão sendo usados.
 - **Ajuste Recursos Subutilizados**: Redimensione ou consolide recursos subutilizados para reduzir gastos.
 - **Use Planos de Economia**: Considere usar planos de economia do Azure para cargas de trabalho dinâmicas, o que pode economizar até 65% em preços pré-pagos.
 - **Reserve Instâncias**: Para cargas de trabalho consistentes, reserve instâncias para obter descontos significativos.
 - **Monitore e Analise Custos**: Utilize o Microsoft Cost Management para monitorar e analisar sua fatura do Azure, definir orçamentos e alocar gastos para suas equipes e projetos.

 Inclusive existe até uma profissão especializada para a otimização de custos em nuvem, geralmente conhecida como **Cloud Cost Management Specialist** ou **Cloud Financial Analyst**.
