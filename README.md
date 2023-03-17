## Simple docker setup for testing wordpress plugins
Run the container once to initialize, then docker-compose down    
Change the line in docker-compose to use local volume, docker-compose up    
This will copy the wordpress installation to /wordpress    
Symlink your plugin dir to wordpress/wp-content/plugins    
``` sudo ln -s ~/moo_filter/moofilter ~/wpfilter/wordpress/wp-content/plugins ```

