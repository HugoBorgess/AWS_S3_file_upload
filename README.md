# Upload de arquivo para o Amazon S3

Este é um script Python que permite fazer o upload de um arquivo local para o serviço de armazenamento em nuvem Amazon S3. O Amazon S3 é um serviço de armazenamento altamente escalável e durável, oferecido pela Amazon Web Services (AWS).

## Requisitos

- Certifique-se de ter as credenciais de acesso da AWS (Access Key e Secret Key) disponíveis. Caso não as possua, obtenha-as no painel de controle da AWS.

## Utilização

1. Substitua as variáveis `ACCESS_KEY`, `SECRET_KEY`, `LOCAL_FILE`, `BUCKET_NAME` e `S3_FILE_NAME` no código pelo valor correto de acordo com o seu ambiente e requisitos.
2. Execute o script em um ambiente Python com as dependências corretas instaladas.
3. O script irá utilizar as credenciais fornecidas para estabelecer uma conexão com o Amazon S3.
4. O arquivo local especificado em `LOCAL_FILE` será carregado para o bucket do S3 especificado em `BUCKET_NAME`, com o nome definido em `S3_FILE_NAME`.
5. Após o upload ser concluído com sucesso, a mensagem "Upload Successful" será exibida.
6. Se ocorrer algum erro durante o processo de upload, mensagens específicas serão exibidas para ajudar a identificar o problema.

## Observação

- Certifique-se de ter permissões adequadas no Amazon S3 para realizar o upload do arquivo.
- Verifique se o arquivo local especificado em `LOCAL_FILE` existe e está acessível pelo script.
- Certifique-se de que o bucket do S3 especificado em `BUCKET_NAME` exista e esteja correto.
- O arquivo será carregado no S3 com o nome especificado em `S3_FILE_NAME`.
- Este script é um exemplo básico de como fazer o upload de um arquivo para o Amazon S3. Você pode adaptá-lo conforme necessário, por exemplo, para fazer upload de vários arquivos ou implementar recursos adicionais.

