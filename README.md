# error-to-failed-to-push-to-some-refs
error

Try this git command

git push origin master --force
or short of force -f

git push origin master -f



.htaccess / redirect www-cpanel

RewriteCond %{HTTP_HOST} ^domain1anda.com
RewriteRule ^(.*) http://domain2anda.com/$1 [P]


//whatsapp!!!

 <head>
      <meta name="viewport" content="width=device-width, initial-scale=1">

 <!--Let browser know website is optimized for mobile-->
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
      <title>PT.Payung Anak Bangsa</title>
<meta name="description" content=" PT.Payung Anak Bangsa is a company engaged in IT Solution. As an experienced IT consultant, we can provide the right solution for all kinds of the problems in managing your IT system and enterprise architecture. We'll provide advice and include in the implementation of your system ,so that it can improve the performance of your business. We have skilled and experienced professionals in their fields.">
 
<!-- Google / Search Engine Tags -->
<meta itemprop="name" content="PT.Payung Anak Bangsa">
<meta itemprop="description" content="PT.Payung Anak Bangsa is a company engaged in IT Solution. As an experienced IT consultant, we can provide the right solution for all kinds of the problems in managing your IT system and enterprise architecture. We'll provide advice and include in the implementation of your system ,so that it can improve the performance of your business. We have skilled and experienced professionals in their fields.">
<meta itemprop="image" content="http://www.payunganakbangsa.com/img/pyng.jpg">
 
<!-- Facebook Meta Tags -->
<meta property="og:url" content="http://www.payunganakbangsa.com/">
<meta property="og:type" content="PT.Payung Anak Bangsa">
<meta property="og:title" content="PT.Payung Anak Bangsa">
<meta property="og:description" content=" PT.Payung Anak Bangsa is a company engaged in IT Solution. As an experienced IT consultant, we can provide the right solution for all kinds of the problems in managing your IT system and enterprise architecture. We'll provide advice and include in the implementation of your system ,so that it can improve the performance of your business. We have skilled and experienced professionals in their fields.">
<meta property="og:image" content="http://www.payunganakbangsa.com/img/pyng.jpg">
 
<!-- Twitter Meta Tags -->
<meta name="twitter:card" content="PT.Payung Anak Bangsa">
<meta name="twitter:title" content="PT.Payung Anak Bangsa">
<meta name="twitter:description" content="PT.Payung Anak Bangsa">
<meta name="twitter:image" content="http://www.payunganakbangsa.com/img/pyng.jpg">
      
 </head>
 
 
 
 
 ERROR
 
 ! [rejected] master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/example/example.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.>hint: See the 'Note about fast-forwards' in 'git push --help' for details.
 
 
 nah, mudah ni cara mengatasinya, cukup ikuti langkah berikut ini :

Buat dulu Repository kalian
Buka Git Bash kalian dan ketik perintah berikut   

$ git init

$ git add .

$ git commit -m "First commit"

$ git remote add origin {remote repository URL}

contoh git remote add origin https://github.com/example/example.git

Solusinya ada di sini nih,

$ git pull origin master --allow-unrelated-histories

Habis itu, baru deh kalian Push
$ git push origin master

melihat status update git,
$ git push origin master -f
 
 
