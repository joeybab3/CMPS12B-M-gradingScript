# How to use

```
curl https://raw.githubusercontent.com/kriszhao/CMPS12B-M-gradingScript/master/pa1/pa1.sh > pa1.sh
chmod +x pa1.sh
```

### Then, do

```
./pa1.sh
```

Currently, files in this branch works on local computer, I changed curl command to cp.

In local computer, change the script path to your local pa1 path in pa1.sh and pa1-check.sh

Then Run:
```
cp script/pa1.sh  (student's file path)/pa1.sh
chmod +x pa1.sh
pa1.sh
```

If you only want to test your unit test by ModelSubsetTest.c, run:
```
make -f Makefile1 ModelSubsetTest
ModelSubsetTest -v
```
