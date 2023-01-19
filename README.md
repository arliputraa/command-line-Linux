# Command Linux Basic


command | description |
--- | --- |
head | open file from top |
head -2 | open file from 2 top |
vi | open and changes file contents (teks editor) |
i | for edit in editor vi |
Esc | exit in editor vi  |
:wq | for save and exit in vi |
:q | for exit not save in vi |
cd | open directory |
cd .. | back to the previous directory |
cd ~ | return to directory home |
wc -l | for see number of row |
rm | delete file |
rm -rf | delete directory |
du -kh | see storage in directory |
du -sh | see size in directory |
df -kh | see all storage path file | 
nano | open and changes file contents (teks editor) |
sudo dpkg-reconfigure tzdata | Set the time according to the region |
mv file.csv newdirectory/ | move file to directory
mv oldfile.csv newfile.csv | change file name



copy files between servers |
 --- |
scp * arli@192.168.18.105:/home/tg-bmri
sudo scp *.csv arli@192.168.18.105:/home/tg-bmri
scp -r sample_data/ arli@192.168.18.118:/home/arli/neo4j-enterprise-4.4.9/import
sudo scp apoc-4.4.0.8-all.jar neo4j-bloom-2.4.0.zip arli@192.168.18.158:/home/arli/neo4j-enterprise-4.4.11/plugins







