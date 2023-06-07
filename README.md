# Welcome to Fast API on Steroids(FAONS)!

Hi! we have created faons to help those who are struggling to setup a base project for fast api with swagger ui. My team used to either copy paste or create manually the files and folders necessary for fast api. But with this package anyone can easily start a fast api project.


## Installing

Use the command `pip install faons` to install the latest version of faons in your environment.

## Creating your first project

Once the package has been installed you can create your first project using the command `faons intializeproject <project_name>`.

## File structure

All your files and folders are created as per the below representation
```markdown
├── src
│   ├── config
│   │   ├── config.py
|   |   └── constants.py
│   ├── core
│   ├── logger
├── conf
│   ├── __init__.py
│   ├── env.conf
├── utils.py
├── settings.py
├── main.py 
└── README.md
```

The `main.py` file will be responsible for running your application. The `settings.py` file will be used for including the settings (eg: database connections) for the application. The `utils.py` contains the necessary utilities to run the application.

## Creating you first app for your project

FAONS inherit the idea of creating apps from Django. We will be creating different apps to separate different modules in our application. We can create apps by using the command `faons startapp <app_name>` . Once done the app folder will be created inside the `src/core` folder.