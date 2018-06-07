# WP_Plugins
# WPDEV

   ## Entorn de desenvolupament Web amb Wordpress 
 
Aquest Script per iniciar, aturar, reiniciar i eliminar el entorn de desenvolupament de Wordpress. 

Consta de un script amb **3** contenidors:

**1**.*dcsss-MariaDB* per desar les dades del Wordpress

**2**.*dcsss-httpd-wpdev* que consta de un apache amb el wordpress

**3**.*cloud9-docker* eina de desenvolupament en una navegador web
    

També te les facilitats de configurar els contenidors amb variables, com per exemple
posar un nom de domini per al Wordpress que s'ha d'indicar : -d "Nom de domini".


Exemple per fer servir el script:
**wpdev -d manager.swarm.asix run**
**wpdev stop**
