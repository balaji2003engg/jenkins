# Jenkins EC2 plugin SSH keys

Problem statement : What SSH Keys are Needed for a New AWS Account in Jenkins EC2 Plugin?

Solution: 


Step 1: Transfer the SSH Keys from Master to New Account

First things first – get those SSH keys from your master node to the new account. It's like passing the baton in a relay race. This step ensures a secure connection and hassle-free access to your EC2 instances.

Step 2: Provide the Same SSH Private Key in EC2 Plugin

Now that your keys are on the move, head over to the EC2 plugin. When adding the new account, make sure to hand over the same SSH private key. It's like giving the secret handshake – it's what lets your EC2 plugin know it's dealing with the right keys.

Conclusion:

And there you have it, folks! Two straightforward steps to ensure your EC2 setup is as smooth as butter. Transferring SSH keys doesn't have to be a headache – follow these steps, and you'll be up and running in no time. Happy blogging!





