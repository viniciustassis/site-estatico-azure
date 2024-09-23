# Criação de um site estático na Azure 🚀

## Passo a Passo:

1. **Criar uma Conta de Armazenamento (Blob Storage)**
   - Acesse o portal da Azure e crie um recurso do tipo **Conta de Armazenamento**.

2. **Habilitar o site estático**
   - No painel da Conta de Armazenamento, vá até: **Visão Geral (Overview)** > **Capacidades (Capabilities)** > **Site estático (Static website)**.
   - Habilite a opção **Site estático** selecionando **Habilitado (Enabled)**.

3. **Configurar o site**
   - A Azure irá fornecer o **Ponto de extremidade principal (Primary Endpoint)**, que é a URL onde o site será acessado.
   - Informe o nome do seu arquivo principal como **index.html**.
   - Defina a página de erro 404 informando o arquivo **404.html**.

4. **Fazer upload dos arquivos do site**
   - Acesse **Armazenamento de dados (Data storage)** > **Contêineres (Containers)** > Crie um contêiner com o nome **web**.
   - Dentro desse contêiner, faça o upload dos seus arquivos HTML, CSS e JavaScript.

5. **Acessar seu site**
   - Use o **Ponto de extremidade principal (Primary Endpoint)** fornecido para acessar o site que você acabou de criar!

## Dica Final:

Lembre-se de **excluir os recursos** na Azure após concluir seu teste ou deploy, para evitar custos indesejados.

## Recursos que devem ser deletados:

1. **Conta de Armazenamento (Blob Storage)**: Acesse o portal da Azure e localize a conta de armazenamento que você criou. Para excluí-la:
   - No menu lateral, clique em **Visão Geral (Overview)**.
   - No topo da página, clique no botão **Excluir (Delete)**.
   - Confirme a exclusão digitando o nome da conta de armazenamento e clicando em **Excluir (Delete)**.

2. **Contêineres**: Ao excluir a conta de armazenamento, todos os contêineres (como o contêiner "web") e os arquivos dentro deles serão excluídos automaticamente.

Ao excluir esses recursos, você garante que não serão cobradas taxas adicionais na sua conta Azure.
