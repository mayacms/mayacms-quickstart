## Django — MayaCMS

```sh
find addons/ -name "*.egg-info" -exec rm -rf {} \;
find addons/ -name "__pycache__" -exec rm -rf {} \;

pip install -e django-mayacms/ --config-settings editable_mode=strict
pip install -e django-mayacms/ --config-settings editable_mode=strict --no-build-isolation
```
