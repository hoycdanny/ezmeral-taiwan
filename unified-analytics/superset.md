# Superset



```
docker run -d -p 8080:8088 -e "SUPERSET_SECRET_KEY=admin12345" --name superset apache/superset
```



```
docker exec -it superset superset fab create-admin --username admin --firstname Superset --lastname Admin --email admin@superset.com --password admin
```

```shell
docker exec -it superset superset db upgrade
docker exec -it superset superset load_examples
docker exec -it superset superset init
```



## This is a Heading

This is a paragraph.

<pre class="language-html"><code class="lang-html"><strong>&#x3C;html>
</strong><strong>&#x3C;h1>This is a Heading&#x3C;/h1>
</strong>&#x3C;p>This is a paragraph.&#x3C;/p>
&#x3C;iframe src="https://www.google.com" height="200" width="300" title="Iframe Example">&#x3C;/iframe>
&#x3C;/html>
</code></pre>

