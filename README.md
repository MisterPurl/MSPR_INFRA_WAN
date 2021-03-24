# MSPR_INFRA_WAN

Ce repository regroupe les configurations des routeurs de l'infrastructure WAN du MSPR mais aussi les configuraions des firewalls pfsense et le cluster haproxy.
Pour une visualisation plus globale de l'architecture WAN -> check le schema_infra.png.

## HAPROXY
La configuration haproxy se trouve dans le sub-repository "haproxy". 
La configuration pour la Virtual IP qui permet une résillience en cas de perte d'un HAP se trouve dans le sub-repository "keepalived".

## FIREWALL
Les configurations des 3 firewalls mis en place sous regroupées dans le sub-repository "pfsense".