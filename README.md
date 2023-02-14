# Utilizado_ASP.NET-MVC-EF_CORE
Pequeno projeto utilizando ASP .NET / MVC / EF CORE

Com esse projeto pude entender e aprender ios conceitos e como utilizar o MVC.

Entendemos que na web, o cliente utiliza um navegador, constituindo o que levamos de *cliente side* (lado do cliente) para se conectar a um servidor no *server side* (lado do servidor) por meio de um endereço ou URL (Uniform Resource Locator) que, em português, é conhecido como localizador padrão de recursos. O uso da URL foi a forma textual encontrada para facilitar o direcionamento a um endereço *Internet Protocol* (IP), sendo que essa tradução é feita por meio de servidores de serviços de DNS (Domain Name Server), ou Sistema de Nomes e Domínios.

O **cliente side** agrega os elementos que o usuário visualiza em uma pagina, como imagens, texto, botões, campo de formulário e as ações executadas na interação desse com o navegador.

O **server side**, por sua vez, inclui tudo que acontece no servidor, o que, de modo geral, inclui receber requisições dos clientes, efetuar seu processamento com interações com base de dados e enviar requisições de repostas aos clientes.

- **FUNCIONAMENTO BÁSICO DO PROTOCOLO HTTP**

O Hyper Texto Transfer Protocol (HTTP) é o protocolo oficial de comunicação de dados na web, que permite a troca de dados padronizado, em novel de aplicação, entre um navegador cliente e servidor.

O cliente envia uma solicitação HTTP para um  servidor, chamada de requisição, e então o servidor responde a essa solicitação por meio de um ou mais mensagens de resposta.

- **HTTPS**

O Hyper Texto Transfer Protocol Secure (HTTPS) se diferencia do HTTP principalmente por realizar a encriptação dos dados trafegados, requerendo para isso a autenticação dos servidores e o recebimento de uma certificação de uma autoridade certificadora (AC). Para tanto, ele utiliza a tecnologia Transport Layer Security (TLS), para realizar o processo de comunicação segura.

Para utilizar o HTTPS o usuário deve digitar “`https://`” antes do endereço do site, e geralmente, é utilizado a porta 443 com certificação validade nesse tipo de comunicação. com a validação da comunicação segura os navegadores são informados desse status normalmente por meio de um ícone de cadeado ao lado do URL, na barra do navegador.

ASP.NET é a plataforma da Microsoft para o desenvolvimento de aplicações Web e é o sucessor da tecnologia ASP. Permite, através de uma linguagem de programação integrada na .NET Framework, criar páginas dinâmicas.

O Postman é uma ferramenta que tem como objetivo TESTAR serviços RESTful (Web APIs) por meio do envio de requisições HTTP e da análise do seu retorno.

O protocolo HTTP define um conjunto de **métodos de requisição** responsáveis por indicar a ação a ser executada para um dado recurso. Embora esses métodos possam ser descritos como substantivos, eles também são comumente referenciados como ***HTTP Verbs (Verbos HTTP)***.

- `[GET](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/GET)`

O método `GET` solicita a representação de um recurso específico. Requisições utilizando o método `GET` devem retornar apenas dados.

- `[HEAD](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/HEAD)`

O método `HEAD` solicita uma resposta de forma idêntica ao método `GET`, porém sem conter o corpo da resposta.

- `[POST](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/POST)`

O método `POST` é utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.

- `[PUT](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/PUT)`

O método `PUT` substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.

- `[DELETE](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/DELETE)`

O método `DELETE` remove um recurso específico.

- `[CONNECT](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/CONNECT)`

O método `CONNECT` estabelece um túnel para o servidor identificado pelo recurso de destino.

- `[OPTIONS](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/OPTIONS)`

O método `OPTIONS` é usado para descrever as opções de comunicação com o recurso de destino.

- `[TRACE](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/TRACE)`

O método `TRACE` executa um teste de chamada *loop-back* junto com o caminho para o recurso de destino.

- `[PATCH](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/PATCH)`

O método `PATCH` é utilizado para aplicar modificações parciais em um recurso.

Entendendo o padrão MVC

O **MVC** (Models, Views e Controllers) é uma arquitetura ou padrão que lhe permite dividir as funcionalidades do seu sistema/site em camadas, essa divisão é realizada para resoluções de um problema maior.

Desta forma, qualquer tipo de alteração em uma das camadas não interfere nas demais, facilitando a atualização de layouts, alterações nas regras de negócios e edição de novos recursos. Em caso de grande projeto, o MVC facilita muito na divisão de tarefas entre equipes.

- vantagens do MVC em seus projetos:
    1. Facilita a reaproveitamento de códigos;
    2. Facilita a manutenção e edição de recursos;
    3. Maior integração da equipe e/ou divisão de tarefas;
    4. Diversas tecnologias estão adotando essa arquitetura;
    5. Facilita em manter o seu código sempre limpo.
    
***MODEL***: Representa as dados modelados, gravando o conteúdo de objetos e incluindo suas restrições lógicas (de negócios ou não). Faz a materialização das classes que trabalham para armazenamento e busca dos dados.

**VIEW (visão ou apresentação)**: Realiza a apresentação visual dos dados contidos no MODEL, mostrando o conteúdo armazenado ao usuário. 

**CONTROLLER**: Interpreta as ações de entrada em um sistema, realizando processamentos e faz busca e inserções de dados no modelo (JavaScript, CSS, HTML e etc).
