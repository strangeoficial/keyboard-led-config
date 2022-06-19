# keyboard-led-config

Aqui fica os arquivos de configurações do meu teclado led para todas bases linux, use esses arquivos quando o seu teclado de alguma forma não estar ascendendo o seu led.

### Adicionando as configurações

Os comandos a seguir irão substituir seus arquivos atuais, faça um backup da pasta antes de seguir.

```sh
  mkdir ~/Backups/
  cp /usr/share/X11/xkb/symbols/* ~/Backups/
  sudo cp files/{us,br} /usr/share/X11/xkb/symbols/
```

Logo depois reiniciei ou faça logout!!
