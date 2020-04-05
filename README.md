# Vimrc-for-cp
A basic vimrc for competitive programming

This is my attempt to congfigure vim for competitive programming. It has been equipped with all the necessary tools for cp such 
as auto indentation, syntex highlighting, automatic bracket closing etc. 

The theme i am using is tender. This is a classic dark theme for vim which i installed using this repo: 

https://github.com/jacoborus/tender.vim

It provides basic functionalities for competitive programming. Whenever you create a new .cpp file uisng terminal it loads it with 
your predesigned template and for that please store your template on ~/.vim/templates/ under the file name skeleton.cpp. Also after completing the code
you can run the code by pressing ctrl+C which enters you into the interactive mode where you can enter the input and then after running the program
press enter to return to vim. Also you can save the code automatically by pressing F2 in command mode.

The features i talked about are only available for file with extension .cpp. So you can try this vimrc by pasting this code in your vimrc.

I am still working on some features for splitting the screen and working simultaneously for taking in input and output on different windows by splitting the screen.
