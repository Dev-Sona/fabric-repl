# fabric repl

## what is it

a repl for fabric server ops to run code on the fly while the server is still on

## why

because it's cool idk, the point is everybody needs this for a different reason and you can make multiple script files and shit and choose which one to run so why wouldn't you want this if ur a server owner?

## ok how do i do it 

when you first run your server with the mod, it will create a folder with a maven project set up with all your mods as dependencies.
open this with any IDE you like and you can have full syntax highlighting. 
script entrypoints should be placed in src/scripts/ and have a class that inherits from the IScript interface. if it does not, it will not work. 
do /script <class-name> 
if the code has not changed, it will use the cached class.