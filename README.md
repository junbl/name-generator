# Name Generator

## Overview

Generates dramatic-sounding, mostly silly, fantasy-themed names and titles as Markov chains. Created as the final project for APPM 3310: Matrix Methods with Eugene Miller and John Salame.

## Usage

    usage: name_generator.py [-h] [-x AMOUNT] [-n NAMES]

                         [-p PLACES]
                         
                         [-t START_STATE END_STATE STEPS]
                         
                         [-q] [-a]

    optional arguments:
        -h, --help            show this help message and exit
        -x AMOUNT, --amount AMOUNT
                        Number of names to generate
        -n NAMES, --names NAMES
                        Names source file
        -p PLACES, --places PLACES
                        Places source file
        -t START_STATE END_STATE STEPS, --transition START_STATE END_STATE STEPS
                        Probability that you will end in a
                        given state starting from a
                        different state in the specified
                        number of steps
        -q, --quiet           Suppress printing
        -a, --average         Print average chain length

The files loc.csv and names.csv contain a collection of places and names from which the generator can draw possibilities.

## Sample output

    Rhoda Lightfoot, Caster
    Melba Boffin, King
    Krisztina Varga of Serpent Slayer
    Kris Kenka of Tanaris
    Tre'gok T'lak, Foe of Fort Collins, Metal Killer
    Kund Havasi, Blood Blight of Stormwind
    Jessamine Took-Brandybuck, Slinger of Dragon Dragon Slinger
    William Adams of Scholomance
    Sirella Mogh, Shaker
    Brosca Szepesy, Death Lord of Uldaman
