1. Download this repo.
    For simplicity I'm going to assume you're going to put it in 
    C:\Users\Example\Desktop\muledump-2-master
2. Open your command prompt (Windows key+R, type in cmd.exe and hit enter)
4. Type in the following:
    `cd "C:\Users\Example\Desktop\muledump-2-master"`
5. Open accounts_sample.js with a text editor (for instance Notepad++)
6. Enter your account info. Steam and Kong do not work as of now.
    It should look something like this: 

    accounts = {
    'me@example.com': 'example',
    }

7. Save the file as accounts.js (make sure it saves as a .js file, and not accounts.js.txt)
8. Open example_config.json with a text editor (for instance Notepad++)
9. Put in your email and password in there. For steam users, put in your steamworks user id and secret token.
    It should look something like this:
[
    {"user":"my@email.com", "password":"mypassword123"}
]

10. Save the file as config.json. Make sure the file extension is .json instead of .txt
11. Go back to your command prompt. Type in: 
muledump-2-master.exe "config.json"
12. Go to http://localhost:5353/muledump.html and click reload all.
