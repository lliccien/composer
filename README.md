Composer for Drupal

Example 

docker run --rm --interactive --tty \
           --volume $PWD:/app \
           lliccien/composer composer create-project drupal/drupal drupal-dir --prefer-dist --no-progress --no-interaction
