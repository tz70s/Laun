# Laun
#### A useless lazy tool

* Target:
I'm inspired to do files exchange via dropbox, because my usbs got disappeared very often.
This is a weak command line tool I think.

The program is still develop.
So, the access token I hidden it,  you can generate it by your self. 

```Python
authorize_url = flow.start()
print ("Go to ",authorize_url)
code = raw_input("Enter the authorization code").strip()
access_token, user_id = flow.finish(code)

client = dropbox.client.DropboxClient(access_token)

```

* Reference : Dropbox python api documentation

* Usage : Look usage docs

```Bash
./Laun -h 
```
