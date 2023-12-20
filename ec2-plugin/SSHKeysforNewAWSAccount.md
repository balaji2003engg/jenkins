# Jenkins EC2 plugin SSH keys

     Problem statement : What SSH Keys are Needed for a New AWS Account in Jenkins EC2 Plugin?

Solution: 


     Step 1: Copy the SSH Keys from Master to New Account

First things first – get those SSH keys from your master node to the new account. It's like passing the baton in a relay race. This step ensures a secure connection and hassle-free access to your EC2 instances.
    Refernce Link : 
    https://github.com/balaji2003engg/AWS/blob/main/Copy%20a%20Key%20Pair%20Generated%20by%20AWS%20%20Another%20Account/Copy%20a%20Key%20Pair%20Generated%20by%20AWS%20to%20Another%20Region%20or%20Another%20Account.readme.md

    Step 2: Provide the Same SSH Private Key in EC2 Plugin

Now that your keys are on the move, head over to the EC2 plugin. When adding the new account, make sure to hand over the same SSH private key. It's like giving the secret handshake – it's what lets your EC2 plugin know it's dealing with the right keys.

    Conclusion:

And there you have it, folks! Two straightforward steps to ensure your EC2 setup is as smooth as butter. Transferring SSH keys doesn't have to be a headache – follow these steps, and you'll be up and running in no time. Happy blogging!





