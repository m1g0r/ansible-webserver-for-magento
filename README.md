For ubuntu 14.04 LTS
Run with: 
ansible-playbook -i hosts magento.yml

Install:
perconaDB
Nginx (and copy virtualhost config for magento port 8080 & create symlink)
Varnish (port 80, and copy config)
php-fpm (and copy config to pool)
memcache
util (mc, htop, vim)