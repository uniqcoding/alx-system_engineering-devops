Shell Redirections
echo '(Oo)'
cat /etc/passwd
cat /etc/passwd /etc/hosts
tail -n 10 /etc/passwd
head -n 10 /etc/passwd
head -n 3 iacta | tail -n 1
echo Best School >\*\'Best School\'\*$\?\*\*\*\*\*:)
ls -la > ls_cwd_content
tail -n 1 iacta >> iacta
find . -type f -name "*.js" -delete
find . -type d -not -name . | wc -l
ls -tl | head -n 10
sort | uniq -u
grep -i "root" /etc/passwd
grep -c -i "bin" /etc/passwd
grep -i "root" -A 3 /etc/passwd
grep -i -v "bin" /etc/passwd
grep -i "^[a-z]" /etc/ssh/sshd_config
tr "A" "Z" | tr "c" "e"
tr -d "cC"
rev
