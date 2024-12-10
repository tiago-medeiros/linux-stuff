#### Daily Heroes:
- ps aux | grep {process} - Encontre aquele processo furtivo
- lsof -i :{port} - Quem está monopolizando aquela porta?
- df -h - O clássico verificador de "estamos sem espaço"
- netstat -tulpn - Detetive de conexão de rede
- kubectl get pods | grep -i error - Localizador de problemas do K8s

#### Log Warriors:
- tail -f /var/log/* - Observador de log em tempo real
- journalctl -fu service-name - Perseguidor de log do SystemD
- grep -r "error" . - O caçador de erros
- zcat access.log.gz | grep "500" - Ninja de log compactado
- less +F - O melhor comando tail

#### Container Whisperers:
- docker ps --format '{{.Names}} {{.Status}}' - Verificação de status limpa
- docker stats --no-stream - Verificação rápida de recursos
- crictl logs {container} - Histórias brutas de contêineres
- docker exec -it - O backdoor do contêiner
- podman top - Espiada de processos dentro de contêineres

#### System Detectives:
- htop - Contador de histórias de recursos do sistema
- iostat -xz 1 - Poeta de desempenho de disco
- free -h - Solucionador de mistérios de memória
- vmstat 1 - Sinais vitais do sistema
- dmesg -T | tail - Fofocas recentes do Kernel

#### Network Ninjas:
- curl -v - Depurador de conversação HTTP
- dig +short - Pesquisa rápida de DNS
- ss -tunlp - Estatísticas de socket simplificadas
- iptables -L - Leitor de regras de firewall
- traceroute - Localizador de caminho

#### File Jugglers:
- find . -name "*.yaml" -type f - Caçador de YAML
- rsync -avz - Melhor copiador de arquivos
- tar -xvf - O descompactador (sim, todos nós pesquisamos isso no Google)
- ln -s - Assistente de Symlink
- chmod +x - Torna executável

#### Performance Profilers:
- strace -p {pid} - Espião de chamada de sistema
- tcpdump -i any - Farejador de pacotes de rede
- sar -n DEV 1 - Monitoramento de estatísticas de rede
- uptime - Média de carga em resumo
- top -c - Visualizador de processos clássico

#### Git Essentials:
- git log --oneline - Histórico simplificado
- git reset --hard HEAD^ - Apagador de "oops"
- git stash - O ocultador de trabalho
- git diff --cached - O que é preparado?
- git blame - O resolvedor "quem fez isso?"

#### Correções rápidas:
- sudo !! - Execute o último comando com sudo
- ctrl+r - Pesquisa de histórico de comandos
- history | grep - Máquina do tempo de comando
- alias - Criador de atalhos de comando
- watch - Repetidor de comandos