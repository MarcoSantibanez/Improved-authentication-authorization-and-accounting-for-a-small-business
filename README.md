# Improved-authentication-authorization-and-accounting-for-a-small-business
I assessed the access controls used by a small business.

Tools used, google sheets and google docs.

Recently, a deposit was made from the business to an unknown bank account. The finance manager says they didn’t make a mistake. Fortunately, they were able to stop the payment. The owner has asked you to investigate what happened to prevent any future incidents.

I started by looking at the event log:

![image](https://github.com/MarcoSantibanez/Improved-authentication-authorization-and-accounting-for-a-small-business/assets/138132151/8bfde6b2-4c97-4063-a6fc-2ab947a90f37)



Then I looked at the current controls:

![image](https://github.com/MarcoSantibanez/Improved-authentication-authorization-and-accounting-for-a-small-business/assets/138132151/45f14b9a-e2eb-4c6b-a652-e7b755f07fe7)


Worksheet presented to owner:
![image](https://github.com/MarcoSantibanez/Improved-authentication-authorization-and-accounting-for-a-small-business/assets/138132151/94c49190-537b-4f4c-aa22-bdb438e7f49f)

In summary: 
It appears as though a former employee is potentially the threat actor. However, it's possible that they were not the person responsible for this security incident.

It is common for people to reuse login credentials across many services. And if those credentials are compromised on one platform then an attacker can use them to gain access to others. In this case, implementing access controls, like password policies, limited file permissions, and MFA can protect the business from incidents like this.


