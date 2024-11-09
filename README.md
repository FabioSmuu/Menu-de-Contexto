# Repositorio de arquivos regedit.

Este é um projeto simples e rápido, com o intuito de criar menus de contexto para rodar um programa ou arquivo em lote.

> Verifique também meu repositório para a criação de uma [extensão](https://github.com/FabioSmuu/.Deeh) com menu de contexto.

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
