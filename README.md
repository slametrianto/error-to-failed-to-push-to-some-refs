# error-to-failed-to-push-to-some-refs
error

Try this git command

git push origin master --force
or short of force -f

git push origin master -f



.htaccess / redirect www-cpanel

RewriteCond %{HTTP_HOST} ^domain1anda.com
RewriteRule ^(.*) http://domain2anda.com/$1 [P]
