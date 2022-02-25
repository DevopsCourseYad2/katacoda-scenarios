# katacoda-scenarios


## Create a new scenario

``` shell
> tree -l
.
├── README.md
├── linux-essentials
│   ├── cpu
│   │   ├── index.json
│   │   ├── intro.md
│   │   ├── setup.sh
│   │   └── step1.md
│   └── file-system
│       ├── index.json
│       └── step1.md
└── linux-essentials-pathway.json

> katacoda courses:create
? Course Title:  Web Applications
? Course Description:  Web Applications description
? friendly-url (This will also be the course\'s folder name):  web-applications
Course created successfully.

> katacoda scenarios:create
? Friendly url:  load-balancing
? Scenario Title:  Load Balancing
? Scenario Description:  Load Balancing Description
? Difficulty Level:  Beginner
? Estimated time: (Please specify in minutes or hours e.g. 2 hours) 60 minutes
? Number of Steps (Not including intro & finish):  2
? Image:  python:3.8
? Layout:  Terminal
Scenario created successfully.


```

