# laravel-installer

I got tired of editing the same files and making changes so that User.php was in App\Models\User namespace/folder. 

This installs laravel 5.7.9 (I cloned the laravel repo to: patrickcurl/laravel), and changed the installer to use that fork instead. 

This fork simply moves all model references to models, and fixes all mentions of User.php. 

installation: 

```composer global remove laravel/installer```

```composer global require patrickcurl/laravel-installer```

```laravel new test```
