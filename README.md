# GT People JSON data importer

## Notes on generating UUID
```
drush ev '$uuid_service=\Drupal::service("uuid");$uuid=$uuid_service->generate();echo "$uuid\n";'
```
