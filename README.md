# Reveal JS Demo


## Requirements and Installation

### Requirements

- Python 3
- virtualenv

### Installation Instructions on Mac and Linux using `virtualenv`

- Install this repo
- Navigate to the project directory with `cd`
- run this code in the project directory:
```

touch .env
echo "venv" >> .gitignore
echo '.env' >> .gitignore
virtualenv venv
. venv/bin/activate

```

- Once the virtualenv is activated, run this:
```
pip install -r requirements.txt
```
- Edit the `.env` file and add `KEY=VALUE` for any items you wish to import (NOTE this will NOT be stored in Github. NEVER check this in to a repo!)


### ...later on...

When you go back to your code, do these things:
- activate the environment with `. venv/bin/activate`
- (To exit your virtualenv, type `deactivate`)

## Contributing

- be sure to run `pip freeze > requirements.txt` if any new libraries are installed, and commit the updated file to github
