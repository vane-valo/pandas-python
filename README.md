# pandas-python
This Jupyter Notebook is about a data cleaning exercise using the Pandas library on Python.

## pandas library

pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool,
built on top of the Python programming language.

pandas is an open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.

Some of the functions used were:

### -> pandas.DataFrame.drop
DataFrame.drop(labels=None, *, axis=0, index=None, columns=None, level=None, inplace=False, errors='raise')

Drop specified labels from rows or columns.

Remove rows or columns by specifying label names and corresponding axis, or by specifying directly index or column names. When using a multi-index, labels on different levels can be removed by specifying the level. See the user guide for more information about the now unused levels.

### -> pandas.DataFrame.max
DataFrame.max(axis=0, skipna=True, numeric_only=False, **kwargs)

Return the maximum of the values over the requested axis.

If you want the index of the maximum, use idxmax. This is the equivalent of the numpy.ndarray method argmax.

### -> pandas.DataFrame.min
DataFrame.min(axis=0, skipna=True, numeric_only=False, **kwargs)

Return the minimum of the values over the requested axis.

If you want the index of the minimum, use idxmin. This is the equivalent of the numpy.ndarray method argmin.

### -> pandas.unique
pandas.unique(values)

Return unique values based on a hash table.

Uniques are returned in order of appearance. This does NOT sort.

Significantly faster than numpy.unique for long enough sequences. Includes NA values.

### -> pandas.get_dummies
pandas.get_dummies(data, prefix=None, prefix_sep='_', dummy_na=False, columns=None, sparse=False, drop_first=False, dtype=None)

Convert categorical variable into dummy/indicator variables.

Each variable is converted in as many 0/1 variables as there are different values. Columns in the output are each named after a value; if the input is a DataFrame, the name of the original variable is prepended to the value.

### -> pandas.DataFrame.loc
property DataFrame.loc

Access a group of rows and columns by label(s) or a boolean array.

.loc[] is primarily label based, but may also be used with a boolean array.

Source:
Pandas Official Documentation: 
https://pandas.pydata.org/docs/index.html
