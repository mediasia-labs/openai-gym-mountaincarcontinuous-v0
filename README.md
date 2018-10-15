# Solving OpenAI Gym - MountainCarContinuous-v0

Solve MountainCarContinuous-v0 challenge with genetic style evolution.

![MountainCarContinuous-v0 Challenge](https://raw.githubusercontent.com/mediasia-labs/openai-gym-mountaincarcontinuous-v0/master/screenshot.png)

### Install

This project uses numpy and gym. Install depedencies with `pip`

	$ pip install -r requirements.txt

### Run

Run

	$ python train.py

Result

	$ python train.py
	Generation 1 Best score -200.001011045 Finished 0.0
	Generation 2 Best score 40.6576518519 Finished 1.08
	Generation 3 Best score 52.0173731036 Finished 1.7
	...
	Generation 26 Best score 87.6259341522 Finished 14.74
	Generation 27 Best score 87.4580638971 Finished 14.7
	Generation 28 Best score 88.1793944848 Finished 15.16

Challenge is considered solved when a network reaches an average score of 90 over 100 games