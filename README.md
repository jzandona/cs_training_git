# cs_training_git

# 1st Part
## Setup your local directory
`mkdir github && cd github`

## Clone Repository
`git clone https://github.com/jzandona/cs_training_git`

## Try Commit
`git commit`

## Change Directory
`cd cs_training_git` 

## Update Detection
`vim rules/crowdstrike_rules/crowdstrike_dns_request.py`

## First Commit 
`git commit -m “my first message”`

# 2nd part
## Pull latest
`git pull`

## Update detection
`vim rules/crowdstrike_rules/crowdstrike_detection_passthrough.yml`

## Second Commit
`git commit -m “my second message”`

## Check Connection 
`panther_analysis_tool check-connection --api-token ADD_TOKEN --api-host https://api.papaya-junior.runpanther.net/public/graphql`

## Upload Detection


# Troubleshooting
## panther_analysis_tool not found
If error says `command not found: panther_analysis_tool`

Try using:
`export PATH="/Users/$LOGNAME/Library/Python/3.9/bin/:$PATH"` 

## Upgrading panther_analysis_tool
`pip install --upgrade panther_analysis_tool`

# 3rd Part (Take Home)

## Push a change to this repository. 
Hint: Requires Github Account
1. You will need to create a branch and make your changes within the branch

2. Publish the branch to the this repo

3. Create a `Pull Request` on the branch to merge into `main`