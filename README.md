# config_srv_ajax
la configuration  du serveur wamp,pour l'acceptation d'autre url en dehors de notre de domaine

On fait un copier/coller à la fin du fichier **httpd.conf** qui se trouve à l'emplacement suivant pour moi wamp est
installer le disque C :
**C:\wamp64\bin\apache\apache2.4.33\conf\httpd.conf**
<pre><code>

<IfModule mod_headers.c>
	# Accept cross-domain requests
	Header always set Access-Control-Allow-Origin "*"
	Header always set Access-Control-Allow-Headers "Content-Type"
</IfModule>

</code></pre>
la première modification 
la dernière modification
