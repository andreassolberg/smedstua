
# Set initial configuration


# Update composer

composer update --ignore-platform-reqs
git add composer.lock
git commit -m 'Rebuild composer.lock'
git push heroku master


# Migrate database







# CMD

alias hb="composer update --ignore-platform-reqs && git add composer.json composer.lock"
alias hp="git push heroku master"



# Plugins


To be verified and installed. (if needed)


    "wpackagist-plugin/fourteen-extended-master": "*",


# Disabled plugins


    "wpackagist-plugin/wp-retina-2x": "~3.5",

    "wpackagist-plugin/memcached-cloud": "~1.0",






    ,
        "wpackagist-plugin/memcachier": "1.0.1"



NEXT:

w3 total cache: DISK


---

enable cahce = true

For å få denne til å fungere så må vi kjøre:

        "wpackagist-plugin/memcachier": "1.0.1"

cp wordpress/wp-content/plugins/memcachier/object-cache.php wordpress/wp-content/object-cache.php


+

BATCACHE:

cp wordpress/wp-content/plugins/batcache/advanced-cache.php wordpress/wp-content/advanced-cache.php