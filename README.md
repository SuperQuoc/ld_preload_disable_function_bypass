# open_basedir & disable_functions bypass

* Work if function mail() and putenv() not disabled
* Modify LD_PRELOAD using putenv() and run payload .so using function mail()
