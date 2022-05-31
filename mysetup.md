

autoload -U +X bashcompinit && bashcompinit
autoload -Uz compinit && compinit

complete -C aws_completer aws
complete -o nospace -C /usr/local/bin/terraform terraform

aws configure
