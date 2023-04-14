# DESCRIPTION

- platform to discover and submit AI tools for students

## Name

AIForSchool.com

# MVP GOALS

- User can **see submited** AI tools
- User can **submit** new AI tools
- Have authentication
- Furfill the SEO standards

## Maybe Goals

- rating relevance on a scale of 1-5

# Deployment Instructions
### Setup environment and install packages

```
pip install virtualenv
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

### Populate the DB
```
python
from app import prepopulate
prepopulate()
```
