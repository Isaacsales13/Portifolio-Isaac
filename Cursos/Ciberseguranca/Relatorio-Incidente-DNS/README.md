# Relatório de Incidente de Segurança Cibernética

Este projeto documenta a análise de tráfego de rede referente ao erro **udp port 53 unreachable**, ocorrido ao tentar acessar o domínio `www.yummyrecipesforme.com`.

## Evidência do erro
![Erro DNS](Erro%20DNS.png)

## Relatório técnico
O relatório completo está disponível em [relatorio](Relatorio%20DNS.pdf).

### Resumo
- Porta 53 (DNS) inacessível, mensagem ICMP: *udp port 53 unreachable*.
- Incidente às 13:24h durante acesso ao domínio.
- Possíveis causas:
- Servidor DNS fora do ar ou não configurado.
- Bloqueio de tráfego na porta 53 por firewall ou restrição de rede.

