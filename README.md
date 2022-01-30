# pe-accounting-python-api

Python package to use the PE Accounting API with Python.

PE Accounting is the Swedish bookkeeping system found at <https://www.accounting.pe/sv/var-tjanst>. PE's API docs are here: <https://api-doc.accounting.pe>.

```sh
pip install pe-accounting-python-api
```

```python
#!/usr/bin/env python3
from pe_accounting_python_api import PeRestClient

pe_rest_client  = PeRestClient(company_id="<company_id>", api_access_token="<api_access_token>")
print(pe_rest_client.company())
```

