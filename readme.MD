- volumes folder will contain all volumes
- auth folder should contain `htpasswd` file with auth
    you can make this file by typing in shell: `htpasswd -Bbn testuser password > auth/htpasswd`
    or with Docker (will create this file in ./): docker run --rm --entrypoint htpasswd httpd:2 -Bbn username password >  htpasswd

! UI opened only for the local machine
