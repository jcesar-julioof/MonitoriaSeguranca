# Projeto: Monitor na Matéria de Segurança de Redes

## 📌 Descrição

Projeto desenvolvido durante monitoria da disciplina de Segurança de Redes (Out/2025 – Dez/2025), com foco na implementação de segmentação lógica utilizando VLANs no Cisco Packet Tracer.

### Atividade 1

O laboratório simula um ambiente corporativo com separação de setores (TI, Administrativo e CFTV), controle de acesso e comunicação entre switches via trunk.

Crie uma infraestrutura de rede física com as seguintes características:

1. Utilize dois switches gerenciaveis (esquerda.localdomain e direita.localdomain).
2. Configure os switches para utilizar a senha 123456 para o acesso via console e 654321 para o acesso ao modo privilegiado.
3. Configure o nome dos switches;
4. Utilize o seguinte banner para o acesso ao switches:

```
Instituto Federal de Goiás
Campus Luziânia
Equipamento monitorado
```

5. Habilite o acesso remoto ao terminal dos switches por meio do usuário “admin” e senha “cisco”.
6. Crie a VLAN de número 10 nos dois switches com nome “ti” e adicione o IP 192.168.0.1/24 para o primeiro switch e 192.168.0.2/24 para o segundo switch.
7. Separe as portas 1 a 5 do switch esquerda.localdomain para a VLAN ti e insira um computador com endereço IP fixo 192.168.0.3/24.
8. Nos dos switches, crie as VLANs 20 e 30 respectivamente com nome “administrativo” e “cftv” e adicione as portas abaixo:

(a) esquerda.localdomain: portas 6 a 10 para cftv e 11 a 24 para administrativo.
(b) direita.localdomain: portas 1 a 10 para cftv e 11 a 24 para administrativo.

9. Interligue os dois switches pela porta GigabitEthernet0/1 utilizando um tronco com as 3 VLANs (ti, administrativo e cftv).
10. Insira um computador em cada switch para a vlan cftv com endereço IP fixo na rede 172.16.0.0/16.
11. Insira um servidor na vlan administrativo com IP 10.0.0.1/8 e habilite o DHCP para oferecer endereços na rede.
12. Insira um computador em cada switch na vlan administrativo e configure estes equipamentos para pegar endereço via DHCP.
13. Verifique a conectividade em cada uma das VLANs.

[Script para utilizado:]()

### Atividade 2

