# README for multi-account ECR and secret policy for Azure DevOps Builders

Assume "aaaaaaa" account is the Hub where secret and ECR lives, 
and "bbbbbb" account is a single spoke account. Spoke accounts can 
scale out to 'n' number, effectively infinite. 

This permits managing your secret PAK and image in one place, and 
all spoke accounts will pick up the values and use them. 