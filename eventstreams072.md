---

copyright:
  years: 2015, 2018
lastupdated: "2018-10-29"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}


#Monitoring and logging (Standard plan)
{: #monitoring}

{{site.data.keyword.messagehub}} on the Standard plan automatically collects metrics and events so that you
can monitor your usage of {{site.data.keyword.messagehub}}.
{:shortdesc}

**Note:** Metrics and events are available as part of the {{site.data.keyword.messagehub}} Standard plan in US South, (Dallas), UK South (London), and AP South (Sydney) only. 


You can monitor the following log information:

<dl>
<dt>Topic metrics</dt>
<dd>We send the number of bytes in and out for each of your topics (a
checkpoint is taken every 15 minutes). You can access these metrics by clicking the
**Grafana** button on the {{site.data.keyword.messagehub}} dashboard in the {{site.data.keyword.Bluemix_notm}} console.
</dd>
<dt>Topic events</dt>
<dd>We also push events each time you create or delete a topic. You can
access these events by clicking the **Kibana** button on the {{site.data.keyword.messagehub}} dashboard in the {{site.data.keyword.Bluemix_notm}} console.</dd>
</dl>


We recommend that you don't edit the {{site.data.keyword.messagehub}} dashboards
because {{site.data.keyword.messagehub}} makes updates that might overwrite your
changes. However, you can include these metrics and events in
your own dashboards.


