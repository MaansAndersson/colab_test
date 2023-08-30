# colab_test


Zip and download file.
```
try:
  from google.colab import files
except ImportError:
   pass
else:
  !zip -r /content/file.zip /content/SAVE_FOLDER
  files.download("/content/file.zip")
```
