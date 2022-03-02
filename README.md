# python-word-count-beam

### Instructions to run the Python word-Count:

0. Navigate to your python-word-count-beam directory and open with Powershell (as Admin)

1. Make sure you have python installed on your system.

> ```python --version```

2. Make sure you have pip installed on your system.

> ```pip --version```

3. Now, Upgrade your pip to latest version

> ```python -m pip install --upgrade pip```

4. Now, create an virtual environment in your directory

> ```python -m venv C:\path\to\directory```

5. Activate your virtual environment.

> ```C:\path\to\directory\Scripts\activate.ps1```

6. Download and Install Apache BEAM

> ```python -m pip install apache-beam```

7. Now, open your directory with VS Code and create 'wordcount.py' file. Copy the Code for 'wordcount.py' from this [link](https://github.com/apache/beam/blob/master/sdks/python/apache_beam/examples/wordcount.py). Paste it in your 'wordcount.py' file.

8. Create a empty text file and copy the contents from this [link](https://00f74ba44b963764a31d794cfbb9a16a8904a8d4a9-apidata.googleusercontent.com/download/storage/v1/b/apache-beam-samples/o/shakespeare%2Fsonnets.txt?jk=AFshE3UR-5dRvKFmq7toNMefNLl9aaKaOZ3bwuzGskJB6MLNBOcWO9eE4wSQL1mcmUrXTt7N2XqgPFgiJPJKwXAB584AQsanNLk5plxmhohU7Oro4AlUCeV5RvvEG1-dSmnvRuoLaLC1noKFygH0RiI_ZSNZdiSGaoZPOSLTvgDbSA6p15pAgRm4mXZFoXySSqDC7QSqYIdUEkqbOMlMLhNTejjWSszS_aMIbzlotAfS7f9MG0wTj8EmJdzITx3y8CKejID_u4T-6FgXWZNcz41ggCrWrudkYlnV5tf_tuz1fiWygYIPz3X7RHgvTYajzFNy_6P2LBGB5anPkBoMZy6XGeG7yboZ0ogCAkSlfqyvLRAvOjM598g4xi4R-LDxc5XMsO-CHkNQwBPjyiI4vVKCT9PrJj2Y0IjbqarKJGy4TjboRxRKw-9E7kXUj6c609PSMtrnPrM5ASDJBYcdBfUgGfgLI9f1esDTdp-TyDo2RPt7wfx86bYkLlqwqiEEeh4LKOeQ-87c6qowMXeltZzA2lKJvROcgK8_8IpGYfS44IxFfRh1loFZZAK5bbOA7JJYtGMyEou0jPPIZzQs-sIBgYVSsfvsTv-wHvuJ1pwGE5lDk7NSf69m0HoQYmKFOQQUpaZYtak_lXR2zAa3fmt8ANLnUSFMgT_27mjkLzd6uJMB-_DE1leP-glg3GUkiIXIY5J1bGHTNiq2XjqBUR9Satr1fgMfmVw2Zlu2tLZjFGBrD-FcK75qMJ4xGqOeXuUOO8QudDQSMw3q6HcKWRUCwhajOIrweZkbet8bn2yrsspixoOY71wqlzrDRuo64QkvXFOyahkoNkWG5sNrtgmrfUH8uZ2UkdrYzZGaBMK_cxOrFvtcf-5w5roCNkM01eya0M1t_P_kNI_QmuhXjaXecjq2pm0l9rVMb-ICZ18CoIj5h8JC19Qlw-YNxla_OrpfKgrz3UimYLgVV7ncCg-nj3Ont6I&isca=1). Paste it in your text file.

9. Now, execute the pipeline in Powershell. Replace ```/path/to/inputfile```  with your input file name. Replace ```/path/to/write/counts``` with your desired output file name.

> ```python -m apache_beam.examples.wordcount --input /path/to/inputfile --output /path/to/write/counts```

10. You can find the output file in your directory. Open with VS Code to view thre counts output file.


