# CIS567-integrated-lab-2
week 7 assignment

string = input()

char = string[0]
phrase = string[2:]

count = 0 

for ch in phrase:
    if ch == char:
        count += 1
        
if count == 1:
    print(count, char)
else:
    print(count, char + "'s")
