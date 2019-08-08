# cli-tools
Gadgets for everyday work


### `readexcel`

```
Usage:
	readexcel <Excelfile> [sheetNum=1] (trim_ws=T) (col_names=F)
	readexcel <Excelfile> [sheetNum=1] (trim_ws=T) (col_names=F) | less
	readexcel <Excelfile> [sheetNum=1] (trim_ws=T) (col_names=F) > out.txt
	
```

### `writexlsx`

```
Usage:
	writexlsx  <infile> <outfile> [sheetName=Sheet1] [col.names=F]
	writexlsx  -  <outfile> [sheetName] [col.names]  <  <infile>
	cat <infile> | writexlsx  -  <outfile> [sheetName] [col.names]
	
```

