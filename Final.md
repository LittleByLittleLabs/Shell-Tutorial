Final
=====================

**One**:

Resolve Git conflict 

Fork, clone and run the script at https://github.com/LittleByLittleLabs/create-git-conflict.sh

Merge branch to master by resolving conflicts. Turn in output of the commands that you used to solve this problem using `history`.

Acceptence Criteria: Please remember to use Git best practices. 

**Two**:  

Build a SQL schema for Kata01: Supermarket Pricing
http://codekata.com/kata/kata01-supermarket-pricing

Acceptence Criteria: Must be valid SQL schema and expected to run using psql. Must also model the use cases discussed in class. Add comments to describe how your schema definition satiesfies the various use cases in the problem statement.

**Three**:  

Write a script (Bash or Awk) to download “Art of War” by Sun Tzu, parse and print a table of the following:

 - Top 15 most frequent words 
 - Least 15 frequent words
 - Average word size
 - Length of shortest word
 - Length of longest word
 - Number of sentences

    https://www.gutenberg.org/files/132/132.txt
    
    Acceptence Criteria: Your script must read each line once. Please remember to use shell script best practices. 

**Four**:  

Write a script (Bash or Awk) which lists all the URLs referenced in www.google.com source code.

Acceptence Criteria: Display all links (including relative, absolute, and http urls)
 
**Five**: Extra Credit (10 pts)
 

Create a Vagrant file and a bash script to configure the software stack at https://github.com/Instagram/python-instagram
```
This repository includes a one-file sample app that uses the bottle framework and demonstrates authentication, subscriptions, and update processing. To try it out:

Download bottle if you don't already have it: pip install bottle

Download bottle-session if you don't already have it: pip install bottle-session

Download and run a redis instance on port 6379 if you don't already have it. Check http://redis.io for instructions.

Run `python sample_app.py`

Try visiting http://localhost:8515 in your browser
```

Acceptence Criteria: `vagrant up` should allow a curl command on `http://localhost:8515` to work.
