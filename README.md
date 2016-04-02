# drushHelper

1- Take a snapshot of the production environment (database and filesytem)

Go in the root of the site

```
drush ard
```

2- Move the dump to the development site


I use a Virtual VM and FileZilla to ftp my backup.

3- Restore the snapshot on the development server

Go in the root of the site

```
drush arr ~/example.tar.gz
```