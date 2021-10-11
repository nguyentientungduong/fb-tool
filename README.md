# PMH - Python Auto Comment & Share Facebook

Facebook auto comment and share, this is very useful for the promotion or any

### Installation:


* we use python 2.7, > for windows download from https://www.python.org/downloads/
* Import Module with pip or easy_install

```python
pip install mechanize
```

For running, go to directory facebot and run
```python
python start.py
```

### Configuration:

* set accounts username-password in file : `accounts.txt` separated by a `new line`
* set comments text in file : `comments.txt`  separated them with `::`
* set shares text in file : `shares.txt` separated them with `::`
* and setup delay, id post and url to share in file : `start.py`
```python
delay           = 10 # delay change account
delay_comment   = 4 # delay comment
delay_share     = 7 # delay share
delay_logout    = 3 # delay logout
id_post         = '905146633758398' #id post to comment
link_share      = 'https://www.facebook.com/cafeine.d/videos/905146633758398' # url post or url web to share
accounts_file = "accounts.txt" # account file in same folder
comments_file = "comments.txt" # comments file in same folder
shares_file   = "shares.txt" # shares file in same folder
```


That's it ..

### Donation

If this project help you reduce time to develop, you can give me a cup of coffee :)

[email](nguyentientungduong@gmail.com)
