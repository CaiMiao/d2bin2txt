# d2bin2txt

## Description
Utility to convert from formatted excel binary to csv, which is used by the game Diablo II.

Originally released at [Baidu Tieba](http://tieba.baidu.com/p/3982989915).

## Usage

`-h`: Outputs following texts:

```
Usage: bin2txt.exe [args]

    -tc <specific tc offset>
	
    -template <template path>
	
    -bin <bin path>
	
    -output <output txt path>
	
    -all | -file <specific file prefix>
```

Without argument: run the program with default arguments as following:

`-tc 0 -template .\template -bin .\bin -output .\txt -all`


Template folder shall include a set of original *.txt and a set of converted *.txt of *.tbl files from /data/local/LNG/<Language>.

EnquettarrM is recommended for the convertion.

Txts of extended custom tbls probably not supported as document writer didn't tested it.

[使用说明 - 中文](使用说明.doc)

## License
This program uses [GPL-3.0](LICENSE).