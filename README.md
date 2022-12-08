```py
if __name__ == "__main__":
  from college import clinical_depression
else:
  def clinical_depression():
    hobby = "Crying in a corner"
    return hobby

import os
def clear():
  if(os.name == 'posix'):
    os.system('clear')
  else:
    os.system('cls')
  
def brainrot():
  while True:
    clear()
    choice = "null"
    choice = input("Hi there, I'm NitWitted, a lonely depressed fuckwit that doesn't know common sense and limits to insanity.\n\nPlease choose a mode! (type 'EXIT' to exit)\n1. Personal info\n2. why?\n3. Jesus fucking god why would you do something like this?\n\n\nYour choice: ")

    if choice == "1":
      clear()
      input(f"Name: Nitwit\nAge: Old enough to bang ur mom\nJob: Student slave\nHobbies: {clinical_depression()}\nLanguages: Dutch, English, Python, Javascript, Html, Php, peepee poopoo\n\n\nPress ENTER to continue: ")

    elif choice == "2":
      clear()
      input("Because yes.\n\n\nPress ENTER to continue: ")

    elif choice == "3":
      clear()
      input("I have serious brain damage\n\n:)\n\n\nPress ENTER to continue: ")

    elif choice.lower() == "exit":
      clear()
      break

    else:
      clear()
      input("You put in an invalid response, I deez nutsed ur mom, we are not the same. [insert meme here]\n\n\nPress ENTER to continue: ")

if __name__ == "__main__":
  brainrot()

```
