mkdir vjezba2 && cd vjezba2    # izrada direktorija vjezba2 i ulazak u njega
touch file.txt  # izrada datoteke unutar direktorija vjezba2
cp file.txt file_copy.txt   # kopiranje datoteke file.txt
ls   # ispis svih datoteke unutar direktorija vjezba2 (file.txt i file_copy.txt)
rm file.txt  # brisanje datoteke file.txt
cd ~  # povratak u pocetni radni direktorij
rmdir vjezba2  # pokusaj brisanja direktorija vjezba2 ali neuspjesno jer nam daje da direktorij nije prazan , odnosno nakon brisanja file.txt ostao je file_copy.txt
