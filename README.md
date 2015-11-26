
# Set initial configuration

heroku config:set AUTH_KEY='fNV9n1zB7tTzM4GxL9S45uvtqKiziEQp' SECURE_AUTH_KEY='545naqA7XLAez91JaxdF8AQ2y1bAj9Eb' LOGGED_IN_KEY='KjiURqBlxlFXGOX1eJc9N4Lq3tCoQpWg' NONCE_KEY='dA8C7UezP70AV7ra4WJ9v5ePY2JKH7zi' AUTH_SALT='XWS4EBbFCFD2s6DmNXkbDhaJzYSeS1QN' SECURE_AUTH_SALT='x5T66lKUQq6jX9bFMU9Uay5dCgQBXBau' LOGGED_IN_SALT='fLwMflBEoJ5VonyfViqbOdrEF3ksqI2y' NONCE_SALT='8wz3wnnm82pFs50vkPnS2wCJ7wQlUsgb'


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