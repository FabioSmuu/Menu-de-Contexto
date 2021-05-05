# Repositorio de arquivos regedit.

[![N|Solid](https://cdn.discordapp.com/attachments/631607183301148672/724397007170568313/paypal.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=fabinhoec2210@gmail.com&item_name=F%C3%A1bio&currency_code=BRL)  [![N|Solid](https://cdn.discordapp.com/attachments/631607183301148672/724397005543178270/picpay.png)](https://app.picpay.com/user/smuu)

Este é um projeto simples e rápido, com o intuito de criar menus de contexto para rodar um programa ou arquivo em lote.

> Verifique também meu repositório para a criação de uma [extensão](https://github.com/FabioSmuu/.Deeh) com menu de contexto.

Imagem de exemplo:

![N|Solid](https://cdn.discordapp.com/attachments/837842973537730580/839611751871807498/unknown.png)

### Oque alterar:
- Procure por `NOMEdoCONTEXTO` (existe 2 em cada arquivo)
- Altere ou remova `--parametros` do diretório, pois, se refere aos parâmetros levado para a aplicação.
- Em Icon, coloque o caminho onde se encontra o ícone ou executável.
- Na última linha, coloque o diretório do arquivo seguido do parâmetro `%v`.

### Informativo:
- O parâmetro `%v`, serve pra indicar ao programa o argumento referente ao arquivo que será levado para dentro da aplicação.
- Você pode usar tanto bat, quanto executeis e até mesmo binários ou comandos.
- O uso de variáveis de ambiente como `%programfiles%`, funciona como valor.


Descrição dos arquivos:
- [Background](/Background.reg) Cria um menu de contexto na desktop e na background de pastas.
- [Directory](/Directory.reg) Cria um menu de contexto em pastas e diretórios.
- [File](File.reg) Cria um menu de contexto em todos os arquivos com e sem extensões.

**Obrigado pela sua atenção!**
