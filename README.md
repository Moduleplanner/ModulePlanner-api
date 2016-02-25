# ModulePlanner

A website to help students choose their modules

Installation
============

To run this locally on your machine first clone this repository

```
$ git clone https://github.com/Huaraz2/ModulePlanner.git
```

Then run the following commands:
```
$ cd ModulePlanner  
$ sudo pip install virtualenv
$ virtualenv venv
$ . venv/bin/activate
$ pip install Flask
```

Finally and open your web browser to the address
```http://localhost:8000/main.html``` and you should be able to use the website



Contributing
============

There are many tasks that need completing before this can even be considered
useful:

  - Students should be able to select the modules they wish to take
  - Students should be able to select their degree scheme as this alters which
    modules are core and what optional modules are available
  - Modules should grey-out as they become unavailable
  - We need a good way of handling the placement of modules on screen
    so that related modules are placed near each other so that we dont have a
    mess.
