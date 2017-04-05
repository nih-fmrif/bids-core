# SciTran – Scientific Data Management


### Usage
```
./bin/run.sh [config file]
```
or
```
PYTHONPATH=. uwsgi --http :8443 --virtualenv ./runtime --master --wsgi-file bin/api.wsgi
```


### Maintenance

#### Upgrading Python Packages

List outdated packages
```
pip list --local --outdated
```

Then review and decide what upgrades to make, if any.<br>
Changes to `requirements.txt` should always be a pull request.
