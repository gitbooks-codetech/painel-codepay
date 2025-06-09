---
icon: dungeon
---

# Clientes Gateway

## Novo Cliente

Aqui que você cadastra um novo cliente no CodePay.

No menu lateral no item **Administração**, clique em <mark style="color:green;">**Clientes Gateway**</mark>, a lista de clientes cadastrados é exibida.

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Para cadastrar novo cliente é necessário ter permissão nessa funcionalidade.
{% endhint %}

Clique no botão Cadastrar e preencha o formulário. Os campos nome, email e documento são obrigatórios o preenchimento.

Os campos de Taxa Pix IN e Taxa Pix OUT são obrigatórios mas possuem um padrão ao criar a conta de valor igual a zero.

Informe o seu código de 2fa (segundo fator de segurança) para clicar em <mark style="color:green;">**Cadastrar**</mark> e finalizar o cadastro.

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Após criar um novo cliente ele recebe no email cadastrado 2 emails, um com as credenciais da conta para integração e outro para o primeiro acesso ao banco CodePay.
{% endhint %}

## Editar Cliente

Para alterar informações do cliente, nalista de clientes cadastrados clique no ícone de edição.

Os campos nome, email e documento não podem ser alterados pelo Painel CodePay, é necessário solicitar alteração.

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Para editar todas as informações do cliete, exceto os campos nome, email e documento, é necessário ter permissão nessa funcionalidade.
{% endhint %}

Ao clicar em editar um formulário é exibido com os campos permitidos para a alteração. Para finalizar a edição é necessário informar o código 2fa (segundo fator de segurança).

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

O status do cliente pode ser alterado para inativo, dessa forma o cliente não consegue mais utilizar o CodePay e nem realizar movimentos direto pelo API Gateway da CodePay.

A URL de notificação é o endereço do WEBHOOK que enviaremos as notificações de confirmação para o cliente.&#x20;

O campo frase de segurança é enviado via WEBHOOK para o cliente fazer uma validação caso necessário.

{% hint style="info" %}
Esse campo, **URL de notificação e Frase de segurança**, o cliente consegue editar diretamente pelo CodePay\
[https://code-tech.gitbook.io/code-pay/configuracoes/informacoes#dados-do-webhook](https://code-tech.gitbook.io/code-pay/configuracoes/informacoes#dados-do-webhook)
{% endhint %}

Para clientes que forem utilizar saque (PIX OUT) via API é necessário habilitar o campo Permitir saque via API. O padrão sempre é desabilitado/Não.
