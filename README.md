# Bigbangtheory


pentesting

we are going do some reverse engineering techniques. in here we use gdb debugger to see in side the programm 

First we are going to use gdb with sheldon1 file

![2020-03-09_08-08-1](https://user-images.githubusercontent.com/34812175/76230707-1ce39400-624a-11ea-9b97-03608a00bcdb.png)


Use gdb's info functions command to get all available functions in sheldon1, and identify the "main" function (can use start as well).


![2020-03-09_08-10-2 copy](https://user-images.githubusercontent.com/34812175/76230987-8bc0ed00-624a-11ea-91af-386e33173757.png)

Here, you can find an instruction named test and there the program will check the values of eax and eax. In top of that, about like 4 lines before, there is a static push to the stack.
Print out the string value of this using x/s and get the passphrase for phase_1.


![2020-03-09_08-10-2 copy](https://user-images.githubusercontent.com/34812175/76231556-6a143580-624b-11ea-9efa-ecbe17be3132.png)


![2020-03-09_08-11-3](https://user-images.githubusercontent.com/34812175/76231645-887a3100-624b-11ea-9be0-bd756127200e.png)

Then run the sheldon1 again

![2020-03-09_08-34-6](https://user-images.githubusercontent.com/34812175/76231830-cd05cc80-624b-11ea-9e8a-b64ed42a8329.png)



