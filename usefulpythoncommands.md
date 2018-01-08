# usefulpythoncommands
## In Python:
* End script at this point
```python
raise Systemexit
``` 
## In Pip:
* List all packages
```bash
pip freeze
```
* Update all packages
```bash
pip freeze --local | grep -v '^\-e' | cut -d = -f 1  | xargs -n1 pip install -U
```
