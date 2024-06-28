<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Gestor de Atendimentos</h1>
    <p>Um sistema de gestão de atendimentos desenvolvido com HTML, Bootstrap e Local Storage. Este projeto foi criado para gerenciar e registrar atendimentos de forma organizada e controlada.</p>
    <h2>Funcionalidades</h2>
    <ul>
        <li>Autenticação de usuários (simulada)</li>
        <li>Registro de atendimentos com diversos campos</li>
        <li>Cadastro de tipos de atendimentos</li>
        <li>Visualização dos atendimentos registrados</li>
        <li>Funcionalidades de CRUD (Create, Read, Update, Delete) utilizando Local Storage</li>
    </ul>
    <h2>Tecnologias Utilizadas</h2>
    <ul>
        <li>HTML</li>
        <li>Bootstrap</li>
        <li>JavaScript</li>
        <li>Local Storage</li>
    </ul>
    <h2>Estrutura do Projeto</h2>
    <p>O projeto contém as seguintes telas:</p>
    <ol>
        <li><strong>Login:</strong> Tela de login para autenticação do usuário.</li>
        <li><strong>Registro de Atendimento:</strong> Formulário para registrar novos atendimentos.</li>
        <li><strong>Cadastro de Atendimento:</strong> Formulário para cadastrar tipos de atendimentos.</li>
        <li><strong>Visualizar Atendimentos:</strong> Tabela para visualizar e gerenciar os atendimentos registrados.</li>
    </ol>
    <h2>Como Usar</h2>
    <h3>Pré-requisitos</h3>
    <p>Nenhum pré-requisito especial é necessário, basta um navegador moderno.</p>
    <h3>Instalação</h3>
    <ol>
        <li>Clone o repositório:
            <pre><code>git clone https://github.com/seu-usuario/a3_gestao_form.git</code></pre>
        </li>
        <li>Navegue até o diretório do projeto:
            <pre><code>cd gestor-de-atendimentos</code></pre>
        </li>
        <li>Abra o arquivo <code>index.html</code> no seu navegador.</li>
    </ol>
    <h3>Funcionalidades de CRUD</h3>
    <p>O projeto utiliza Local Storage para armazenar os dados dos atendimentos. As operações de CRUD podem ser realizadas através das seguintes funcionalidades:</p>
    <ul>
        <li><strong>Create:</strong> Preencha os formulários de registro ou cadastro de atendimento e clique em "Registrar Atendimento" ou "Cadastrar Atendimento".</li>
        <li><strong>Read:</strong> Navegue até a seção "Visualizar Atendimentos" para ver a tabela com os atendimentos registrados.</li>
        <li><strong>Update:</strong> (Funcionalidade a ser implementada)</li>
        <li><strong>Delete:</strong> Clique no botão "Delete" na tabela de visualização de atendimentos para remover um atendimento registrado.</li>
    </ul>
    <h3>Estrutura de Código</h3>
    <p><code>index.html</code>: Arquivo principal contendo toda a estrutura HTML e os scripts JavaScript.</p>
    <h3>Scripts JavaScript</h3>
    <p>Os scripts JavaScript são responsáveis por:</p>
    <ul>
        <li>Salvar dados no Local Storage.</li>
        <li>Recuperar dados do Local Storage.</li>
        <li>Renderizar a tabela de visualização de atendimentos.</li>
        <li>Gerenciar os eventos de submit dos formulários.</li>
    </ul>
    <h3>Contribuições</h3>
    <p>Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.</p>
    <h3>Licença</h3>
    <p>Este projeto está licenciado sob a <a href="LICENSE">MIT License</a>.</p>
</body>
</html>
