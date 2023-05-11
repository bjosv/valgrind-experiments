# valgrind experiments

## Build
apt-get install autotools-dev automake

git clone https://sourceware.org/git/valgrind.git
cd valgrind
./autogen.sh
./configure
make


## Logs

### Debug logs
Add: -d

### Verbose logs
Add: "-v" or "-v -v" or ..
