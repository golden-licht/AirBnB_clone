# AirBnB_clone - The console

This repo contains a command interpreter to manage AirBnB objects. It is the first phase of building a simple [AirBnB](https://www.airbnb.com/) clone.

|![General architecture of simple AirBnB clone](./imgs/arch_console_phase.png)|
|:--:|
| *General architecture of simple AirBnB clone* |

In this phase a JSON file is used as a storage, which will be replaced by a Database (MySQL) in the coming phases.

## project structure
```
.
├── console.py
├── file.json
└── models
    ├── amenity.py
    ├── base_model.py
    ├── city.py
    ├── engine
    │   └── file_storage.py
    ├── place.py
    ├── review.py
    ├── state.py
    └── user.py
```
|![Class diagram](./imgs/class_diagram.jpg)|
|:--:| 
| *Class diagram* |

## demo of the command interpreter

The command interpreter contains small list of commands 

```
$ ./console.py 
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

(hbnb) help create
Creates a new instance of BaseModel

(hbnb) create BaseModel
69ae5c55-313e-4a1a-8134-d195ba2c9791

(hbnb) quit

$
```
