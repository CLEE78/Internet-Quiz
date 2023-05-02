# Internet-Quiz
print("Welcome to my internet quiz!")

playing = input("Are you going to play? ")

if playing.lower() != "yes":
    quit()

print("Great! Let's play :)")
score = 0

answer = input("What is CPU ? ")
if answer.lower() == "central processing unit":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What is GPU ? ")
if answer.lower() == "graphics processing unit":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What is RAM ? ")
if answer.lower() == "random access memory":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What is PSU ? ")
if answer.lower() == "power supply":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

print(f"You got + {score} + questions correct!")
print(f"You got " + {score / 4} * 100) + "%.")
