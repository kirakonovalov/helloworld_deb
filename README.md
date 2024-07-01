To build binary deb-package:
1) git clone https://github.com/kirakonovalov/helloworld_deb
2) cd helloworld_deb/
3) rm -rf .git/
4) dpkg-source -x helloworld_1.0.0-1.2.dsc
5) cd helloworld-1.0.0/
6) debuild -us -uc
Done
