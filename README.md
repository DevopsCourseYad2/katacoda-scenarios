# katacoda-scenarios


## Layout
``` shell
> tree -l
.
├── README.md
├── assets
│   └── avatar.png
├── linux-essentials
│   ├── cpu
│   │   ├── index.json
│   │   ├── intro.md
│   │   ├── setup.sh
│   │   └── step1.md
│   └── file-system
│       ├── index.json
│       └── step1.md
├── linux-essentials-pathway.json
├── web-applications
│   └── load-balancing
│       ├── finish.md
│       ├── index.json
│       ├── intro.md
│       ├── step1.md
│       └── step2.md
└── web-applications-pathway.json
```

## Create a new course
``` shell
> katacoda courses:create
? Course Title:  Web Applications
? Course Description:  Web Applications description
? friendly-url (This will also be the course\'s folder name):  web-applications
Course created successfully.
```
## Create a new scenario
``` shell
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
## Add scenario to course
``` shell
> katacoda courses:add:scenarios
? Please enter scenario path ./load-balancing
? Please enter course path ./web-applications
? Would you like todo? Move to courses folder
```

