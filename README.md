# sambot-ai-chatbot
This is an api for an artificial inteligent chabtot. Access it via a GET request.

# Usage
To use this api, all you need to do is send a GET request to the Sam Bot server. To use my chatbot, send a GET request to:
http://sambot.ddns.net/text/api/?input=

Keep in mind that this chatbot api can only process alphanumeric characters and the "+" character. If you have any input with non-alphanumeric character besides the "+" symbol, please remove them when using this api. Additionally, all spaces should be replaced with the "+" symbol. Characters not allowed in the GET request include, {! @ # & ( ) – [ { } ] : ; ', ? / * ` ~ $ ^ = < >} 

# Examples

For example, if you would like to say "hello" to the chatbot, you would go the the url:
http://sambot.ddns.net/text/api/?input=hello

If you would like to say "What's up" to the chatbot, you would go the the url:
http://sambot.ddns.net/text/api/?input=Whats+up
Again, make sure to replace all spaces with "+" and remove characters that are not alphanumeric.

As a last example, if you would like to say "Leave me alone!" to the chatbot, you would go the the url:
http://sambot.ddns.net/text/api/?input=Leave+me+alone

# Output
This api outputs all data as a json. This api always outputs as a json array with a size of two. The first index will be your input as a string and the second will be the chatbot's output as a string. Since the ouput will always be a json, you can use this api in any proggramming language. 

# Java Integration
Examples coming soon...

# PHP Integration
Examples coming soon...


# Contact
This chatbot api was created by Sam Bhatt. If you have any questions or concerns, you can email me at samalert101@gmail.com. Or you can visit my GitHub @SamMachine.
