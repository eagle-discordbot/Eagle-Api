# Eagle-Api
Eagle Api is an usefull libary to using Eagle bot informations in your own discord bots or in your own websites

With Eagle Api, we can retrieve informations about user invitations, etc... (the rest is comming)

To use Eagle Api, we have to buy it on https://eagle-bot.ml/eagleapi/


## installation

In a command prompt, run this command:
```
pip3 install eagleapi
```

If it doesn't work, try all this commands,  maybe one can work
```
pip install eagleapi
py -m pip install eagleapi
python3 -m pip install eagleapi
py -m pip3 install eagleapi
python3 -m install eagleapi
py3 -m pip install eagleapi
py3 -m pip3 install eagleapi
python -m pip install eagleapi
python3 -m pip install eagleapi
python-pip install eagleapi
python3-pip install eagleapi
python-pip3 install eagleapi
python3-pip3 install eagleapi
```


## Documentation

* #### Get informations about an user invitations:

```py
import eagleapi

member = eagleapi.Invit_member(guild_id=560165986301640704, member_id=575012772526686208) #the bot Eagle need to be in your server, but now, he is not operational

print(member.nb_invites) #equivalent to print(membre.get_nb_invites())

print(member.invited_by) #equivalent to print(membre.get_inviter())
```
