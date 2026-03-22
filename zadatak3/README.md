mkdir vjezba3 && cd vjezba3    # izrada direktorija vjezba3 i ulazak u njega
mkdir backup   # izrada direktorija backup
touch notes.txt todo.txt script.sh  # izrada 3 datoteke u direktoriju vjezba3
cp notes.txt todo.txt script.sh backup/  # kopiranje tih datoteka iz vjezba3 u backup
rm script.sh  # brisanje datoteke script.sh 
ls  # ispis datoteka koje su ostale u vjezba3
cd backup # ulaz u backup direktorij
mkdir $USER  # dodavanje novog direktorija u backupu 
mv notes.txt todo.txt script.sh $USER/  # premjestanje datoteka iz direktorija backup u USER
