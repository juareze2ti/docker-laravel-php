# docker-laravel-php


## Configurações adicionais do php
- criar volume referenciando arquivo: `<path-config>/config.ini:/usr/local/etc/php/conf.d/config.ini:ro`

## Sintetizador de voz
- criar volume referenciando licenca: `<path-licenca>/licenca.txt:/usr/vt/helena/P16/data-common/verify/verification.txt:ro`

## Exemplo arquivo `<path-config>/config.ini`

````
post_max_size = 200M
upload_max_filesize = 200M
max_execution_time = 900
memory_limit = 1024M
date.timezone = America/Campo_Grande
max_input_vars = 9000
````
