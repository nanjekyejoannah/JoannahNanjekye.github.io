---
layout: post
title: How to make a fresh ubuntu install able to detect wireless connections
---

After struggling for four hours with this , I  finally found a solution.I hope this saves someone.

Now if you have just installed Ubuntu and are not able to see your available wireless connections the following helped me;

    Connect to the network through an Ethernet cable. You can actually USB tether to your phone.
    Then run the following commands. 
                **udo apt-get update**
                **sudo apt-get install bcmwl-kernel-source**                    
    Disconnect your Ethernet and the wireless connections should be visible now.

