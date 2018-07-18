# odoo_deps_wheels
Odoo dependences wheels repo for new buildout

## How to build a wheel

```
pip install pipenv
mkdir wheelhouse
pipenv shell
STATIC_DEPS=true pip wheel build --no-cache-dir my_dep
```

Then commit the new wheel to repo
