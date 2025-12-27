## Odoo json-2
    Odoo json-2 client using 'requests' as the underlying transport.
<br>

	version: 0.0.1
	author: Joan A. Pinol
	author_nickname: japinol
	author_gitHub: japinol7
	author_twitter: @japinol
<br>

	Dependencies: requests.
	Python requires: 3.13 or greater.
    Tested against Odoo 19.0 CE.
<br>


### More info

* Official Odoo documentation
  * [External JSON-2 API — Odoo 19.0 documentation](https://www.odoo.com/documentation/19.0/developer/reference/external_api.html)

<br>

### Implemented client
* odoo-json2
  * Simple json-2 client using 'requests' as the underlying transport.
  * odoo_client   -> Te odoo client with the API interface
  * simple_json2  -> The underlying json-2 client and connection.


### Small programs that can be useful as examples of usage

* Odoo integration examples in Python using this Odoo json-2 package
    * [odoo-json2-integration-examples](https://github.com/japinol7/odoo-json2-integration-examples)

<br>

### Install the last package tag released from this repo in your project
Add this to your requirements.txt file: <br>

    git+https://github.com/japinol7/odoo-json2.git@v0.0.1

<br>
Alternatively, if you use an uv toml file: <br>

    dependencies = [
        "odoo-json2",
    ]
    
    [tool.uv.sources]
    odoo-json2 = { git = "https://github.com/japinol7/odoo-json2.git", rev = "v0.0.1" }

<br>
.
