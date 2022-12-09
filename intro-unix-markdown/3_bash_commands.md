## Bash Commands

#### `history` lists past commands
```bash
reshama 🐘  $ history
```
Result:  
```bash
  506  ls
  507  clear
  508  history
  509  home
  510  clear
  511  history
  512  jobs
  513  clear
  514  alias home
  515  alias c
  516  cleear
  517  clear
  518  history
reshama 🐘  $ 
```

#### `!` + command number:  recall command without extra typing
Type:  
```bash
$ !514
```
Result:  
```
reshama 🐘  $ !514
alias home
alias home='cd /Users/reshamashaikh'
reshama 🐘  $ 
```

---

#### To get what version of Python being used
```bash
reshama 🐘  $ python --version
Python 2.7.11 :: Anaconda 2.4.0 (x86_64)
reshama 🐘  $ 
```

#### To get what version of git is installed
```bash
reshama 🐘  $ git --version
git version 2.7.4 (Apple Git-66)
reshama 🐘  $ 
```

---

#### To get what version of Python library being used
```bash
reshama 🐘  $ pip freeze | grep 'numpy'
reshama 🐘  $ pip freeze | grep 'numpy'
numpy==1.10.1
reshama 🐘  $ 
```

---

#### List of all Python libraries installed
```bash
reshama 🐘  $ pip list
```
Result:  
```
statsmodels (0.6.1)
sympy (0.7.6.1)
tables (3.2.2)
terminado (0.6)
textblob (0.11.1)
toolz (0.7.4)
tornado (4.3)
traitlets (4.1.0)
tweepy (3.5.0)
twitter (1.17.1)
ujson (1.33)
unicodecsv (0.14.1)
Werkzeug (0.10.4)
wheel (0.29.0)
xlrd (0.9.4)
XlsxWriter (0.7.7)
xlwings (0.4.1)
xlwt (1.0.0)
```





#### References

[My Favorite bash Tips and Tricks by Prentice Bisbal](http://www.linuxjournal.com/article/7385?page=0,1)

