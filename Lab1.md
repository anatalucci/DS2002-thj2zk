LAB 1
1. cd $HOME
2. mkdir development
3. cd development 
   touch README.md
4. echo "DS2002" > README.md
5. echo "Alessia Natalucci" >> README.md
6. for i in {101..200..4}; do touch file$i.txt; done
7. touch bash_history
8. history > bash_history
9. cd $HOME
   tar -czvf archive.tar.gz development
10. export FAVORITE_FLAVOR="chocolate" > ~/.bashrc
used codespaces 