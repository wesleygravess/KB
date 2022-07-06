# 🎚 What is a Destination Tag?

In general, destination tags are used to identify transactions to large merchants and exchanges. This extra identifier allows for the transaction to be matched internally with a particular order. ShapeShift trades require a destination tag for all incoming deposits of XRP.&#x20;

### **Sending XRP to ShapeShift**

When trading XRP for BTC, for example, you will need to include a destination tag on the incoming deposit to ShapeShift. If you are using an XRP client wallet, you will need to use the special format we provide on the order page. It will look something like this: "rwfGzgd4bUStS9gA5xUhCmg1J86TMtmGMo?dt=10002653".

If you are using an exchange, a third-party wallet, or a multi-coin wallet, there may be separate fields for the address and the destination tag. You will separate them both and only include the numbers at the very end of the string in the destination tag field (Ex. "10002653").
