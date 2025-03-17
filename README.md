# site-projetos-de-tecnologia

Site desenvolvido para armazenar informações de projetos de tecnologia do CEET Vasco Coutinho

## Tecnologias Utilizadas

- **PHP** (Backend)
- **HTML5** (Estrutura)
- **CSS3** (Estilização)
- **JavaScript** (Interatividade)
- **Bootstrap** (Framework CSS, opcional)

## Requisitos

Certifique-se de ter os seguintes requisitos instalados no seu sistema:

- **PHP** (versão 7.4 ou superior)
- **Apache** (via XAMPP, WAMP ou outro servidor local)
- **Git** (para clonar o repositório)

## Como Executar o Projeto

### 1. Clonar o repositório

```bash
 git clone git@github.com:projeto-ceet/site-projetos-de-tecnologia.git
```

### 2. Acesse o diretório do projeto

```bash
 cd site-projetos-de-tecnologia
```

### 3. Mova os arquivos para o diretório do servidor local

Se estiver usando XAMPP:

```bash
 mv site-projetos-de-tecnologia/ /c/xampp/htdocs/
```

Se estiver usando WAMP:

```bash
 mv site-projetos-de-tecnologia/ /c/wamp/www/
```

### 4. Iniciar o servidor local

Para rodar o projeto, inicie o servidor Apache e MySQL no XAMPP/WAMP ou rode o PHP embutido:

```bash
 php -S localhost
```

Acesse no navegador:

```
 http://localhost/site-projetos-de-tecnologia/
```

Ou, se usou o servidor embutido:

```
 http://localhost/
```

## Estrutura do Projeto

```
/site-projetos-de-tecnologia
│── /assets          # Arquivos estáticos (CSS, JS, imagens)
│── /includes        # Arquivos PHP reutilizáveis (header, footer)
│── /pages           # Páginas do site
│── index.php        # Página inicial
│── README.md        # Documentação
```

## Contribuição

Se quiser contribuir com o projeto, siga estes passos:

1. Clone o repositório do projeto: `git clone git@github.com:projeto-ceet/site-projetos-de-tecnologia.git`
2. Vá para a branch develop: `git checkout develop`
3. Crie uma branch para sua funcionalidade: `git checkout -b nome-minha-branch`
4. Faça as alterações e commit: `git commit -m "Descrição da alteração"`
5. Envie para o repositório remoto: `git push origin nome-minha-branch`
6. Abra um Pull Request

---

📧 **Contato:** projeto.ceet.vasco@gmail.com
