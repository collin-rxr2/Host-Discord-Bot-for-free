# How to Host your Discord.py Bot for free
### Step 1
- Create an Account at https://fly.io/
- Download this Repository
- Navigate into it
- Download the Fly Command Line Interface
- Run this Command `flyctl launch`
-> Don't deploy just yet
- This should create a `fly.toml` File
- Run this Command: `flyctl auth token`
- Copy the Token to your Clipboard
### Step 2
- Create a new Repo
- Upload the Repository from earlier
- Click on Settings
- Click "Secrets and variables"
- Click on "Actions"
- Create a New repository secret
- The Name should be FLY_API_TOKEN
- Set the Value to the API Token you copied earlier
### Step 3
- Add your Requirements into `requirements.txt` if you haven't already
- Add your Token in `bot.py`
### Done
Your Code will now automatically deploy to the Cloud everytime you commit to the Repository
- Open an Issue if you need help
