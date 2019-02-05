find ./ -type f -not -perm 644 -not -name ".ftpquota" -exec chmod 644 -c {} \;; find ./ -type d -not -perm 755 -not -group nobody -exec chmod 755 -c {} \;
