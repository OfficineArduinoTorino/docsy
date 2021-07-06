---
title: "Security report"
linkTitle: "Security report"
weight: 5
description: >

---

Molti dei servizi necessari al funzionamento del servizio sono hostati in cloud da AWS.
In virtù dell'affidabilità di tali servizi sarà necessario solo porre particolare cura nell’implementazione e hardening delle API.

L’attenzione va invece focalizzata sulla protezione dell’infrastruttura interna al ciclo rifugio.
L’home server infatti è un nodo nevralgico della struttura ed un eventuale attacco comprometterebbe non solo le automazioni del rifugio, ma anche la rete a monte.
Sarà necessario configurare delle policy di rete molto strette per ridurre la superficie d’attacco dei RevPi Core, e assicurarsi di applicare le opportune misure di hardening dei servizi esposti. In ultimo sarà necessario assicurarsi che il dispositivo sia protetto anche fisicamente, per impedire l’accesso ai non autorizzati.

 
 
