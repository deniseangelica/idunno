Log in:

emphaticgpvm01.fnal.gov via kerberized ssh.

Execute: 

source /emph/app/setup/setup_emphatic.sh

cd /emph/app/users/dhuerta

mkdir art_1


Clone:

Git repository for EMPHATICSOFT/emphaticsoft by downloading zip from the emphaticsoft-master branch

Copy into art_1:

scp -r emphaticsoft-master dhuerta@emphaticgpvm01.fnal.gov: /emph/app/users/dhuerta/art_1

Execute:

cd /emph/app/users/dhuerta/art_1/build
source /emph/app/users/dhuerta/art_1/emphaticsoft-master/ups/setup_for_development -p

Compile: 
buildtool -j4
