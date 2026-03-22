mkdir vjezba4 && cd vjezba4   # izrada direktorija vjezba 4 i ulazak u njega
mkdir subfolder # izrada direktorija subfolder, unutar vjezba4
touch $HOSTNAME  # izrada datoteke HOSTNAME
mv $HOSTNAME $USER  # preimenovanje HOSTNAME u USER
mv $USER subfolder/  # premjestanje datoteke USER u direktorij subfolder
rm /home/$USER/vjezba4/subfolder/$USER   # brisanje koristevi apsolutnu putanju i ostane samo direktorij subfolder
