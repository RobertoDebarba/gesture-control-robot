# Gesture Control Robotic Vehicle

A gesture control robotic vehicle based on the Esp8266 NodeMCU and Arduino.
Through gestures with the glove the user can move the robot forward, back and side, without clicking any button!

All the components and build instructions are described in [this paper](https://github.com/RobertoDebarba/gesture-control-robot/blob/master/docs/paper.pdf).

<img src="https://github.com/RobertoDebarba/gesture-control-robot/blob/master/docs/presentation.gif">
<img src="https://github.com/RobertoDebarba/gesture-control-robot/blob/master/docs/glove.jpg">
<img src="https://github.com/RobertoDebarba/gesture-control-robot/blob/master/docs/vehicle.jpg">

## How to run

### Prerequisites

* [PlatformIO](https://platformio.org/)
* Install NodeMCU on PlatformIO
* Install NodeMCU drivers (on Windows)

### Build and flash

1. Build and flash ./glove project on glove NodeMCU
1. Build and flash ./car project on vehicle NodeMCU

*Follow PlatformIO instructions to build*

## Authors

* [Roberto Luiz Debarba](https://github.com/RobertoDebarba)
* Guilherme Stiehl Ceroni

## License

The codebase is licensed under [GPL v3.0](http://www.gnu.org/licenses/gpl-3.0.html).