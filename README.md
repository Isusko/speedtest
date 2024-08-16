With this example I can get a speed test of internet:

Fecha y Hora  16-08-2024 10:32:02
Dowload Speed in Mbps:  48.74
Upload Speed in Mbps:  48.22
Ping:  23.344

then I can save this information on word.

This example was made on Python 3
We need to install the next packages

```
1.- pip install speedtest-cli 

PS C:\Users\USER\Documents\GitHub\ExamplesPy\speedtest> pip install speedtest-cli 
Requirement already satisfied: speedtest-cli in c:\users\fspmvl5\appdata\local\programs\python\python312\lib\site-packages (2.1.3)
PS C:\Users\FSPMVL5\Documents\GitHub\ExamplesPy\speedtest> c:\Users\FSPMVL5\Documents\GitHub\ExamplesPy\speedtest\.venv\Scripts\python.exe -m pip install speedtest-cli
Collecting speedtest-cli
  Using cached speedtest_cli-2.1.3-py2.py3-none-any.whl.metadata (6.8 kB)
Using cached speedtest_cli-2.1.3-py2.py3-none-any.whl (23 kB)
Installing collected packages: speedtest-cli
Successfully installed speedtest-cli-2.1.3
```

```
2.- pip install python-docx

PS C:\Users\USER\Documents\GitHub\ExamplesPy\speedtest> pip install python-docx
Collecting python-docx
  Using cached python_docx-1.1.2-py3-none-any.whl.metadata (2.0 kB)
Collecting lxml>=3.1.0 (from python-docx)
  Using cached lxml-5.3.0-cp312-cp312-win_amd64.whl.metadata (3.9 kB)
Collecting typing-extensions>=4.9.0 (from python-docx)
  Using cached typing_extensions-4.12.2-py3-none-any.whl.metadata (3.0 kB)
Using cached python_docx-1.1.2-py3-none-any.whl (244 kB)
Using cached lxml-5.3.0-cp312-cp312-win_amd64.whl (3.8 MB)
Using cached typing_extensions-4.12.2-py3-none-any.whl (37 kB)
Installing collected packages: typing-extensions, lxml, python-docx
Successfully installed lxml-5.3.0 python-docx-1.1.2 typing-extensions-4.12.2

then run the example:
PS C:\Users\USER\Documents\GitHub\ExamplesPy\speedtest> python .\Speed_Test.py                                                                                
Fecha y Hora  16-08-2024 10:09:45
Dowload Speed in Mbps:  48.34
Upload Speed in Mbps:  48.94
Ping:  21.659

```