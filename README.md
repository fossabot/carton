# carton
> Well, if you want your cross-platform 
project to work on arduino ,that will 
 be pain in ass.

* The purpose of this project is to implement 
some daily-used containers for 
[UWE](https://github.com/quited/UWE)
 in cpp cause most embedded platforms don’t provide 
~any~ full STL support and STL containers is indeed
 much too heavy-weighted for embedded platforms.

* This project is expected to work on
 as many embedded devices as possible, 
such as stm32 and arduino, so our goal
 is to write code with low memory
 usage(as low as possible), which 
means that sometimes speed 
can be traded off.
 
## Roadmap

### Containers

* [ ] array
* [ ] vector
* [ ] map
* [ ] set
* [ ] buffer
* [ ] stack
* [ ] deque
* [ ] list

### Circle CI

* [ ] configuration 

## Compiler And Cpp Standard

* Personally I really want to use cpp 
module but for now it’s almost impossible 
(as we mainly use gcc toolchain)

* For now the newest version of 
arm-none-eabi toolset is 8 and ~gcc-avr
 is 9 so we decided to target c++14.~

* The freaking thing is that Arduino Ide
 is still using the aged gcc-avr 4.9 so 
we can only target c++11. Screw you arduino.

## Code Style 

We follow [google’s cpp
 style guidelines](https://google.github.io/styleguide/cppguide.html)

## License

MIT
