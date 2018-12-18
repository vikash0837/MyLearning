# To check gpu utilisation:
`watch -n 1 nvidia-smi`

# Replacing content in unix
`:%s/foo/bar/g`
Find each occurrence of 'foo' (in all lines), and replace it with 'bar'.

For specific lines:

`:6,10s/foo/bar/g`
Change each 'foo' to 'bar' for all lines from line 6 to line 10 inclusive.

# to load xlsx file on pandasa and finding sheet names

`xl = pd.ExcelFile('foo.xls')`

`xl.sheet_names`  # see all sheet names

`xl.parse(sheet_name)`  # read a specific sheet to DataFrame
