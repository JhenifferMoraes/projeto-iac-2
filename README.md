<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=f5b100&height=180&section=header"/>

 # <img width=3% src="tux.png"/> Projeto Script Bash: Provisionamento de um Servidor Web (Apache)
Este projeto, desenvolvido como parte das atividades do bootcamp Linux, teve como objetivo principal a criação de um script de Infraestrutura como Código (IaC).
Ele automatiza o processo de atualização do servidor, 
instalação do servidor web Apache2 e o deploy de uma aplicação web estática baixada diretamente de um repositório GitHub.

### ⚠️ Principais assuntos trabalhados:

- Atualização e Upgrade de Pacotes do Sistema
  
- Instalação de Serviços `Apache2` e Utilitários `Unzip`

- Download de arquivos via linha de comando `wget`

- Manipulação e Descompactação de Arquivos `unzip`

- Implantação de aplicação no diretório padrão do Apache

### ⛏️Como realizar a execução:

- O script deve ser executado com permissões de superusuário (sudo) ou diretamente como root.

- Atenção: Este script substitui o conteúdo do diretório /var/www/html/. Execute-o preferencialmente em um ambiente limpo ou virtualizado.

- O fluxo de execução do script é:
 1. Atualização: Executa `apt-get update` e `apt-get upgrade` para garantir que o sistema esteja seguro e atualizado.
 2. Instalação: Instala o servidor web `apache2` e a ferramenta `unzip`.
 3. Download: Baixa o código fonte da aplicação do repositório remoto.
 4. Deploy: Descompacta o arquivo e copia todos os arquivos da aplicação para a pasta raiz do servidor web.

### 📋O que foi necessário para realizar este projeto:

Este projeto exigiu o uso de um terminal Linux funcional (baseado em Debian ou Ubuntu), operando preferencialmente em uma Máquina Virtual (VM) para simular um servidor real. 
Foram explorados comandos essenciais de gerenciamento de pacotes e manipulação de arquivos.

O script foi salvo com a extensão `.sh`, tornado executável com o comando `chmod +x nome_do_script.sh` e executado para provisionar o servidor automaticamente.

Abaixo, deixarei alguns links para downloads das ferramentas e do repositório utilizado.

```
 VirtualBox Oracle - https://www.virtualbox.org/
```
```
 Ubuntu - https://ubuntu.com/download/desktop
```

```
 Repositório da Aplicação - https://github.com/denilsonbonatti/linux-site-dio
```

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=f5b100&height=100&section=footer"/>
