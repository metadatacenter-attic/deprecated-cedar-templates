
for i in example*.json; do jsvalid.py -s template_validator.json -i $i; done

This validator and associated examples works with:

http://json-schema-validator.herokuapp.com/
https://pypi.python.org/pypi/jsonschema

However, the following two validators are not happy unless the template element is placed before a template in the initial oneOf for some examples:

http://www.jsonschemavalidator.net
http://jsonschemalint.com/draft4/#
