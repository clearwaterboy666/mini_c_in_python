# mini_c_in_python
It is the mini C written in python, which has <600 lines of code. 
This project is for educational purpose. Clarity is the top priority here.

python3 compiler.py # this will generate loop.s
gcc -m32 loop.s -o loop # run it in linux please. not working in mac.
./loop
