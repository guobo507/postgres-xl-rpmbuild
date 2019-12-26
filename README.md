## Build Postgres-XL RPM for EL 7.x

This project builds the Postgres-XL RPMs from v9.5r1.6 source file. 

I forked this project from `netman2k/postgres-xl-rpmbuild`, and I have modified and tested the new project on CentOS 7.6 64-bit, it works file.

### How to use?

    git clone https://github.com/guobo507/postgres-xl-rpmbuild.git
    cd postgres-xl-rpmbuild/
    ./install_req.sh
    ./buildxc

### How to get the results?

When you finished, you can check the result by using the following command:

    cd ./RPMS/x86_64/
    ls -lh 

Or for source rpm package:

    cd ./RPMS/
    ls -lh 

