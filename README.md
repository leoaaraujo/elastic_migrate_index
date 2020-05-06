# Playbook for Index Elasticsearch Migration



````
$ git clone https://github.com/leoaaraujo/elastic_migrate_index && cd elastic_migrate_index
````

````
$ ansible-playbook -i inventory migrate.yaml
````


````
.
├── README.md
├── ansible.cfg
├── inventory
├── migrate.yaml
└── roles
    └── elastic_migrate_index
        ├── handlers
        │   └── main.yml
        └── tasks
            └── main.yml

4 directories, 6 files
````
