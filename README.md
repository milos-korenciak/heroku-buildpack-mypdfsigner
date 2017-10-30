# MyPDFSigner

This is heroku build pack. It installs MyPDFSigner commandline tool
(kryptokoder.com) with no extra dependency (heroku base env suffice).

This is just the wrapper script around the tool. The tool itself owns
Kryptocoder Luis (Kryptocoder.com).

The tool without licence creates some aditional pdf attributes in
signed file. If you are OK with that, you probably do not need the
licence. For exact info: https://kryptokoder.com/license.html .
It is easy to add the existing licence file to the project.

Usage on commandline:
$ mypdfsigner -i input.pdf -o output.pdf -p "password" -l "location" -r "reason" -v <visible> -c <certify> -q <timestamp> -t "title" -a "author" -s "subject" -k "keywords" -z mypdfsigner.conf

For a bit more info about, run the tool with -h:
$ mypdfsigner -h

For short, but exhaustive usage docs:
https://kryptokoder.com/manual.html#Configuration


For full configuation, read exhaustive docs:
https://kryptokoder.com/manual.html#Configuration


