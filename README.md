# Xray-core-UPX

Сжатые с помощью UPX бинарники xray-core для установки во внутреннюю память роутеров

## Прямые ссылки на загрузку

Для роутеров на процессорах arm64 - [xray-linux-arm64-v8a](https://github.com/jameszeroX/Xray-core-UPX/releases/latest/download/Xray-linux-arm64-v8a.zip)

Для роутеров на процессорах mips32le - [xray-linux-mips32le](https://github.com/jameszeroX/Xray-core-UPX/releases/latest/download/Xray-linux-mips32le.zip)

Для роутеров на процессорах mips32 - [xray-linux-mips32](https://github.com/jameszeroX/Xray-core-UPX/releases/latest/download/Xray-linux-mips32.zip)

Для роутеров Keenetic Skipper 4G (KN-2910) и Keenetic 4G (KN-1212) - [xray-linux-mips32le](https://github.com/jameszeroX/Xray-core-UPX/releases/latest/download/Xray-linux-mips32le-softfloat.zip)

##

Требуемую архитектуру бинарника для вашего роутера можете посмотреть в [таблице](https://github.com/jameszeroX/XKeen/wiki/Routers-Info)

##

## Порядок установки

Применительно к роутерам Keenetic с установленной средой Entware:
- Загрузить и распаковать архив необходимой архитектуры
- Поместить бинарник xray в папку /opt/sbin/
- Сделать бинарник исполняемым командой `chmod +x /opt/sbin/xray`

## Источник

https://github.com/XTLS/Xray-core
