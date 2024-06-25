# Git_course
1-git clone https.....
الامر دا اذا بغيت بسحب ريبو من الريموت لازم اكون بمسار الفولدر الي بغيت بحط فيه فولدر الريبو

2-git init 
امر اذا بغيت بنشى ريبو عندي بعدها بسوي له بش على الريموت

3-git add [file name]/ *
عشان نضيف الملفات الي عدلت عليها او انشاتها في الوركنينق دريكتوري لل ستيجن ديريكتوري

4-git commit -m 'descrip what you do'
الامر دا ينقل الملف من السيجن ديريكتوري الى اللوكل ديريكتزري 

5- git push origin main 
بدا الامر اقدر ارفع الملفان من اللوكل للريموت 

6-git reset head .\tstrecet.txt ==  git restore --staged .\tstrecet.txt
اذا بغيت برجع الملف untracked

-SSH
7- ssh key من خلاله اقدر ارفع واوصل للريبو من غير مايطلب مني لوقن ولا حتى بريميشن 
/n
وعشان اقدر انشاء كي جديد ادخل على التيرمنل من المكان الي بغيت تشتغل فيه وتكتب الامر الي ينشا كي ويخزنه بحيث تقدر تستعمله في اي مكان 

ssh-keygen -t rsa -b 4096 -C "[Email repo]"
/n بعدها تدخل باسورد 
تحط الامر دا عشان تنسخ الكي الببلك الي منشا 
cat ~/.ssh/id_rsa.pub
بعدها تروح ع القيت هب وتحط الكي حقك 

تحط الامر دا عشان تتاكد انه تعرف ع الكي الي عندك وفادر يدخلك بدون اي مشاكل 
ssh -T git@github.com


الحين تكون قادر انك تسوي بوش على الريبو 
git remote add origin git@github.com:Khulood-2000/Test.git

git push origin main


# باختصار انه في عندي 4 ديريكتوريز 
1-Working directory والي هو اشتغل فيه في الvscode 
2-Staging directory [git add]
3-Local directory [git commit]
4-Remote directory in github website [git push]











# commands and qustions
git reset head .\tstrecet.txt ==  git restore --staged .\tstrecet.txt
الامرين يسوون نفس الشغل والي هو يخرجون الملف من الستيج اريا بعد ماسوينا امر الادد بس ايش الفرق بينهم علما بان الركوماندس لما نسوي قيت ستيت يكون لثانيه



