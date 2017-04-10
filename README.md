# SciTran – Scientific Data Management

[![CircleCI](https://circleci.com/gh/nih-fmrif/bids-core/tree/dsst.svg?style=shield&circle-token=23b4f2363af393753b7ac991e3151e903236fbf5)](https://circleci.com/gh/nih-fmrif/bids-core/tree/dsst)

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
