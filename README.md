hadith-islamware
================

Hadith database from [Islam Ware](https://www.islamware.com/app/downloads).

Copyright (C) 2006-2014 Islam Ware.

The files are provided here and signed by [Hendy Irawan](http://www.hendyirawan.com/)
for preservation purposes.

The UTF-8 files are converted using:

```
iconv -f cp1256 -t utf8 -o hadith-maliks-muwatta.utf8.csv           hadith-maliks-muwatta.csv                            
iconv -f cp1256 -t utf8 -o hadith-musnad-ahmad-ibn-hanbal.utf8.csv  hadith-musnad-ahmad-ibn-hanbal.csv                            
iconv -f cp1256 -t utf8 -o hadith-sahih-bukhari.utf8.csv            hadith-sahih-bukhari.csv                            
iconv -f cp1256 -t utf8 -o hadith-sahih-muslim.utf8.csv             hadith-sahih-muslim.csv                            
iconv -f cp1256 -t utf8 -o hadith-sunan-abu-dawud.utf8.csv          hadith-sunan-abu-dawud.csv                            
iconv -f cp1256 -t utf8 -o hadith-sunan-al-darimi.utf8.csv          hadith-sunan-al-darimi.csv                            
iconv -f cp1256 -t utf8 -o hadith-sunan-al-nasai.utf8.csv           hadith-sunan-al-nasai.csv                            
iconv -f cp1256 -t utf8 -o hadith-sunan-al-tirmidhi.utf8.csv        hadith-sunan-al-tirmidhi.csv                            
iconv -f cp1256 -t utf8 -o hadith-sunan-ibn-maja.utf8.csv           hadith-sunan-ibn-maja.csv                            
```

The LF-line-ending files are signed with Hendy Irawan <ceefour666@gmail.com> [key 5A9AC703](https://keyserver.pgp.com/vkd/DownloadKey.event?keyid=0xFEDB960B5A9AC703) using:

```
for i in *.csv ; do gpg --detach-sign --armor $i ; done
```

`--textmode` not usable due to `gpg: can't handle text lines longer than 19995 characters`
