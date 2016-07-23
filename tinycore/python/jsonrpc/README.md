$ docker build -t tinycore/python/jsonrpc .<br>
$ docker run -it --rm tinycore/python/jsonrpc python -c 'help("modules")'|grep json<br>
_codecs_kr          audioop             json                socketserver<br>
_codecs_tw          base64              jsonrpc             spwd<br>
_json               contextlib          numbers             termios<br>
