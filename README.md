# Description

This is a domain-specific bot based on the open source RASA platform. Its purpose is to book a flight ticket for the user. It is a schematic example of the expected interaction, no actual purchases can be made. The idea is for the bot to demonstrate use of a form, proper entity derivation and extraction, and intent comprehension.

## In order to run the bot follow the steps bellow

1) Clone the repository
2) Execute the following commands:
```
python3 -m venv ./venv
```
```
source ./venv/bin/activate
```
```
pip3 install -U pip
```
```
pip3 install rasa[spacy]
```
The last command will install RASA as well as Spacy, which is a library necessary for the correct derivation of cities given as input to the bot.

3) In order to train the bot after modifying the codebase:
```
rasa train
```
4) In order to train it interactively:
```
rasa interactive
```
5) To run the bot and interact with it:
```
rasa shell
```
