## WARNING

```
FOR STUDY AND DISCUSSION ONLY, PLEASE DO NOT ENGAGE IN ANY ILLEGAL ACTS.
ANY PROBLEMS ARISING FROM THIS WILL BE BORNE BY THE USER (YOU).
```

## Features
- Supports Version 1.0.0+ (At least for now.)
- Supports Win/Ubuntu(Tested) supported by typora

## Usage

1. `pip install -r requirements.txt`
2. `python typora.py --help`
3. read and use.
4. do something.
5. pack and replace app.asar.
6. enjoy it.


## Example

```shell
> python typora.py --help
usage: typora.py [-h] [-u] [-f] asarPath dirPath

[extract and decryption / pack and encryption] app.asar file from [Typora].

positional arguments:
  asarPath    app.asar file path/dir [input/ouput]
  dirPath     as tmp and out directory.

optional arguments:
  -h, --help  show this help message and exit
  -u          pack & encryption (default: extract & decryption)
  -f          enabled prettify/compress (default: disabled)

If you have any questions, please contact [ MasonShi@88.com ]

> python typora.py {installRoot}/Typora/resources/app.asar workstation/outfile/
⋯
# (patch code in workstation/outfile/dec_app)
> python typora.py -u workstation/outfile/dec_app workstation/outappasar
⋯
> cp {installRoot}/Typora/resources/app.asar {installRoot}/Typora/resources/app.asar.bak
> mv workstation/outappasar/app.asar {installRoot}/Typora/resources/app.asar
> node example/keygen.js
XXXXXX-XXXXXX-XXXXXX-XXXXXX
> typora
# (input info)
email: crack@example.com
serial: XXXXXX-XXXXXX-XXXXXX-XXXXXX
```

