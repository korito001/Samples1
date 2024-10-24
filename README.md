# Samples1
サンプル集

はじめてgithubを使うのでお試しです。

# Files

* pi3.f
* wallclock.c

# Usage

oneAPIを使ってコンパイル

---
mpiifx -O3 -xHost pi3.f -o pi3.exe
---

wallclock.cはサブルーチンなので、オブジェクトを作ります。

---
icx -o -O3 wallclock.c
---

# Author

* Kohtaro Orito
* HPC Solutions inc
* korito@hpc-sol.co.jp



