mkdir /home/$USER/Documents/vjezba6   # izrada direktorija koristeci apsolutnu putanju
cd /home/$USER/Documents/vjezba6   # ulazak u direktorij
touch OS_script.md notes.txt && mkdir scripts  # izrada 2 datoteke i 1 direktorija
mv OS_script.md scripts/  # prebacivanje OS_script.md u scripts
mv notes.txt todo.txt # preimenovanje notes.txt u todo.txt
cd scripts
rm ../todo.txt  # ulazak u scripts i brisanje koristeći RELATIVNU putanju
