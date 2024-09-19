<p align="center">
<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/76541047/365524077-d98e20f2-997a-4079-9e2b-356f29cc9ff1.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240909%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240909T053843Z&X-Amz-Expires=300&X-Amz-Signature=412cfcfa3f61cfd1374f702dbc2ec83a65cf9bae9e09554366ba0325bd9174bb&X-Amz-SignedHeaders=host&actor_id=76541047&key_id=0&repo_id=803458455" width="100" />
</p>

<h1 align="center">
  hiring-front-end-angular
</h1>

<p align="center">
 <a href="#figma">Figma</a> •
 <a href="#layout">Layout</a> • 
 <a href="#config">Configuração do Projeto</a> • 
 <a href="#deploy">Deploy</a> 
</p>

<p> 
  <strong> Este projeto consiste em uma tabela dinâmica que carrega dados de um arquivo JSON. A tabela permite:</strong> editar registros existentes, adicionar novos registros, Excluir registros, filtrar registros por `department` e `role`, ordenar registros por qualquer campo, paginar registros, com no máximo 5 registros por página, exportar registros visíveis em CSV, buscar registros por `name`, `email` ou `phone` e Validação de formulários.
  As alterações feitas na tabela são refletidas diretamente no JSON local, garantindo que os dados estejam sempre atualizados.
</p>
  
<h2 id="figma">🎨Design</h2> 

O design da aplicação está disponível no Figma. Você pode visualizar e obter os detalhes do design através do seguinte link:

[Figma Design - Hiring Front-end Angular](https://www.figma.com/design/JCwvqIXLh0Kc8TtHW86zCW/hiring-front-end-angular?node-id=1-475&node-type=FRAME&t=V3Xz037K3yza65wf-0)

<h2 id="layout">🖼️Imagens do Layout</h2>

Abaixo estão algumas imagens representativas do layout da aplicação, conforme o design definido no Figma. 

<p align="center">
  
  <img src="https://github.com/user-attachments/assets/a5bc86a7-9d8f-4efd-bfce-62daf261fc6a" width="370"/>
  <img src="https://github.com/user-attachments/assets/00264cdc-f7d1-41bf-a889-be72dfb972d9" width="370"/>
  <img src="https://github.com/user-attachments/assets/cea03407-2ffb-4d62-9a1c-d1ea6ae44b57" width="370"/>
  <img src="https://github.com/user-attachments/assets/020576f3-4e36-45f8-a1ea-1be94da08b7a" width="370"/>

</p>

<h2 id="config">🛠️Configuração do Projeto </h2>

### 1. Instalar o Projeto na Máquina

- Versão de Node.js: O projeto foi desenvolvido com Node.js versão 20.10.0. É recomendável instalar essa versão para garantir compatibilidade.

- Gerenciador de Pacotes: Utilize o npm (Node Package Manager) para gerenciar as dependências do projeto.

- Para instalar o Node.js e o npm, você pode baixar o instalador apropriado para o seu sistema operacional no site oficial do Node.js.

- Versão do Angular:
Este projeto utiliza Angular versão 15. Certifique-se de ter o Angular CLI instalado com a versão compatível:

```bash
    npm install -g @angular/cli@15
```
Agora é só clone o projeto na sua máquina, usando o comando:

```bash
    git clone https://github.com/jussaraalves/hiring-front-end-angular.git
```

### 2. Entre no diretório do projeto
Depois de clonar o repositório, navegue até o diretório do projeto e execute o seguinte comando para instalar as dependências necessárias:

```bash
   npm install
```

### 3. Rodar o Ambiente de Desenvolvimento
Para iniciar o servidor de desenvolvimento e ver a aplicação em funcionamento, utilize:

```bash
  npm start
```
O projeto será iniciado e estará acessível em http://localhost:4200 por padrão.

### 4. Rodar a Build de Deploy da Aplicação
Para criar uma build de produção do projeto, execute o comando:

```bash
  npm run build
```
<h2 id="deploy">🌐Hospedagem</h2>

O projeto está hospedado no seguinte link:

[Link da Hospedagem](https://example.com) 
