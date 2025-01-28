# Gestor de Clientes

## Sobre o Projeto
O **Gestor de Clientes** é um sistema simples de gerenciamento de clientes desenvolvido em C#. O sistema permite realizar as seguintes operações:

- Listar clientes
- Adicionar novos clientes
- Remover clientes
- Armazenar os dados localmente em arquivo binário

## Funcionalidades

### 1. **Listagem de Clientes**
Permite visualizar todos os clientes cadastrados com seus respectivos IDs, nomes, e-mails e CPFs.

### 2. **Adicionar Cliente**
Permite cadastrar um novo cliente informando:
- Nome
- E-mail
- CPF

### 3. **Remover Cliente**
Permite remover um cliente através de seu ID exibido na listagem.

### 4. **Persistência de Dados**
Os dados são armazenados em um arquivo binário (`clients.dat`) para garantir que os registros permaneçam após o encerramento do programa.

## Tecnologias Utilizadas
- Linguagem: C#
- Plataforma: .NET
- Estrutura de Dados: List
- Serialização: BinaryFormatter

## Exemplo de Uso
```
Sistema de clientes - Bem Vindo!
================================
1-Listagem
2-Adicionar
3-Remover
4-Sair
Escolha uma opção: 1

Lista de clientes:
ID: 0
Nome: João Silva
Email: joao@email.com
CPF: 123.456.789-00
=======================
Aperte enter para sair.
```

## Melhorias Futuras
- Validação de dados de entrada (nome, CPF, e-mail)
- Implementação de interface gráfica
- Persistência em banco de dados
- Opção de editar dados do cliente

## Observação
O projeto utiliza `BinaryFormatter`, que está obsoleto e pode apresentar riscos de segurança. Para projetos futuros, recomenda-se utilizar formatos de serialização modernos, como JSON.

---
