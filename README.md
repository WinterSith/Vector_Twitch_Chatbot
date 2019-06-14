# Vector_Twitch_Chatbot
Make Vector respond to Twitch chat commands

1) set up Vector SDK
2) Set up Twitch chatbot according to Twitch's instructions
3) place chatbot code and vector code in same directory
4) run chatbot program.  You will need to know your oauth token and client id.  I ran it from the command line as follows:
      python3 chatbot.py chatbot_account clinet_id oauth_token channel_to_join
      and here is their license: http://aws.amazon.com/apache2.0/
      
      
The Twitch chatbot app came directly from the Twitch dev web site.  It is all their code except for the part where I call the Vector pyhton code.

I developed this on a linux machine.  The call to the Vector program may need updated if done on a Windows machine
