# Política de privacidade do Nimbo

Vale para o aplicativo Nimbo e para a extensão "Nimbo Download Manager" (Firefox, Chrome, Edge, Brave e outros
navegadores Chromium). Última atualização: 22 de novembro de 2026.

## Resumo

O Nimbo não coleta, não vende e não envia seus dados para ninguém. Não há conta, servidor, anúncios nem telemetria.

## O que a extensão faz com os seus dados

Quando um download é entregue ao Nimbo, a extensão manda para o **aplicativo Nimbo no seu próprio computador**
(endereço `127.0.0.1`, que não sai da sua máquina):

- o link do arquivo, o nome sugerido e o endereço da página de onde ele veio;
- os cookies do site desse link, para que downloads de sites com login funcionem;
- o identificador do navegador (user agent).

Esses dados vão apenas para o aplicativo, que os usa para fazer o download e guarda a lista de downloads no seu
computador. Nada é enviado para servidores do Nimbo — eles não existem.

A extensão também guarda no próprio navegador se a captura está ligada e o estado da conexão com o aplicativo.

## Permissões da extensão

- **downloads**: ver os downloads que começam no navegador e entregá-los ao Nimbo.
- **cookies**: enviar ao Nimbo os cookies do site do download, para que sites com login funcionem.
- **webRequest** e acesso a todos os sites: perceber vídeos e transmissões tocando na página, para oferecer o download.
- **contextMenus**: o item "Baixar com o Nimbo" no botão direito.
- **scripting** e **activeTab**: ler os links da página aberta quando você pede "Baixar todos os links".
- **tabs**: saber a página e o título do vídeo que você quer baixar.
- **storage**: guardar as preferências da extensão.

## O aplicativo

O aplicativo baixa os arquivos direto dos sites que você escolheu. Para vídeos, ele baixa e atualiza ferramentas
públicas (yt-dlp, FFmpeg e Deno) dos repositórios oficiais delas no GitHub, e procura atualizações do próprio Nimbo
neste repositório. Nenhum dado pessoal vai junto nesses pedidos.

## Contato

Dúvidas: abra uma [issue](https://github.com/blat0r/nimbo-download-manager/issues).

---

# Nimbo privacy policy (English)

Nimbo collects nothing, sells nothing and sends your data to no one: no account, no server, no ads, no telemetry.
The extension sends the download link, file name, source page, that site's cookies and the user agent only to the
Nimbo app on your own computer (`127.0.0.1`), which uses them to perform the download. Nothing leaves your machine
except the download requests to the sites you chose.
