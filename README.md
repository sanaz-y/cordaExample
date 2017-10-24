![Corda](https://www.corda.net/wp-content/uploads/2016/11/fg005_corda_b.png)

# Example CorDapp

Welcome to the example CorDapp. This CorDapp is documented [here](http://docs.corda.net/tutorial-cordapp.html).

The contract has been extended so that if the lending and borrowing countries must not be same. Note that the code is relying on the user to input countries correctly. This is a quick extention so some checks are deliberately skipped. 

![extended contract](https://raw.githubusercontent.com/sanaz-y/cordaExample/release-V1/Screen%20Shot%202017-10-24%20at%2017.08.49.png)

Because in the above request the lending and borrowing countries are the same, the transaction is failed and will not be added to the ledger.

![transaction failed](https://raw.githubusercontent.com/sanaz-y/cordaExample/release-V1/Screen%20Shot%202017-10-24%20at%2017.08.59.png)
