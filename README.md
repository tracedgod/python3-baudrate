# Fork of sickcodes' fork of baudrate

I ran across issues getting the script to run on Windows, attempting to fix + add possible features to script.

# Baudrate Python 3 - fork of baudrate

```bash
git clone https://github.com/sickcodes/python3-baudrate
cd python3-baudrate
pipenv run pip install -r requirements.txt
pipenv run sudo python baudrate.py -a

# or without pipenv
# pip install -r requirements.txt
# sudo python baudrate.py
```

Forked and cherry-picked @Loris1123 commit because he deleted his repo.

Added requirements.txt

See PR: https://github.com/devttys0/baudrate/pull/4#commits-pushed-0eb5f36


# Credits

Original author Craig Heffner @devttys0: https://github.com/devttys0/baudrate

Upgraded to Python3 by @Loris1123: https://github.com/Loris1123

Modernized by Sick.Codes @sickcodes : https://github.com/sickcodes

Windows Fix @tracedgod : https://github.com/tracedgod