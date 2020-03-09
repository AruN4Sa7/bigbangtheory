# bigbangtheory

In here Sheldon 1 is not the executable file there for its need to give the execute permission

![Capture](https://user-images.githubusercontent.com/41334869/76190703-d1be7800-619a-11ea-8c7e-dd1b076fc2de.PNG)

After Run the Sheldon1

![Capture 2](https://user-images.githubusercontent.com/41334869/76190977-8789c680-619b-11ea-9a1f-f7a6e156f358.PNG)

And this is the some kind of game ,its need to provide some secret code to achieve the key, to achieve the secret key need to reverse the 
given code.we use to gdb application to debug., Usin "gdb sheldon1" command can be debug

Using "info function" Command can extract the function of the sheldon 1

![Capture 3](https://user-images.githubusercontent.com/41334869/76191313-4cd45e00-619c-11ea-81cf-f15920d40a8f.PNG)

After that Using "disassembly main" command can be extract the main function

![Capture 4](https://user-images.githubusercontent.com/41334869/76191711-3a0e5900-619d-11ea-8312-5369e7304699.PNG)

There have special function call phase_1

![Capture 5](https://user-images.githubusercontent.com/41334869/76191798-6629da00-619d-11ea-963a-3e19642103f6.PNG)

Extract the Phase_1 fuction using the "disassembly Phase_1" command

![Capture 6](https://user-images.githubusercontent.com/41334869/76191890-9a9d9600-619d-11ea-80b5-ea6ef09168af.PNG)
 There have push memory address to stack
 0x80497c0, In 'Phase_1', There is a call to function 'strings_not_equal' with the first argument is 'input', the second argument is constant memory address 0x80497c0. after the call, in line 390, it's testing the return value, 'explode_bomb' is called if non-zero. So, we just type the same string as stored at 0x80497c0
 
 ![Capture 7](https://user-images.githubusercontent.com/41334869/76194305-249c2d80-61a3-11ea-87ae-a9987b277d7b.PNG)
 
 check founded secret with the sheldon 1
 
 ![Capture 8](https://user-images.githubusercontent.com/41334869/76194478-7fce2000-61a3-11ea-98f0-76b3dd9f965f.PNG)

 

