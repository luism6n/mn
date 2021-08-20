usage: mn [-h] [--root ROOT] [--editor EDITOR] [-l {debug,info,error}] COMMAND

Stupidly simple personal notes manager

positional arguments:
  COMMAND               open-root     open your note's root directory
                        list          print the path of all notes
                        print-root    print root directory for the notes
                        sync          commit and push (if network enabled) notes root directory
                        todo          grep all #todo tags in markdown files
                        done          grep all #done tags in markdown files
                        cronjob       print cronjob line to sync notes periodically
                        fix           rename file to match title or add title to match filename

optional arguments:
  -h, --help            show this help message and exit
  --root ROOT           root dir for your notes
  --editor EDITOR       editor to open notes
  -l {debug,info,error}, --log-level {debug,info,error}
