# Pikachu_Simulator
A custom simulator was built using pygame and programmed using python to simulate A star search vs Bidirectional Search. We have named it as the Pikachu Simulator.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Clone and extract Pikachu_Simulator.zip in a Folder of your choice. To run it first install pygame:

Note : It works with python 3.7


```
Pygame
```

### Installing

A step by step series of examples that tell you how to get a development env running

For MAC OS
In terminal:
```
python3 -m pip install -U pygame --user
```

```
mkdir Pikachu
cd Pikachu
git clone https://github.com/gautam-sharma1/Pikachu_Simulator.git
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

In terminal:
```
python sim.py -a [astar or bidirec] -x [staring x position] -y [staring y position] -gx [goal x position] -gy [goal x position]
```
Note : Only put coordinates that are multiple of 25 and <=500.

Eg : 
```
python sim.py -a astar -x 0 -y 0 -gx 100 -gy 100
python sim.py -a bidirec -x 0 -y 0 -gx 100 -gy 100
```
The program execution time will be printed out to the terminal after the program terminates. Observe the difference in time between A star and Bidirectional.




## Built With

* [Pygame](https://www.pygame.org/wiki/GettingStarted) - Used for simulation environment


## Authors

* **Gautam Sharma** - *Initial work* - [Github](https://github.com/gautam-sharma1)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Tech With Tim (https://www.youtube.com/channel/UC4JX40jDee_tINbkjycV4Sg)

