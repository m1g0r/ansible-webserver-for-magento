For ubuntu 14.04 LTS<br>
Run with: <br>
ansible-playbook -i hosts webserver_for_magento.yml<br><br>

Install:<br>
<ul>
	<li>perconaDB</li>
	<li>Nginx (and copy virtualhost config for magento port frontend SSL 443 and backend 8080 & create symlink & copy php info file to www root)</li>
	<li>Varnish (port 6081, and copy config)</li>
	<li>php-fpm (and copy config to pool)</li>
	<li>memcache</li>
	<li>util (mc, htop, vim)</li>
</ul>