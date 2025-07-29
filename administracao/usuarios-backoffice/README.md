---
icon: user-police
---

# Usuários Backoffice

Nessa página vamos exibir a lista de todos os clientes e o status de cada um relacionado ao acesso ao Code Pay.

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

É aqui que verificamos se o cliente já ativou a conta no Code Pay. Lista dos status:\


| Status                     | Descrição                                                                      |
| -------------------------- | ------------------------------------------------------------------------------ |
| Ativo                      | O cliente fez o primeiro acesso e criou a sua senha.                           |
| Aguardando Primeiro Acesso | O cliente não realizou o primeiro acesso para criar a senha.                   |
| Inativo                    | O cliente foi inativado internamente e por isso não possui acesso ao Code Pay. |

Se o cliente estive com o status  **"Aguardando Primeiro Acesso"** é possível reenviar o email de Primeiro Acesso para o email que está cadastrado na conta dele.-

* Clique no ícone de envio de email e selecione o email de Primeiro Acesso.
* Informe o seu código de segurança (2fa) e clique em Reenviar Email.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Caso o cliente precise das sua credencias para acessar o Gateway de pagamentos via API, é possível reenviar o email de Credenciais. Apenas seguir os mesmo passos do item anterior selecionando o email **Credenciais**.

{% hint style="warning" %}
Os dois emails sempre são enviados no momento da criação da conta do cliente gateway.
{% endhint %}
