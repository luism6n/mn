usage: mn [-h] [--root ROOT] [--use-internet] COMMAND

Stupidly simple personal notes manager

positional arguments:
  COMMAND         fix           try to fix problems with the notes
                  lint          print problems with the notes
                  open-root     open your note's root directory
                  list          print the path of all notes
                  print-root    print root directory for the notes
                  today         open today's note
                  tomorrow      open tomorrow's note
                  yesterday     open yesterday's note

optional arguments:
  -h, --help      show this help message and exit
  --root ROOT     root dir for your notes
  --use-internet  use the internet when linting references
