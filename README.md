
## Donation | Doações

(En)      Support our project via Pix or PayPal. <br />
(Pt-Br) Apoie nosso projeto via Pix ou PayPal: <br />

- Brazilian Pix: d56da244-4dc5-4f77-be6d-28e94fdd46b2 <br />
- Paypal:  https://bit.ly/MonitTelegram <br /><br />

## Credits
- Original Project: https://github.com/CitraIT/pfsense_citra_patches/tree/main/telegram_logon_event
- Author: Luciano Rodrigues

<br /><br />


# pfSense_Telegram_Login - Overview
Patch for pfSense: When someone logs in or tries to log in to pfSense, it sends a standard message to Telegram. This patch changes the standard message to a custom message that is easier to read and visually more appealing. <br />

## Tested Versions
  2.7.0, 2.7.1, 2.7.2

## Screenshot
![Screenshot](https://github.com/macielmeireles/pfSense_Telegram_Login/blob/main/_screenshot.png)


### Prerequisites
1) Configured a gateway group in pfSense.
2) Have Telegram installed and configured.
3) Completed the integration procedure between Telegram and pfSense.
4) Ensure that pfSense already sends the default message to your Telegram when one of the links becomes unavailable, for example.


### Installation
0) Install "System Patches" package via Package Manager (System - Package Manager).
1) Log in as an administrator via pfSense GUI.
2) Click on System, Patches.
3) Click on Add New Patch.
4) Fill in the `description` field, suggestion: `telegram_status_multiwan`.
5) Fill in the `Patch Contents` field with the content of the file in raw format. For convenience, the link is here: [link](https://raw.githubusercontent.com/macielmeireles/pfSense_StatusMultiWan_Telegram/main/pfsense_telegram_status_multiwan.patch).
6) In the `Path Strip Count` field, change to 1.
7) Click on `Save` at the end of the page.
8) Apply, to use click on the apply button next to the name of the chosen patch in item 4.
9) If you prefer, it is possible to click on the revert button.


# pfSense_Telegram_Login - Visão Geral (pt-BR)
Patch para pfSense: Quando alguém faz login ou tenta fazer login no pfSense, ele envia uma mensagem padrão para o Telegram. Este patch altera a mensagem padrão para uma mensagem personalizada que é mais fácil de ler e visualmente mais bonita.


### Pré-requisitos
1) Configurar um grupo de gateways no pfSense.
2) Ter o Telegram instalado e configurado.
3) Completar o procedimento de integração entre o Telegram e o pfSense.
4) Certifique-se de que o pfSense já envia a mensagem padrão para o seu Telegram quando um dos links fica indisponível, por exemplo.


### Instalação
0) Instale o pacote "System Patches" via Package Manager (System - Package Manager).
1) Faça login como administrador via GUI do pfSense.
2) Clique em Sistema, Patches.
3) Clique em Adicionar Novo Patch.
4) Preencha o campo `descrição`, sugestão: `telegram_status_multiwan`.
5) Preencha o campo `Conteúdo do Patch` com o conteúdo do arquivo no formato raw. Para facilitar, o link está aqui: [link](https://raw.githubusercontent.com/macielmeireles/pfSense_StatusMultiWan_Telegram/main/pfsense_telegram_status_multiwan.patch).
6) No campo `Contagem de Retirada de Caminho`, altere para 1.
7) Clique em `Salvar` no final da página.
8) Aplique, para usar clique no botão aplicar ao lado do nome do patch escolhido no item 4.
9) Se preferir, é possível clicar no botão reverter.


