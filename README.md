# .github-workflows
DevOps Scenario 

name: Super-Linter
  on: push 

Lint code base 
    jobs:

runs-on :ubuntu-latest 
# Checkout code
actions/checkout@v2
github/superlinter@v4  
# Configure environment 
env: 
  Defualt_branch = main
  Github-Token = ${{secrets.github_token }}
  # scrape stock data 
  AAPL, BRK. A, META, MSFT, NVDA, and TSLA 
  # run every 15 mins 
  
