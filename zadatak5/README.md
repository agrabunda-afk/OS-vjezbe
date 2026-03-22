mkdir vjezba5 && cd vjezba5  # izrada direktorija vjezba5 i ulazak u njega
touch $RANDOM.num  # izrada datoteke $RANDOM i ekstenzijom .num
ls  # provjera da je datoteka stvorena
cp *.num backup.num  # kopija datoteke
cd ..  # povratak u roditeljski direktorij
mkdir backup  # izrada direktorija backup
mv vjezba5/backup.num backup/  # premjestanje datoteka u backup
