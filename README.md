# BlogBundle

### Enable Doctrine Extensions in config.yml:
``` yaml
stof_doctrine_extensions:
    orm:
        default:
          timestampable: true
          loggable: true
          blameable: true
          sluggable: true
```

Your also can import [YoushidoAdminBundle](https://github.com/Youshido/AdminBundle) config file from /config/admin/structure.blog.yml

