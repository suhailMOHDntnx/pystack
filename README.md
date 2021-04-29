[![PyPI](https://img.shields.io/pypi/v/pystack-debugger.svg)](https://pypi.org/project/pystack-debugger/)

# pystack

A debug tool to print python threads or greenlet stacks.

fork of [pystack](https://pypi.org/project/pystack-debugger/).

deviations from original:
- works without click
- no pip install required, suitable for simply copying the script onto the cluster and executing
- leverages `format_run_info` provided by latest version of gevents for dumping greenlet info


## Usage

Copy `pystack.py` onto your machine.

Then:

    $ sudo python pystack <pid>

