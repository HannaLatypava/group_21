# group_21
pwd
mkdir cat
cd cat
mkdir -p{cat1,cat2,cat3}
cd cat1
touch frog_{1..3}.txt
touch bear_{1..3}.json
mkdir -p{dog1,dog2,dog3}
ls -la
mv bear_1.json bear_2.json dog1/
cp {frog_2.txt,frog_3.txt} dog1/
find /d/cat -name '*bear*'
tail -f /d/cat
awk 'FNR <=3' frog_1.txt
tail -2 frog_1.txt
less frog_1.txt
date