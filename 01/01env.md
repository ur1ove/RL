###
~~~
(keras) E:\Data\강화학습>conda install pandas-datareader
Solving environment: done

## Package Plan ##

  environment location: E:\Program\Anaconda3\envs\keras

  added / updated specs:
    - pandas-datareader


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    wrapt-1.10.11              |   py36hfa6e2cd_2          44 KB
    libxml2-2.9.8              |       hadb2253_1         3.2 MB
    pyopenssl-18.0.0           |           py36_0          83 KB
    idna-2.7                   |           py36_0         132 KB
    pandas-0.23.4              |   py36h830ac7b_0         8.6 MB
    pycparser-2.19             |           py36_0         174 KB
    pytz-2018.7                |           py36_0         260 KB
    chardet-3.0.4              |           py36_1         210 KB
    cryptography-2.4.1         |   py36h7a1dbc1_0         540 KB
    lxml-4.2.5                 |   py36hef2cd61_0         1.2 MB
    pandas-datareader-0.7.0    |           py36_0         142 KB
    win_inet_pton-1.0.1        |           py36_1           6 KB
    requests-2.20.1            |           py36_0          85 KB
    python-dateutil-2.7.5      |           py36_0         276 KB
    cffi-1.11.5                |   py36h74b6da3_1         213 KB
    pysocks-1.6.8              |           py36_0          23 KB
    urllib3-1.23               |           py36_0         152 KB
    ------------------------------------------------------------
                                           Total:        15.3 MB

The following NEW packages will be INSTALLED:

    asn1crypto:        0.24.0-py36_0
    cffi:              1.11.5-py36h74b6da3_1
    chardet:           3.0.4-py36_1
    cryptography:      2.4.1-py36h7a1dbc1_0
    idna:              2.7-py36_0
    libiconv:          1.15-h1df5818_7
    libxml2:           2.9.8-hadb2253_1
    libxslt:           1.1.32-hf6f1972_0
    lxml:              4.2.5-py36hef2cd61_0
    pandas:            0.23.4-py36h830ac7b_0
    pandas-datareader: 0.7.0-py36_0
    pycparser:         2.19-py36_0
    pyopenssl:         18.0.0-py36_0
    pysocks:           1.6.8-py36_0
    python-dateutil:   2.7.5-py36_0
    pytz:              2018.7-py36_0
    requests:          2.20.1-py36_0
    urllib3:           1.23-py36_0
    win_inet_pton:     1.0.1-py36_1
    wrapt:             1.10.11-py36hfa6e2cd_2

Proceed ([y]/n)? y


Downloading and Extracting Packages
wrapt-1.10.11        | 44 KB     | ############################################################################ | 100%
libxml2-2.9.8        | 3.2 MB    | ############################################################################ | 100%
pyopenssl-18.0.0     | 83 KB     | ############################################################################ | 100%
idna-2.7             | 132 KB    | ############################################################################ | 100%
pandas-0.23.4        | 8.6 MB    | ############################################################################ | 100%
pycparser-2.19       | 174 KB    | ############################################################################ | 100%
pytz-2018.7          | 260 KB    | ############################################################################ | 100%
chardet-3.0.4        | 210 KB    | ############################################################################ | 100%
cryptography-2.4.1   | 540 KB    | ############################################################################ | 100%
lxml-4.2.5           | 1.2 MB    | ############################################################################ | 100%
pandas-datareader-0. | 142 KB    | ############################################################################ | 100%
win_inet_pton-1.0.1  | 6 KB      | ############################################################################ | 100%
requests-2.20.1      | 85 KB     | ############################################################################ | 100%
python-dateutil-2.7. | 276 KB    | ############################################################################ | 100%
cffi-1.11.5          | 213 KB    | ############################################################################ | 100%
pysocks-1.6.8        | 23 KB     | ############################################################################ | 100%
urllib3-1.23         | 152 KB    | ############################################################################ | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: done

(keras) E:\Data\강화학습>
~~~
~~~
(keras) E:\Data\강화학습>pip install fix_yahoo_finance --upgrade --no-cache-dir
Collecting fix_yahoo_finance
  Downloading https://files.pythonhosted.org/packages/0a/96/d44330e427f5368cb8abd25997b72956a31b52073d285c4d5cd56e5fdc17/fix-yahoo-finance-0.0.22.tar.gz
Requirement already satisfied, skipping upgrade: pandas in e:\program\anaconda3\envs\keras\lib\site-packages (from fix_yahoo_finance) (0.23.4)
Requirement already satisfied, skipping upgrade: numpy in e:\program\anaconda3\envs\keras\lib\site-packages (from fix_yahoo_finance) (1.15.4)
Requirement already satisfied, skipping upgrade: requests in e:\program\anaconda3\envs\keras\lib\site-packages (from fix_yahoo_finance) (2.20.1)
Collecting multitasking (from fix_yahoo_finance)
  Downloading https://files.pythonhosted.org/packages/ac/1a/0750416c5e3683d170757e423f097fdf78ceb9ccdc65658b24341664e53e/multitasking-0.0.7.tar.gz
Requirement already satisfied, skipping upgrade: python-dateutil>=2.5.0 in e:\program\anaconda3\envs\keras\lib\site-packages (from pandas->fix_yahoo_finance) (2.7.5)
Requirement already satisfied, skipping upgrade: pytz>=2011k in e:\program\anaconda3\envs\keras\lib\site-packages (from pandas->fix_yahoo_finance) (2018.7)
Requirement already satisfied, skipping upgrade: idna<2.8,>=2.5 in e:\program\anaconda3\envs\keras\lib\site-packages (from requests->fix_yahoo_finance) (2.7)
Requirement already satisfied, skipping upgrade: certifi>=2017.4.17 in e:\program\anaconda3\envs\keras\lib\site-packages (from requests->fix_yahoo_finance) (2018.10.15)
Requirement already satisfied, skipping upgrade: urllib3<1.25,>=1.21.1 in e:\program\anaconda3\envs\keras\lib\site-packages (from requests->fix_yahoo_finance) (1.23)
Requirement already satisfied, skipping upgrade: chardet<3.1.0,>=3.0.2 in e:\program\anaconda3\envs\keras\lib\site-packages (from requests->fix_yahoo_finance) (3.0.4)
Requirement already satisfied, skipping upgrade: six>=1.5 in e:\program\anaconda3\envs\keras\lib\site-packages (from python-dateutil>=2.5.0->pandas->fix_yahoo_finance) (1.11.0)
Installing collected packages: multitasking, fix-yahoo-finance
  Running setup.py install for multitasking ... done
  Running setup.py install for fix-yahoo-finance ... done
Successfully installed fix-yahoo-finance-0.0.22 multitasking-0.0.7

(keras) E:\Data\강화학습>
~~~
