## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there
- Hi

## intent:goodbye
- bye
- goodbye
- see you around
- see you later

## intent:affirm
- yes
- indeed
- of course
- that sounds good
- correct

## intent:deny
- no
- never
- I don't think so
- don't like that
- no way
- not really

## intent:mood_great
- perfect
- very good
- great
- amazing
- wonderful
- I am feeling very good
- I am great
- I'm good
- I am good

## intent:mood_unhappy
- sad
- very sad
- unhappy
- bad
- very bad
- awful
- terrible
- not very good
- extremely sad
- so sad

## intent:bot_challenge
- are you a bot?
- are you a human?
- am I talking to a bot?
- am I talking to a human?

## intent:rivers_verify
- I got locked out of rivers
- I need Rivers Access
- I need access to rivers
- I need access to Rivers
- I need access to rivers please [*****ac.melton01@gmail.com](extract_email)
- I need access to rivers[ ](extract_email)[ ](extract_email)[ ](extract_email)[*****ac.melton01@gmail.com](extract_email)
- yes, I need access to rivers [*****ac.melton01@gmail.com](extract_email)
- I need access to rivers right now [*****ac.melton01@gmail.com](extract_email)
- I need access to rivers [*****ac.melton01@gmail.com](extract_email)
- I need access to rivers [*****ac_melton@hotmail.com](extract_email)
- I need access to rivers [9485235435214aN: AAMkADA1YTE1NzBjLWNjM2ItNDFjYy1iMzNhLWMxYzI3ZmNkNzUyYgBGAAAAAAD2KnCrb4HEQr2A6YrZyBFiBwAHGsWk4qReSpDk7en2ifvUAAAAAAEMAAAHGsWk4qReSpDk7en2ifvUAAAAB6nKAAA=](extract_id)

## regex:extract_email
- (?<=lkjdsfah5838fl3: )([a-zA-Z0-9._-]+@[a-zA-Z0-9._-]+\.[a-zA-Z0-9_-]+)

## regex:extract_id
- (?<=9485235435214aN: )(.*)
