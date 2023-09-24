# Chrome password extractor

Script to extract saved passwords in Chrome using pycryptodome and pypiwin32 libraries.  

Create and activate a new python environment with PowerShell:

```bash
python -m env chrome_password
chrome_password\Scripts\Activate.ps1
```

Now we need to install the required dependencies:

`pip3 install pycryptodome pypiwin32`

This scritp will save the content of Chrome database into a file called **data.txt**
