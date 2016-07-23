$ docker build -t tinycore/python/jsonrpc .
$ docker run -it --rm tinycore/python/jsonrpc python -c 'help("modules")'|grep json
_codecs_kr          audioop             json                socketserver
_codecs_tw          base64              jsonrpc             spwd
_json               contextlib          numbers             termios
