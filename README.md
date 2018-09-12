# Sarcasm as a Service
An API written with Mule that generates sarcastic sentences in compliance with the Sarcastic Spongebob Protocol. Basically it's this: https://stopthatrightnow.github.io/ as a service, which is what everyone wanted anyway. Be careful with weird characters (seriously, I'm not being sarcastic this time).

## Example:

Deploy this application on your own CloudHub instance and replace "somewhere.cloudhub.io" with your CloudHub host name.

### Request: 
http://somewhere.cloudhub.io/api/sarcasm?input=Hello%20World!

### Response:
hElLO wORld!
