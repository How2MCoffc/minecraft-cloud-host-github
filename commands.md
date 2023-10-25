### To run the server 
java -Xmx6G -Xms6G -jar server.jar nogui

# ngrok
[Create Account on ngrok.com](https://dashboard.ngrok.com/get-started/your-authtoken)

### To invite friends
bash : ./ngrok authtoken 'your_auth_token'
bash : ./ngrok tcp -region='your_region' 'server_port'

### Here are some common region codes you can use:
us: United States
eu: Europe
ap: Asia-Pacific
au: Australia
sa: South America
jp: Japan
in: India


