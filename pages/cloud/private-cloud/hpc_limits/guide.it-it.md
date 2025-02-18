---
title: Capacità tecniche
slug: capacita-tecniche
excerpt: Ritrova le capacità e i limiti tecnici delle soluzioni Hosted Private Cloud fornite da OVHcloud
section: FAQ
order: 2
updated: 2023-03-23
---

> [!primary]
> Questa traduzione è stata generata automaticamente dal nostro partner SYSTRAN. I contenuti potrebbero presentare imprecisioni, ad esempio la nomenclatura dei pulsanti o alcuni dettagli tecnici. In caso di dubbi consigliamo di fare riferimento alla versione inglese o francese della guida. Per aiutarci a migliorare questa traduzione, utilizza il pulsante "Modifica" di questa pagina.
>

**Ultimo aggiornamento: 23/03/2023**

## Obiettivo

**Questa pagina fornisce una panoramica delle funzionalità e dei limiti tecnici dei servizi Hosted Private Cloud OVHcloud.**

## Capacità e limitazioni note

| Elemento | Descrizione | Valore |
|:-----:|:-----:|:----------:|
| Numero max. di PCC per ID cliente | Numero di vCenter o di pack per organizzazione | Nessun limite |
| Numero di PCC associati | Connessione di vCenters (Enhanced Link Mode) | 0 (non autorizzato) |
| Numero min. di datastore per PCC (SLA) | Numero di datastore per vCenter per mantenere il contratto di livello di servizio | 2 |
| Numero min. di host per PCC (SLA) | Numero di host per vCenter per mantenere il contratto di livello di servizio | 2 |
| Numero min. di host per PCC (senza SLA) | Numero minimo di host da utilizzare con vCenter senza contratto di livello di servizio | 0 |
| Numero max. di host per cluster | Host per cluster | 64 |
| Numero max. di cluster per vDC | Numero di cluster nello stesso datacenter virtuale | Nessun limite |
| Numero max. di vDC per PCC | Il numero di datacenter virtuali (vDC) che i clienti possono aggiungere per vCenter | 400 |
| Numero max. di host per PCC | Limiti host per vCenter | 231 |
| Numero max. di datastore per PCC | Limiti di datastore per vCenter | 110 |
| Numero max. di macchine virtuali tramite SDDC | VM gestite dallo stesso vCenter | 25 000 |
| Numero max. di macchine virtuali per host | VM ospitate sullo stesso host fisico | 1024 |
| Numero max. di indirizzi IP per PCC | Numero max. di indirizzi IP pubblici che possono essere attribuiti e utilizzabili dal vCenter | 1 x /23 |
| vCPU, RAM e disco utilizzati da vCenter standard | Risorse assegnate a vCenter (VCSA) | 4 processori virtuali, 16 GB di RAM, 290 GB di spazio disco |
| vCPU, RAM e disco utilizzati da NSX standard | Risorse assegnate al Manager e al Controller NSX | 4 CPU virtuali, 4 GB di RAM, 60 GB di spazio disco<br>4 CPU virtuali, 2 GB di RAM, 28 GB di spazio disco |
| vCPU, RAM e disco utilizzati da vROPS | Risorse assegnate a vROPS | 4 processori virtuali, 16 GB di RAM |
| Numero max. de edge nodes | Numero max. di periferiche da implementare da NSX | 2000 |
| Numero max. di tunnel VPN IPSec | Numero max. di gallerie VPN per estensione | 512 comppact edge<br>1600 large<br>4096 quad large edge<br>6000 extra large |
| Numero max. di vRack per vDC | Numero max. di reti private via Virtual Data Center (VDC) | 1 |
| Numero max. di clienti VPN L2 | Numero di clienti VPN da collegare | 5 |
| Numero max. di indirizzi IP autorizzati | Numero di indirizzi IP autorizzati a connettersi alla tua infrastruttura VMware | 2048 |

## Per saperne di più

Unisciti alla nostra Community di utenti <https://community.ovh.com/en/>.
