## Test 



## Setup git environment in linux local
- make sure ssh connection is valid, use commnad:
'''
ssh -T git@github.com
'''
Should see : 
Hi ilovedennis! You've successfully authenticated,
but GitHub does not provide shell access.

- for empty folder
'''
git clone git@github.com:ilovedennis/ai_park.git
'''

- for exist folder
'''
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin git@github.com:ilovedennis/ai_park.git
git push -u origin main
'''
