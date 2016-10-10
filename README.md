For ubuntu 14.04 LTS<br>
Run with: <br>
ansible-playbook -i hosts magento.yml<br><br>

Install:<br>
<ul>
	<li>perconaDB</li>
	<li>Nginx (and copy virtualhost config for magento port 8080 & create symlink & copy php info file to www root)</li>
	<li>Varnish (port 80, and copy config)</li>
	<li>php-fpm (and copy config to pool)</li>
	<li>memcache</li>
	<li>util (mc, htop, vim)</li>
</ul>