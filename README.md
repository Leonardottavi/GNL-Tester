# Get_Next_Line Tester (2023)
Questo tester serve a voi plebei per non bestemmiare nel caso vogliate pushare get_next_line, siate inteligenti lodate il sole.
Clonate questa repository nella vostra bellissima ma poco funzionale cartella, di seguito i comandi da inserire nel vostro sporco terminale.

Si consiglia questa canzone in sottofondo durante il test. https://www.youtube.com/watch?v=QJJYpsA5tv8

# Commands
make m = launch mandatory tests
make b = launch bonus tests
make a = launch mandatory tests + bonus tests + happy ending

make dockerm = launch mandatory tests in linux container
make dockerb = launch bonus tests in linux container
make dockera = launch mandatory tests + bonus tests in linux container

Potete cambiare il timeout value in Makefile
![alt text](https://i.imgur.com/jUimpaC.png)


# Setup docker in goinfre for 42 mac
```
rm -rf ~/Library/Containers/com.docker.docker
rm -rf ~/.docker
rm -rf /goinfre/${USER}/docker /goinfre/${USER}/agent
mkdir -p /goinfre/${USER}/docker /goinfre/${USER}/agent
ln -s /goinfre/${USER}/agent ~/Library/Containers/com.docker.docker
ln -s /goinfre/${USER}/docker ~/.docker
```

MOK / MKO = avete sbagliato la memoria del malloc (anche quella del vostro membro).

# Report bugs / Improvement
fixateli per cazzi vostri.
