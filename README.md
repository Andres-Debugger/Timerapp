# Timerapp

![](https://github.com/Andres-Debugger/Timerapp/blob/Development/Mockup/Mockup.png?raw=true)
## What is Timerapp?
---

It is a fully customizable and cross-platform timer that at the same time works as a single page application. This application allows the user to create two time slots, to do that, they just have to press the "Settings" button, in it they will find two range inputs, the first symbolizes the period of time in which the user goes to "Work" and is represented in a green color, below it, represented in blue, the period in which the user goes to "Break" is located. Once you have configured according to your needs your rest and work periods, it is only a matter of going back through the "Go Back" button and giving it play, at that moment it will begin to count the work time and once it has elapsed, a beep will sound that announces that the work time has ended and automatically begin the rest time, thus creating an indefinite cycle, and in the case that you want to pause, you just have to pause it.
## Frameworks, Libraries and Packages Used:
---

- For Logic: 
	- [React.js](https://reactjs.org/ "React.js")
- For sound: 
	- [Howler.js](https://howlerjs.com/ "Howler.js") 
- For the Slider: 
	- [React-slider](https://www.npmjs.com/package/react-slider "React-slider")
- For the Pogressbar:
	-  [React-circular-progresbar](https://www.npmjs.com/package/react-circular-progressbar "React-circular-progresbar")
- For cross-platform:
	- [Electorn.js](https://www.electronjs.org/ "Electorn.js")
	- [Electron-builder](https://github.com/electron-userland/electron-builder "Electron-builder")
	- [Electron-is-dev](https://github.com/sindresorhus/electron-is-dev#readme "Electron-is-dev")
- For run multiple command:
	- [Concurrently](https://www.npmjs.com/package/concurrently "Concurrently")
- For run scripts that set and use environment variables across platforms:
	- [Cross-env](https://www.npmjs.com/package/cross-env "Cross-env")
	- [Wait-on](https://www.npmjs.com/package/wait-on "Wait-on")