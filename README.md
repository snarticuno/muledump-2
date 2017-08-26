1. Download this repo.
    For simplicity I'm going to assume you're going to put it in 
    C:\Users\Example\Desktop\muledump-2-master
2. Open accounts_sample.js with a text editor (for instance Notepad++)
3. Enter your account info. Steam and Kong do not work as of now.
    It should look something like this: 

    accounts = {
    'me@example.com': 'example',
    }

4. Save the file as accounts.js (make sure it saves as a .js file, and not accounts.js.txt)
5. Open example_config.json with a text editor (for instance Notepad++)
6. Put in your email and password in there. For steam users, put in your steamworks user id and secret token.
    It should look something like this:
[
    {"user":"my@email.com", "password":"mypassword123"}
]

7. Save the file as config.json. Make sure the file extension is .json instead of .txt
8. Go back to your command prompt. Type in: 
muledump-2-master.exe "config.json"
9. Go to http://localhost:5353/muledump.html and click reload all.
