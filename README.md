# application_TTN_Node-RED
Explorando APIs e nodes TTN

A boa dica desta vez será um fluxo de monitoramento de falhas de gateways (Gateway Management). Na verdade, nada foi inventado, pois este trabalho foi inspirado e adaptado da comunidade TTN de Barcelona (https://tinkerman.cat/post/monitor-your-ttn-gateways-with-node-red). 

A ideia se baseia em utilizar algumas APIs, meio que perdidas no “limbo”, para checar o status (on-line ou off-line) dos gateways numa determinada região e, melhor ainda, ser alertado por meio do envio de mensagem pelo Telegram quando houver alguma alteração de status.

Bem, faz-se necessário saber mexer um pouco com o Node-RED, descobrir o ID dos gateways-alvos de interesse e configurar apropriadamente o Node Telegram. Simplesmente, importe o código (gw-management.json) para o seu Node-RED e faça as adaptações necessárias para sua rede.

![tela Node-RED](https://github.com/Mario-Camara/application_TTN_Node-RED/blob/main/tela_gw-management.jpg)
