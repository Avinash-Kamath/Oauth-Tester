# Oauth-Tester
A simple Test UI for testing Outh Flow. 
- View Decoded ID tokens, access tokens in Json
- Refresh Tokens if refresh token is available
- Timer for access token expiry for easy debugging
- Backchannel and front channgel logouts with IDP endpoints

## Setup Instructions

1. **Fill the Configuration**  
   Edit the `config.json` file and provide your OAuth client details:
   ```json
   {
     "client_id": "YOUR_CLIENT_ID",
     "client_secret": "YOUR_CLIENT_SECRET",
     "authorization_endpoint": "YOUR_AUTHORIZATION_ENDPOINT",
     "token_endpoint": "YOUR_TOKEN_ENDPOINT",
     "scopes": "openid profile email offline_access"
   }
   ```

2. **Install Dependencies**  
   Make sure you have Python 3 installed. Then install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**  
   Start the app with:
   ```bash
   python outh_test.py
   ```

4. **Open in Browser**  
   Navigate to [http://localhost:5555](http://localhost:5555) to use the OAuth Tester UI.

## View Tokens
![image](https://github.com/user-attachments/assets/0f5de532-64ec-40ee-9925-770845ed2c1b)


## Refresh Tokens
![image](https://github.com/user-attachments/assets/500b4a8f-9172-4188-a317-e8b8da77e54d)
