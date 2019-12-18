# Student experts

## Helpfull commands

installing requirements.txt in venv:

```virtualenv venv && source venv/bin/activate && pip install -r requirements.txt```

using venv:

```source venv/bin/activate```

adding installed requirements to requirements.txt:

```pip freeze > requirements.txt```

alternatively if you have the pkg-resources=0.0.0 bug use:

```pip freeze | grep -v "pkgresources" > requirements.txt


## Google cloud commands

deploying function:

```cloud functions deploy {function} --runtime python37 --trigger-http```


