# Arquivo ls.c Modificado
A modificação adiciona a opção --gustavomezomo.

## Codigos adicionados:

no long_options
```bash
{"gustavomezomo", no_argument, nullptr, 1000},
```

no switch (c)
```bash
 case 1000:
       printf("print trabalho Gustavo Mezomo\n");
       exit(0);
```

deve ser substituido na pasta: 
```bash
src/
```
do código-fonte do coreutils.

## Gustavo Mezomo
