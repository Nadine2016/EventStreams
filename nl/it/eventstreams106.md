---

copyright:
  years: 2015, 2018
lastupdated: "2018-05-25"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# Che cos'è l'API MQ Light e in che cosa è differente?
{: #mqlight}

** L'API MQ Light è disponibile solo come parte del piano Standard.**
<br/>

L'API {{site.data.keyword.mql}} fornisce un livello di astrazione superiore per la messaggistica, rispetto a Kafka.
{:shortdesc}

La scelta tra l'utilizzo di un client Kafka o dell'API {{site.data.keyword.mql}} dipende dalla topologia di messaggistica che vuoi
creare:

* Con Kafka, utilizzi un numero ridotto di argomenti e puoi avere più partizioni per ogni argomento per una maggiore scalabilità. Puoi condividere i messaggi tra i consumatori utilizzando gruppi di consumatori, ma ogni consumatore deve essere in grado di mantenere il passo con la frequenza dei messaggi per le partizioni assegnate.
* Con l'API {{site.data.keyword.mql}}, puoi utilizzare un numero molto maggiore di argomenti e i nomi degli argomenti sono gerarchici (ad esempio: <code>‘/sports/football’</code> e <code>‘/sports/tiddlywinks’</code>). 

Gli argomenti nell'API {{site.data.keyword.mql}} non sono gli stessi
argomenti presenti in Kafka. Al contrario, la API {{site.data.keyword.mql}} utilizza
un singolo argomento Kafka chiamato "MQLight" e tutti i messaggi inviati e ricevuti utilizzando la API {{site.data.keyword.mql}} passano attraverso quel solo argomento Kafka.

{{site.data.keyword.mql}} è disponibile solo nelle regioni
{{site.data.keyword.Bluemix_notm}} Stati Uniti Sud, Regno Unito e Sydney. La API MQ Light non è disponibile nella regione Germania o in
{{site.data.keyword.Bluemix_notm}} dedicato.

<!-- begin STAGING ONLY -->
Per ulteriori informazioni sulla scelta tra le API, consulta [Scelta tra le tre API](/docs/services/EventStreams/eventstreams087.html).
<!-- end STAGING ONLY -->

