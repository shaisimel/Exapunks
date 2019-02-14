An array of five Zippe-type gas centrifuges, ZGC0 through ZGC4, are connected in a cascade configuration.

Read each of the #ZGCX registers and determine which centrifuge currently has the highest pressure. Then disable that centrifuge's regulator by writing a value of 0 to its #POWR register. Repeat this process until all five regulators have been disabled.

![Solution](https://github.com/shaisimel/Exapunks/blob/master/Solutions/28%20-%20Last%20Stop%20SNAXNET/EXAPUNKS%20-%20Last%20Stop%20SNAXNET%20(198%2C%2057%2C%2022%2C%202019-02-14-16-01-28).gif)
