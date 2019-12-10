# Enigma
This project is a python virtualisation of the 3 rotors enigma. A machine that was used by german nazy in the Second World War to encrypt messages.

# What is enigma?
Enigma – one of the most powerful encryption device built in that period. Created by Arthur Scherbius and Richard Ritter, at first the navy of Germany didn’t pay any attention to its invention. But in 1926 the navy started to build its own Enigmas. And that gave the German army a big advantage in this bloody war.  

# What this project have in it.
This project is built from just 2 file.
* A Enigma machine python file file (enigma.py)
* A settings file for enigma (settings.json)

# Enigma file
In this file enigma machine is implemented as a python class. This a class have next features:
* __init__ function that allows to set the enigma in 3 different ways. One from a json settings file, manually and default settings.
* The Steckerbret or the tableau of sockets that allows to set specific encryptions for certain chracters.
* The 3 rotors: Alpha, Beta and Gama. They are integers that are used as keys for permutation encryption algorith.
* The reflector: It is an alphabet turned backward with the letters from steckerbret deleted. It returns the mirror of the the certain letter form the alphabet.
* permutation function: This function do the k-permutation algorithm.
* inverse_permutation function: This function do the k-permutation algorithm backward.
* encrypt_text function: This function encrypts a certain string.
* encrypt_txt function: This function encrypts a certain file creating a new one.

# The settings file
If Enigma is seted from a json file then this file must have next values in the dictionary form:
* steckerbret - a dictionary with all pairs of letters that should that represent the steckerbret.
* alpha - an integer that sets the alpha rotor.
* beta - an integer that sets the beta rotor.
* gama - an integer that sets the gama rotor.

Created by Păpăluță Vasile (Science_kot) 
facebook link: https://www.facebook.com/papaluta.vasile.77 
instagram link: https://www.instagram.com/science_kot/ 
e-mail: vpapaluta06@gmail.com vasile.papaluta@microlab.utm.md
