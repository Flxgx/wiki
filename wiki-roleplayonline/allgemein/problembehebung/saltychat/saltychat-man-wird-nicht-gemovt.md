---
icon: arrow-turn-left-down
---

# Saltychat ("Man wird nicht gemovt")

Aufgrund fehlender DNS Einstellung kann es vor kommen, dass man nicht in den Spiel-Channel gemovt wird. \
Um dies wieder nutzen zu können, müssen kleinere Einstellungen vorgenommen werden.\
\
Um die DNS Einstellungen vorzunehmen, benötigt man wenige Schritte. \
Diese werden Anhand von Windows 10 inklusive Ethernet-Verbindung gezeigt. \
Für Windows 11 sowie WLAN Einstellungen liegt ebenfalls nochmals ein Tutorial-Video im Anhang.



{% tabs %}
{% tab title="Schritt 1" %}
Suche in der Suchleiste nach <mark style="color:purple;">Ethernet</mark> und anklicken.<br>

<figure><img src="../../../.gitbook/assets/image.png" alt="" width="166"><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Schritt 2" %}
Nun das gewünschte <mark style="color:purple;">Ethernet</mark> auswählen<br>

<figure><img src="../../../.gitbook/assets/Screenshot 2025-02-19 042317.png" alt="" width="169"><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Schritt 3" %}
Nun klicke bei IP-Einstellungen auf <mark style="color:purple;">Bearbeiten</mark> und gebe <mark style="color:purple;">Manuell</mark> an<br>

<figure><img src="../../../.gitbook/assets/image (1).png" alt="" width="226"><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Schritt 4" %}
Setze nun die Felder von <mark style="color:purple;">IPv4</mark> sowie <mark style="color:purple;">IPv6</mark> auf <mark style="color:green;">AN</mark><br>

<figure><img src="../../../.gitbook/assets/image (2).png" alt="" width="193"><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Schritt 5.1" %}
Gebe nun im Feld von <mark style="color:purple;">IPv4</mark> bei folgenden Feldern, folgender Inhalt ein:\
\- <mark style="color:purple;">Bevorzugter DNS</mark>\
<mark style="background-color:red;">8.8.8.8</mark>\
\- <mark style="color:purple;">Alternativer DNS</mark>\
<mark style="background-color:red;">8.8.4.4</mark><br>

<figure><img src="../../../.gitbook/assets/image (4).png" alt="" width="172"><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Schritt 5.2" %}
Ebenfalls nun im Feld von <mark style="color:purple;">IPv6</mark> bei folgenden Feldern, folgender Inhalt ein:\
\- <mark style="color:purple;">Bevorzugter DNS</mark>\
2001:4860:4860::8888\
\- <mark style="color:purple;">Alternativer DNS</mark>\
2001:4860:4860::8844<br>

<figure><img src="../../../.gitbook/assets/image (5).png" alt="" width="181"><figcaption></figcaption></figure>

Nun nurnoch auf <mark style="color:purple;">Speichern</mark> und die DNS Einstellungen sind beendet
{% endtab %}
{% endtabs %}

{% embed url="https://www.youtube.com/watch?v=8_WdRqG1BEw" %}

