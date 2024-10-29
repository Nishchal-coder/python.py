# DICE ROLLING GAME

import random

while True:  # Correct capitalization for "True"
    choice = input('Roll the dice? (y/n): ').lower()


    import random
while True:

    if choice == 'y':  # Use '==' for comparison, not '='
        dice1 = random.randint(1, 6)
        dice2 = random.randint(1, 6)  # Corrected to randint instead of "radiant"
        print(f'({dice1}, {dice2})')
        
    elif choice == 'n':  # Use 'elif' here to check for 'n'
        print('Thank you for playing!')
        break
    
    else:
        print('Invalid choice')
