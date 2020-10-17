# Eagle-Api
Eagle Api is an usefull libary to using Eagle bot informations in your own discord bots or in your own websites
With Eagle Api, we can retrieve informations about user invitations, ... (this is not finish)

To use Eagle Api, we have to buy it on https://eagle-bot.ml/eagleapi/


##installation

copy repository in the folder of your project


##Documentation

####Get informations about an user invitations:

```py
import eagleapi

member = eagleApi.Invit_member(guild_id=560165986301640704, member_id=575012772526686208) #the bot Eagle need to be in your server, but now, he is not operational

print(member.nb_invites) #equivalent to print(membre.get_nb_invites())

print(member.invited_by) #equivalent to print(membre.get_inviter())
```
