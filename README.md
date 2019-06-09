# bash
bash scripting/linux skills

Readme provided for basic skills - i am furthering my knowledge in bash/linux in general and keeping my notes here. feel free to browse if they seem helpful. i try to label if possible.

here is a list of basic linux terminal cmd's to help start
CORE CMDS::

cd = change directory
ls = list current directories contents (i prefer ls -alhF) alhF are all each different operators telling it to output a different style, each can be used alone, like -a, or together. as -a -l -h -F would also work
pwd = print working directory (example /home/drew)


------------------------------------------------------
help or -h can always be used with these to get explanations as well as man , short for manuel pages, can be put at the beginning of any cmd and many pages of explanation can be brought up. example ;man ls; would bring up the man pages for ls

mkdir = make directory
rmdir = remove directory

touch = creates a blank file or directory

nano file = creates a file and bring you directly into nano text editor


cp = copy as well as scp = secure copy

lspci = lists all pci devices can be used with a | (this is a pipe used for seperating bits of code) with grep (popular search help cmd)
example :: $ lspci | grep -i AMD
above output would find all amd pci devices

lscpu = list cpu info basic

smartctl = manuel pages may be needed, large group of smart testing tools for hdd, example smartctl --al /dev/sda to see all smart data... tests can also be run


