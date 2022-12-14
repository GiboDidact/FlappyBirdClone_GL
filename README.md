# Flappy Bird Clone

This project was created for fun and to try and recreate the popular game Flappy Bird. 
In Config.h you will see some configuration variables you can mess with to test different things. 
In the game files there is a configuration file as well as error logs in the log directory.

Download game at: https://www.dropbox.com/s/lhkcwmjyfvpjxh9/FlappyBird.zip?dl=0

## Features
- Frame Rate independence (fixed time step with interpolation rendering)
- Screen Size independence (game scales with screen)
- OpenGL rendering with multiple version support 3.0+
- Binary game data export/import
- Protected save file (hashing)
- Error log output
- Configuration file support
- Audio

## Dependencies
- GLM: GLM math library is used. Its already included in the Src/ThirdParty directory
- STBI: this image loading library is used. Its already included in the Src/ThirdParty directory
- GLEW (version 2.1.0): is used to load OpenGL functions. Is available on cross-platform
- GLFW (version 3.3): is used for window handling, and event handling. Is available on cross-platform
- irrKlang (version 1.6.0): Audio library. Is available on cross-platform. Requires irrKlang.dll in running directory

- This game runs on x64 bit. All dependencies support x64.

- Currently only runs on Windows platform. If you build libraries for other operating systems should work. The internal code has no OS dependencies.

- OpenGL Versions supported are 3.0 and up. 


<img width="314" alt="git_1" src="https://user-images.githubusercontent.com/33635742/203861828-ff6b0892-b55a-4c2a-9f4f-f14ea26f4154.png"> <img width="315" alt="git_2" src="https://user-images.githubusercontent.com/33635742/203863506-08ebf979-0771-4a62-8124-22b28d49ac1a.png"> <img width="315" alt="git_3" src="https://user-images.githubusercontent.com/33635742/203863517-61119a99-428e-4ec3-a999-d7f1f3454ebd.png"> <img width="313" alt="git_4" src="https://user-images.githubusercontent.com/33635742/203863922-079ef2e1-9192-483f-b4b0-47b207eba090.png">
