1-mkdir      // folder create karny k ley<br>
2-cd         // folder main enter hon k ley
cd ..      // folder main ak step peechy any k ley
touch      // file create karn k ley
nano       // file main text leakhn k ley
cat        // file ka content dekhny k ley
ls         //  list down k le
ls -a      // hidden files and folders k ley
echo "i am a pakistani">html.txt  //  html.txt file main text add karn k ley without replace the exit text
echo "bdhed nduwhsjw">>html..txt  //   html.txt main text add karna new line main
tree        // structure show karny k ley
find . -name "*.txt"    // .txt name ke sari file doodn k ley 
find . -type f -name "*.log"  // sari faile list down kr do .log wali
find . -type f   // sari file list down krn k ley
find . -type d   // d mtlb directrioes yni folders list down karny k ley
grep       // file main s text doodn k ley
grep "password" html.txt    //html.txt file main password word doodny k ley
grep -i      // remove case sesitivity
grep  -n     // numbering k sath show karwana
grep  -c     // count karn k ley
grep  -v     // jen lines main password word nai ha wo show kr do
chmod        // files aur folders ka mode change karny k ley mtlb kes ko permission deni ha aur kes ko nai owner,group,others
owner    // 4 points
group    //2 points
other    //1 point
chmod 750 "file name" //yhn owner ko read ,write,aur excute karny ke permission ha aur group ko read and write ke aur others ko koi permission nai de gai
chmod o+r "file name"  // others ko read karn ke permision dena
ls -l //check karny k ley
owner k ley o group k ley go aur others k le o use hota ha
chown   // owner change karny k ley
chown root filename
chgrp shamim filename//group change karny k ley
//folders ko tar aur zip banana
tar -cvf task.tar task
tar -xvf task.tar 
zip -r task.tar task
unzip -l task.tar
tar -czvf task.tar.gzp task
tar -xzvf task.tar.gzp
//hamary pass do tarh k user hot hain ak normal user aur dusra root
//normak user ko permission k ley sudo lekhna parta ha
//agr normal user h root user bnn jy to phir us sudo lekhny k zarurat  nai
sudo -i // root user bann k ley,whoami to wo root user baty ga
df -h  // disk storage ketni bari ha aur ketni khali ha,-h mean human readable
du -h myfolder  //  y folder ketni jaga ly raha ha
du -sh fildername // total size checkkarny k ley
cpuls // cpu k related information mko list dfown kr do
lsblk //list block devices(HDD SDD ect) ke hiss yhni particion dekhata ha


