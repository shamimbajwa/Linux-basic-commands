1-mkdir      // folder create karny k ley<br>
2-cd         // folder main enter hon k ley<br>
3-cd ..      // folder main ak step peechy any k ley<br>
4-touch      // file create karn k ley<br>
5-nano       // file main text leakhn k ley<br>
6-cat        // file ka content dekhny k ley<br>
7-ls         //  list down k le<br>
8-ls -a      // hidden files and folders k ley<br>
9-echo "i am a pakistani">html.txt  //  html.txt file main text add karn k ley without replace the exit text<br>
10-echo "bdhed nduwhsjw">>html..txt  //   html.txt main text add karna new line main<br>
11-tree        // structure show karny k ley<br>
12-find . -name "*.txt"    // .txt name ke sari file doodn k ley <br>
13-find . -type f -name "*.log"  // sari faile list down kr do .log wali<br>
14-find . -type f   // sari file list down krn k ley<br>
15-find . -type d   // d mtlb directrioes yni folders list down karny k ley<br>
16-grep       // file main s text doodn k ley<br>
17-grep "password" html.txt    //html.txt file main password word doodny k ley<br>
18-grep -i      // remove case sesitivity<br>
19-grep  -n     // numbering k sath show karwana<br>
20-grep  -c     // count karn k ley<br>
21-grep  -v     // jen lines main password word nai ha wo show kr do<br>
22-chmod        // files aur folders ka mode change karny k ley mtlb kes ko permission deni ha aur kes ko nai owner,group,others<br>
23-owner    // 4 points<br>
24-group    //2 points<br>
25-other    //1 point
26-chmod 750 "file name" //yhn owner ko read ,write,aur excute karny ke permission ha aur group ko read and write ke aur others ko koi permission nai de gai<br>
27-chmod o+r "file name"  // others ko read karn ke permision dena<br>
28-ls -l //check karny k ley<br>
29-owner k ley o group k ley go aur others k le o use hota ha<br>
30-chown   // owner change karny k ley<br>
31-chown root filename<br>
32-chgrp shamim filename//group change karny k ley<br>
33-//folders ko tar aur zip banana<br>
34-tar -cvf task.tar task<br>
35-tar -xvf task.tar <br>
36-zip -r task.tar task<br>
37-unzip -l task.tar<br>
38-tar -czvf task.tar.gzp task<br>
39-tar -xzvf task.tar.gzp<br>
40-//hamary pass do tarh k user hot hain ak normal user aur dusra root<br>
41-//normak user ko permission k ley sudo lekhna parta ha<br>
42-//agr normal user h root user bnn jy to phir us sudo lekhny k zarurat  nai<br>
43-sudo -i // root user bann k ley,whoami to wo root user baty ga<br>
44-df -h  // disk storage ketni bari ha aur ketni khali ha,-h mean human readable<br>
46-du -h myfolder  //  y folder ketni jaga ly raha ha<br>
47-du -sh fildername // total size checkkarny k ley<br>
48-cpuls // cpu k related information mko list dfown kr do<br>
49-lsblk //list block devices(HDD SDD ect) ke hiss yhni particion dekhata ha<br>


