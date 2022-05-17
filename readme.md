This git repo contains 3 files;
1. no_code.ipynb: A workbook containing the data challenge, with no code, leaving you to complete
2. completed_code.ipynb: A workbook containing the entire data challenge including all code. To use as reference
3. data.csv: The dataset we will be working from

In order to make use of this repo;
1. Download the source code as a zip file to your local machine.
2. Then go to [Google colab](http://colab.research.google.com) and start a new notebook.
3. Upon opening the notebook, in the file section _on the left hand side of the screen_, press the upload button and upload the zipped directory, which should be called `hackathon_creating-main.zip`
4. Use the following code to extract the project:
```
from zipfile import ZipFile
file_name = 'hackathon_creating-main.zip'

with ZipFile(file_name, 'r') as zip:
  zip.extractall()
  print('Done')
```
