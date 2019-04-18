#Colab instances are temporary so you need to store files elsewhere.
#Be careful here as you won't get any warnings before overwriting files

#More info available here https://colab.research.google.com/notebooks/io.ipynb

#This lets you import files from grive. I keep files i need readily in a gdrive folder called colabmnt, e.g., credentials.py

from google.colab import drive
drive.mount('/content/gdrive')

# you may want to delay this for a moment as it can take a moment for the gdrive to mount
# FYI, The commands beginning with ! are standard *nix
!cp "/content/gdrive/My Drive/colabmnt/credentials.py" "credentials.py"

# verify your files were copied.
!ls

#use this to copy files back to gdrive
!cp "test.txt" "/content/gdrive/My Drive/colabmnt/test.txt" 
