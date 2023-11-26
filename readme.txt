Create a client_secrets.json with the following details:

{
  "web": {
    "client_id": "Enter client id here",
    "client_secret": "Enter client secret here",
    "redirect_uris": [],
    "auth_uri": "https://accounts.google.com/o/oauth2/auth",
    "token_uri": "https://accounts.google.com/o/oauth2/token"
  }
}


Make sure you have all the python libraries mentioned in requirement.txt in you env.



To Run the script paste the following lines in command line terminal and replace all the values as needed:

python upload_video.py --file="/tmp/test_video_file.flv"
                       --title="Summer vacation in California"
                       --description="Had fun surfing in Santa Cruz"
                       --keywords="surfing,Santa Cruz"
                       --category="22"
                       --privacyStatus="private"