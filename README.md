### description

solaris-monitor is a small python program that allows you to monitor multiple solaris games at once. it generates a table with all the attacks, time until next tick and can play a sound when a new attack is detected.

### dependencyes
`python3.6+`\
*`requests`\
*`playsound`

### usage
solaris-monitor will ask for your solaris login credentials. after login it will store a file called `solaris-cookie.cookie` on the directory you started the program. NEVER SHARE YOUR `solaris-cookie.cookie`.

after a succesfull login you will not need to log in again, as long as you have your cookie. the program will display a table with information on the games you are currently participating. you can press `enter` to enter command mode. in command mode the table will not be updated, so it's important that you press `enter` once again.

## commands
`(q)uit`/`exit`\
`(d)ismiss <gameID>`: resets the new attacks of this game to 0
