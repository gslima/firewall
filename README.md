# Firewall espartano

Script de configuração de um firewall espartano, ou seja, um firewall que bloqueia quase todas as portas, somente permitindo o acesso por portas seguras (ssh, dns, http e https).

# Pré requisitos

- Distribuição linux com iptables

# Configuração

Por [Guilherme Lima](https://github.com/gslima)

A configuração do firewall é fácil, basta digitar:

```
iptables-restore firewall.rules
/etc/init.d/iptables save
```
