FROM debian: 9.5-slim

LABEL  "com.github.actions.name" = "Olá, mundo" 
LABEL  "com.github.actions.description" = "Grave argumentos na saída padrão" 
LABEL  "com.github.actions.icon" = "mic" 
LABEL  " com.github.actions.color " = " roxo "

LABEL  "repository" = "http://github.com/octocat/hello-world" 
LABEL  "homepage" = "http://github.com/actions" 
LABEL  "mantenedor" = "Octocat <octocat@github.com> "

ADD entrypoint.sh /entrypoint.sh
 EXECUTAR chmod + x /entrypoint.sh
 ENTRYPOINT [ "/entrypoint.sh" ]
