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

# Procédure de connexion et d'authentification
{: #rest_connect}

**L'API REST Kafka est disponible uniquement dans le cadre du plan Standard.**
<br/>

Pour se connecter à {{site.data.keyword.messagehub}}, l'API Kafka utilise les données d'identification <code>api_key</code> et <code>kafka_rest_url</code> provenant de la [variable d'environnement VCAP_SERVICES](/docs/services/EventStreams/eventstreams127.html).

Pour vous authentifier à l'API REST Kafka {{site.data.keyword.messagehub}}, vous devez spécifier l'attribut <code>api_key</code> dans l'en-tête X-Auth-Token de vos demandes.
