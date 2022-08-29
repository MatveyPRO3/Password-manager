# Password-manager 🔑
This is password manager that works in console and allows you to create and use physical key for protecting your passwords
```
$ python main.py -i
Enter the physical key letter(without any punctuation): D
Key initialized successfully

$ python main.py -a
Service (google, twitch, skype etc...): steam
Account (nickname or mail): Killer404
Enter password: qwerty_
Detecting physical key...
Physical key found!
Detecting physical key...
Physical key found!
New password successfully saved!

$ python main.py -g
Service (google, twitch, skype etc...): steam
Account (nickname or mail): Killer404
Detecting physical key...
Physical key found!
Copied to clipboard!
```
Now you can paste your password anywhere!

```
$ python main.py -u
Detecting physical key...
Physical key found!
Key updated successfully
```
