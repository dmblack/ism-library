# ism-library

Contains the ISM as downloaded 1930hrs AEST from cyber.gov.au.

Please ensure you read the DISCLAIMER, and visit ACSC for more.

This will be used for some other projects.

# suboptimal pack - out of memory
So... the total size of these is a little larger than I anticipated.
This then results in the above error.

You'll need to increase the size of git pack.windowMemory to around
1024M.

`git config pack.windowMemory 1024`
