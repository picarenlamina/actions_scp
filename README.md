#Desplegar con GitActions en AWS


--Desplegar un sitio web con GitHub Actions
https://desarrolloweb.com/articulos/desplegar-github-actions
https://github.com/marketplace/actions/scp-files

--Existe nueva version que modifica formato
https://stackoverflow.com/questions/76029565/suddenly-cant-connect-without-a-private-ssh-key-or-password-in-github-actions


--Exportar key putty
https://gustavoramosm.medium.com/uso-de-claves-privadas-pem-para-conexi%C3%B3n-ssh-a-servidores-linux-usando-cli-b41e978883fb

--Abrir puerto 22 aws

https://www.digitalocean.com/community/tutorials/como-configurar-un-firewall-con-ufw-en-ubuntu-18-04-es
$sudo ufw allow 22

--Permitir escritura directorio /var/www/html

https://usuariodebian.blogspot.com/2020/09/apache-permisos-usuario-y-grupo-www-data.html
$sudo chown -R www-data:www-data /var/www/html   
$sudo  chmod -R g+w /var/www/htmlml
$sudo usermod -a -G www-data ubuntu


