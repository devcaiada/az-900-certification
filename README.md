# Microsoft Azure Essentials

![capa](https://github.com/devcaiada/az-900-certification/blob/main/assets/azure-capa.png?raw=true)

# Localizando Serviços por Categoria

### 1. Acesse o Portal do Azure:

- Navegue até portal.azure.com e faça login com suas credenciais da conta Microsoft.

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

![virtual-machine]()

### 1. Acesse o Portal do Azure:

- Vá para portal.azure.com e faça login com suas credenciais da conta Microsoft.

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
