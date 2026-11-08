# <p align="center"> canonizeR 
<p align="center"> A Simple CLI Linux/Unix Utility, Rewritten In RS From C++ Originally 
<p align="center"> Originally Compiled With rustc 

### Setup 
Run `rustc -o canonizer canonize.rs`

Note (rustc): -O3 Optimizations ???? 

### Usage  
`./canonizer <Preferred (New) Command Name> <Execution Path,...>`

### Bootstrap With: 

`./canonizer canonizer ./canonizer`


**Use Sudo When Necessary 


### NOTE 

Generally Speaking, You Should Be Using An Absolute Path Instead Of A Relative One, So You Can Use The Tool Anywhere. As Such, The Following Example Outlines The Best Practice For All Usage: 

`./canonizer canonizer /dir/subdir/canonizer` 