# Revenge-Wrapper
A C# discord api wrapper by Xaxlii#1337

Standard usage:

```C#
Login:
DiscordClient Client = new DiscordClient("Token");

Sending Messages:
Client.SendMessage(ChannelId, Message, tts(either false or true), Embed);

Getting Users:
Client.GetUser(UserId);

Finding Any bugs make a pull request or an issue
