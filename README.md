# icy: Python 3 data wrangling glue code
> ### "saving time handling multiple different data sources"

<table>
<tr>
  <td>Latest Release</td>
  <td>
	<a href="https://pypi.python.org/pypi/icy/">
	<img src="https://img.shields.io/pypi/v/icy.svg" alt="latest release" />
    </a>
  </td>
</tr>
<tr>
  <td>Package Status</td>
  <td>
	<a href="https://pypi.python.org/pypi/icy/">
	<img src="https://img.shields.io/pypi/status/icy.svg" alt="status" />
    </a>
  </td>
</tr>
<tr>
  <td>License</td>
  <td>
  	<a href="https://github.com/rcs-analytics/icy/blob/master/LICENSE">
	<img src="https://img.shields.io/pypi/l/icy.svg" alt="license" />
    </a>
  </td>
</tr>
<tr>
  <td>PyPI</td>
  <td>
    <a href="https://pypi.python.org/pypi/icy/">
    <img src="https://img.shields.io/pypi/dm/icy.svg" alt="pypi downloads" />
    </a>
  </td>
</tr>
</table>


## Installation

  * Activate [Python 3.4 environment](https://docs.python.org/3/library/venv.html#creating-virtual-environments)
  * Run
```sh
pip install icy
```
  * Or download from [PyPI](https://pypi.python.org/pypi/icy) (release) or [github](https://github.com/rcs-analytics/icy) (dev) and run
```sh
python setup.py install
```


## Usage

```python
import icy
icy.preview(path)
data = icy.read(path)
```
  * `icy.preview(path)` displays an overview over the data icy was able to parse. This helps configuring all parsing options.
  * `icy.read(path)` returns a dictionary of [pandas.DataFrames](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.html).
  * `path` can be any folder or zip-, csv-, tsv-, txt-, json-, html-, (xml-,) xls-, xlsx-, sqlite-, hdf5-file.
  * icy wraps the [pandas parsers](http://pandas.pydata.org/pandas-docs/stable/api.html#input-output).  Parsing options can be specified in a YAML-file.
  * For more details see [the docs](https://pythonhosted.org/icy/) and especially **[the examples](https://pythonhosted.org/icy/examples.html)**!


## License

  * [MIT](https://github.com/rcs-analytics/icy/blob/master/LICENSE)


## Discussion and Development

  * [Issues](https://github.com/rcs-analytics/icy/issues) and [Pull Requests](https://github.com/rcs-analytics/icy/pulls) are welcome!
  * Find more contact details at https://www.rcs-analytics.com


© 2015 Jonathan Rahn, [RCS Analytics GmbH](https://www.rcs-analytics.com)