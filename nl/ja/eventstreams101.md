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

# MQ Light Python クライアントの使用
{: #mql_python}

**MQ Light API は、標準プランのみの一部として使用可能です。**
<br/>

この API を使用するには、以下のように、Python 用の最新の使用可能な {{site.data.keyword.mql}} クライアント API への参照を追加する必要があります。

<code>requirements.txt</code> ファイルに次の参照を追加します。

```
git+git://github.com/mqlight/python-mqlight.git@readthedocs
```
{:codeblock}

<br>
ソース・ファイルに次の import ステートメントを追加します。

```
import mqlight
```
{:codeblock}

<!-- Comment from Andrew
Instructions for getting started, with links for more info
Simple send source and receive source in-line

-->

