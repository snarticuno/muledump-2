1. Download this repo.
    For simplicity I'm going to assume you're going to put it in 
    C:\Users\Example\Desktop\muledump-2-master
2. Download GoLang from here: https://golang.org/dl/ (also install it ofcourse)
3. Open your command prompt (Windows key+R, type in cmd.exe and hit enter)
4. Type in the following:
    cd "C:\Users\Example\Desktop\muledump-2-master"
5. Type in the following: go build
6. Type in the following again: go build
    You should now have an executable called 
    muledump-2-master.exe.
7. Open accounts_sample.js with a text editor (for instance Notepad++)
8. for steam users: put in your steamworks UID.
    for browser/flash player users: put in your email address. 
    You do NOT need to enter your actual password/steamworks token in there, only your email/user id.
    It should look something like this: 

    accounts = {
    'me@example.com': 'example',
    }


9. Save the file as accounts.js (make sure it saves as a .js file, and not accounts.js.txt)
10. Open example_config.json with a text editor (for instance Notepad++)
11. Put in your email and password in there. For steam users, put in your steamworks user id and secret token.
    It should look something like this:
[
    {"user":"my@email.com", "password":"mypassword123"}
]

12. Save the file as config.json. Make sure the file extension is .json instead of .txt
13. Go back to your command prompt. Type in: 
muledump-2-master.exe "config.json"
14. Go to http://localhost:5353/muledump.html and click reload all.
