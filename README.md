# Deploy an AWS KMS key

[![PyPI](https://img.shields.io/pypi/v/humilis-kms.svg?style=flat)](https://pypi.python.org/pypi/humilis-kms)

A [humilis][humilis] plug-in layer that deploys a KMS key.


[humilis]: https://github.com/humilis/humilis
[kms]: https://aws.amazon.com/kms/


## Installation

```
pip install humilis-kms
```

To install the development version:

```
pip install git+https://github.com/humilis/humilis-kms
```


## Development

Assuming you have [virtualenv][venv] installed:

[venv]: https://virtualenv.readthedocs.org/en/latest/

```
make develop
```

Configure humilis:

```
make configure
```


## Testing

You can test the deployment with:

```
make test
```

If the tests break, you can make sure you are not leaving any infrastructure
behind with:

```bash
make delete
```


## More information

See [humilis][humilis] documentation.

[humilis]: https://github.com/humilis/blob/master/README.md


## Contact

If you have questions, bug reports, suggestions, etc. please create an issue on the [GitHub project page][github].

[github]: http://github.com/humilis/humilis-kms


## License

See the original [Casecommons repository][casecommons] for license information.
