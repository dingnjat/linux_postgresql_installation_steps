## PostgreSQL installation for beginner on linux (fedora)
1. Go to Dowload PostgreSQL site, choose correctly version to your OS, follow the steps on this page.
![Choose version](/image/choose.png)
2. After installing and starting the PostgreSQL services, open terminal, run: <addr>sudo su - postgres</addr>, enter sudo password.
3. If you has not added PATH yet, run <addr>export PATH="path_to_bin:$PATH"</addr>. E.g <addr>export PATH="/usr/pgsql-11/bin:$PATH"</addr>. Then run it.
4. Run <addr>psql</addr> to run psql interface. Now, we can use sql query with postgresql
### Create user
1. <addr>CREATE USER username;</addr>
2. <addr>ALTER USER username WITH ROLE1 ROLE2....;</addr>
### Connect to PostgreSQL