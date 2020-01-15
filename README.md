# nodeploy
How do you deploy a 100% secure web application without substantially increasing risk?

This is inspired by Kelsey-Hightower's [nocode](https://github.com/kelseyhightower/nocode) project and a question. Are there 0, 1 or infinity ways to not deploy nocode?

Although nocode explicitly states that it should not be deployed, the fact that it exists as a repo on github and is viewable to anyone, which is apparently its primary purpose, suggests that it is already deployed.

Conjecture: The number of ways to not deploy nocode is infinity, with a lim-sup of a the set of all deployments which add no significant risk.

That conjecture doesn't seem very manageable, so let's tackle an easier problem first.
What is the most secure way possible to deploy nocode. Is github.com with its millions of users and occasional CVE the most secure way to deploy it? What about this thing called "Provable Security". Can it help us? How do we threat model nocode and nodeploy?

What is the risk of nocode to supply chain attacks? That is, can an attacker inject some code into nocode violating its core pricinple? Is github with its thousands of servers and employees and rapidly expanding "Actions" offerings the safest deployment of nocode? 

If you're beginning to suspect that nocode was not nodeployed in the safest manner you are in the right place.

What is the safest way to nodeploy nocode?





