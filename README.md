# Azure Ubuntu MySQL Lab

## Objetivo
Criar uma máquina virtual Ubuntu Server no Microsoft Azure e configurar um servidor MySQL para testes de administração de banco de dados.

## Tecnologias Utilizadas
- Microsoft Azure
- Ubuntu Server 24.04 LTS
- MySQL Server
- SSH
- Network Security Group (NSG)

## Atividades Realizadas

### Infraestrutura
- Criação de Resource Group
- Criação de Máquina Virtual Linux
- Configuração de IP Público
- Configuração de regras de firewall

### Sistema Operacional
- Atualização do Ubuntu
- Gerenciamento via SSH
- Administração de usuários

### Banco de Dados
- Instalação do MySQL
- Configuração de senha do root
- Testes de acesso ao banco
- Gerenciamento de permissões

## Comandos Utilizados

bash
sudo apt update
sudo apt upgrade -y
sudo apt install mysql-server -y
sudo systemctl status mysql


## Resultados
Servidor Ubuntu implantado com sucesso no Azure e MySQL configurado para administração e testes.
