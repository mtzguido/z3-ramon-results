# .

* SAT 70
* UNSAT 0
* TIMEOUT 0
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_SNIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_SNIA.tar.zst-do
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_SNIA.tar.zst?download=1
Z3 commit message: Fix instance of "flexible array member". (#9883)

This is another PR towards the goal of getting a clean build with clang,
using the compiler options used in building clang-tidy.

In https://github.com/Z3Prover/z3/pull/9800, we changed the build flags
to eliminate a warning for zero-length arrays. In that PR, I missed this
one: there was one instance of m_arr[] instead of m_arr[0]. In the
clang-tidy build, that gives warnings like:
```
/Users/daviddetlefs/llvm-project/build_dbg/_deps/z3-src/src/model/func_interp.h:43:12: warning: flexible array members are a C99 feature [-Wc99-extensions]
```

The PR fixes this, making it a zero-length array, the idiom used in all
the other similar cases. I also added the compiler flag that produced
this warning, so we can notice such changes in the future.

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_SNIA/20200224-Wu-PyExZ3/dddb9cc1f86d5738fd85ffa1b430c4e9df9771c0fffa945b9b414772.smt2 |    0.013s | 20.548MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20200224-Wu-PyExZ3/bdcb3877984a55b540face066045c4642cba1bc553af78576a41a76e.smt2 |    0.014s | 20.608MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1595.corecstrs.readable.smt2 |    0.014s | 19.7MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1598.corecstrs.readable.smt2 |    0.014s | 20.048MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20200224-Wu-PyExZ3/f72b09bc9444f702ad7cdf3a9075754e71d673f3d134d9f485f6608a.smt2 |    0.015s | 20.376MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/808.corecstrs.readable.smt2 |    0.015s | 19.808MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/2008.corecstrs.readable.smt2 |    0.015s | 19.516MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1594.corecstrs.readable.smt2 |    0.015s | 19.796MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1627.corecstrs.readable.smt2 |    0.015s | 19.8MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1568.corecstrs.readable.smt2 |    0.015s | 19.612MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1634.corecstrs.readable.smt2 |    0.015s | 19.608MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/843.corecstrs.readable.smt2 |    0.016s | 20.08MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1911.corecstrs.readable.smt2 |    0.016s | 19.652MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20200224-Wu-PyExZ3/e007cfdcf4dd61007107222cbedbb46ad161a945ab5ee0a68d3f585a.smt2 |    0.017s | 20.072MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1910.corecstrs.readable.smt2 |    0.017s | 19.616MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1553.corecstrs.readable.smt2 |    0.018s | 19.66MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1597.corecstrs.readable.smt2 |    0.019s | 19.596MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1590.corecstrs.readable.smt2 |    0.020s | 19.58MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/2010.corecstrs.readable.smt2 |    0.021s | 19.628MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/821.corecstrs.readable.smt2 |    0.022s | 19.68MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1997.corecstrs.readable.smt2 |    0.022s | 19.568MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1575.corecstrs.readable.smt2 |    0.022s | 19.64MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/823.corecstrs.readable.smt2 |    0.023s | 19.868MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/845.corecstrs.readable.smt2 |    0.023s | 19.656MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/851.corecstrs.readable.smt2 |    0.023s | 19.808MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1884.corecstrs.readable.smt2 |    0.023s | 19.672MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1552.corecstrs.readable.smt2 |    0.023s | 19.796MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1551.corecstrs.readable.smt2 |    0.023s | 19.74MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1908.corecstrs.readable.smt2 |    0.024s | 19.58MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1566.corecstrs.readable.smt2 |    0.024s | 19.8MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1572.corecstrs.readable.smt2 |    0.024s | 19.568MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/820.corecstrs.readable.smt2 |    0.025s | 19.792MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/811.corecstrs.readable.smt2 |    0.025s | 19.712MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/2007.corecstrs.readable.smt2 |    0.025s | 19.596MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/840.corecstrs.readable.smt2 |    0.026s | 19.668MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1635.corecstrs.readable.smt2 |    0.026s | 19.896MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1574.corecstrs.readable.smt2 |    0.026s | 19.812MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1886.corecstrs.readable.smt2 |    0.026s | 19.596MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1628.corecstrs.readable.smt2 |    0.027s | 19.788MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/825.corecstrs.readable.smt2 |    0.029s | 19.832MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/827.corecstrs.readable.smt2 |    0.029s | 19.904MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/849.corecstrs.readable.smt2 |    0.029s | 19.82MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/838.corecstrs.readable.smt2 |    0.029s | 19.748MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1555.corecstrs.readable.smt2 |    0.029s | 19.708MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1909.corecstrs.readable.smt2 |    0.029s | 19.788MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1907.corecstrs.readable.smt2 |    0.029s | 19.652MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1567.corecstrs.readable.smt2 |    0.029s | 19.636MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20200224-Wu-PyExZ3/5735c9082c3f9cd487c6376032029bb499ba1f87113dc9ca03adc6bc.smt2 |    0.030s | 20.576MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/826.corecstrs.readable.smt2 |    0.030s | 19.776MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/839.corecstrs.readable.smt2 |    0.030s | 19.796MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1557.corecstrs.readable.smt2 |    0.030s | 19.788MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1550.corecstrs.readable.smt2 |    0.030s | 19.712MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/812.corecstrs.readable.smt2 |    0.032s | 19.944MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/822.corecstrs.readable.smt2 |    0.032s | 19.792MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1626.corecstrs.readable.smt2 |    0.033s | 19.62MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1636.corecstrs.readable.smt2 |    0.034s | 19.8MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1556.corecstrs.readable.smt2 |    0.034s | 19.8MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/2009.corecstrs.readable.smt2 |    0.034s | 19.564MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1576.corecstrs.readable.smt2 |    0.035s | 19.704MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1637.corecstrs.readable.smt2 |    0.035s | 19.652MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1633.corecstrs.readable.smt2 |    0.035s | 19.648MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1596.corecstrs.readable.smt2 |    0.035s | 19.656MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/846.corecstrs.readable.smt2 |    0.036s | 19.796MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1589.corecstrs.readable.smt2 |    0.036s | 19.572MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/809.corecstrs.readable.smt2 |    0.037s | 19.888MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1885.corecstrs.readable.smt2 |    0.037s | 19.608MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1588.corecstrs.readable.smt2 |    0.037s | 19.772MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1573.corecstrs.readable.smt2 |    0.037s | 19.688MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/small/1554.corecstrs.readable.smt2 |    0.037s | 19.64MiB| sat | 0 |  |  |
|non-incremental/QF_SNIA/20180523-Reynolds/kaluza/sat/big/824.corecstrs.readable.smt2 |    0.038s | 19.692MiB| sat | 0 |  |  |
