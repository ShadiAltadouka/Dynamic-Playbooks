.
└── playbooks
    ├── dynamic_apache.yml
    ├── group_vars
    │   ├── all
    │   │   └── vars
    │   ├── dbservers
    │   │   └── vars
    │   └── webserver
    │       └── vars
    ├── host_vars
    │   ├── ec2-23-22-211-232.compute-1.amazonaws.com.yml
    │   ├── ec2-3-88-51-2.compute-1.amazonaws.com.yml
    │   └── ec2-52-91-5-81.compute-1.amazonaws.com.yml
    ├── inventory
    ├── roles
    │   ├── copy_document_root
    │   │   ├── handlers
    │   │   │   └── main.yml
    │   │   ├── tasks
    │   │   │   └── main.yml
    │   │   └── templates
    │   │       └── index.html.j2
    │   └── install_apache
    │       ├── handlers
    │       │   └── main.yml
    │       ├── tasks
    │       │   └── main.yml
    │       └── templates
    └── static_apache.yml
