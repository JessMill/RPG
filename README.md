# RPG

import pygame
import sys
import os

mainHand = ['Sword', 'Dagger', 'Katana', 'Axe', 'Great Axe', 'Great Sword', 'Staff', 'Wand', 'Bow']
body = ['cloak', 'Tunic', 'Robe', 'Chainmail', 'Subligar']
feet = ['Leaping Boots', 'Cotton Boots', 'Simple Bracers', 'Mercenary Gaiters']
hands = ['Leather Gauntlets', 'Cotton Gloves', 'Tekko', 'Mercenary Gauntlets']
offHand = ['Sword', 'Katana', 'Wand', 'Dagger', 'Axe', 'Shield']
head = ['Wizards Hat', 'Deulist Chapeau', 'Bronze Helmet', 'Hunters Beret']
gear = [mainHand, body, feet, hands, offHand, head]

stats = {'Name':}

inventory = 

Hero = {Name}

subject -> verb -> object (evoke, action, target)
ex hand.cast.Ogre(), staff.cast.Warlock()


# focus - higher damage, higher delay
# clear - higher accuracy, regular delay
# haste - lower accuracy, regular dps, lower delay

# each player has 2 moves per turn. Turns take place concurrently.
# turn consists of 1 move per hand  - can attack/block twice if dual wield 
# or double hand weapons 

# if certain actions both take place concurrently (such as a spell or attack), 
# a minigame duel takes place. The odds of winning can be influenced before the duel
# by the way the action is rigged up (i.e cast fire with focus+ and elemental match
# will give you better chances against a caster who simply casts fire alone)

def spell(name):
	element.fire() or element.ice()
	forceWave()
	
	
	


