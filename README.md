# Samco Brokerage Calculator

Basically wrote it for personal use, instead of checking there website after every trade. I decided to write a small python script to calculate.

### Usage
```bash
$ python3 calc.py -h
Usage: calc.py [-h] [-i [INTRADAY ...]] [-d [DELIVERY ...]] [-c [CASHPLUS ...]] [-o [OPTIONS...]]
   
    Samco Brokerage Calculator

    optional arguments:
    -h, --help            show this help message and exit
    -i [INTRADAY ...], --intraday [INTRADAY ...]
                          For equities intraday.
    -d [DELIVERY ...], --delivery [DELIVERY ...]
                          For equities delivery.
    -c [CASHPLUS ...], --cashplus [CASHPLUS ...]
                          For cashplus delivery.
    -o [OPTIONS ...], --options [OPTIONS ...]
                          For options intraday/delivery.
```

For further usage help, you can execute the program with desired argument.

### Misc. Tip
You can add this file to your `.bashrc` or `.zshrc` if you're ZSH user, to use it as a command line tool, instead of navigating to that terminal everytime.
```
alias calc="python3 [PATH_TO_CALC.PY]"
```