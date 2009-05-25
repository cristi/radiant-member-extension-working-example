This is a Radiant project which includes [Aissac's Member Extension][ame].

The steps needed to get this Radiant project up and running are listed below:

    git clone git://github.com/cristi/radiant-member-extension-working-example.git 

    cd radiant-member-extension-working-example/

    git submodule init

    git submodule update

    rake db:super_export

    script/server

The user/password for the admin section:

*  username: admin
*  password: radiant

The email/password for the only member I created

*  email: cristi@aissac.ro
*  password: passtest

[ame]: http://blog.aissac.ro/radiant/member-extension/