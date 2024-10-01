# Tree-Hole

## Directory structure

A standard directory structure for Flask web should be like:
```text
/FlaskWebProject
    /MyApplication              # Project folder
        /__init__.py            # Initialize Flask application
        /app
            /__init__.py        # Initialize blueprint
            /views
                __init__.py     # Initialize views module
                index.py        # Homepage view
            /models
                __init__.py     # Initialize model module
                database.py     # Database models
            /static
                /css
                /js
                /images
                ...             # Static files
            /templates
                layout.html     # Base template
                index.html      # Homepage template
                ...             # Other templates
            /forms
                __init__.py     # Initialize forms module
                example.py      # Form definition 
        /config
            __init__.py
            default.py          # Default configuration
            development.py      # Development environment configuration
            production.py       # Production environment configuration
        /tests
            __init__.py
            test_example.py     # Test cases
        /instance
            config.py           # Project instance configuration
    /run.py                     # Startup script
    /requirements.txt           # Project dependencies
    /README.md                  # Project documentation
```