# ism-library

Contains the ISM as downloaded from cyber.gov.au.

Please ensure you read the DISCLAIMER, and visit ACSC for more.

This will be used for some other projects.

# Contrib

Files were independently downloaded. SHA256 checksum generated and added
to manifest.

FTP the latest updates into src directory;
```ftp <url>```

Generate hash, and add to SHA256 file.
```sha256 <result> >> SHA256``` 

# Usage

As there's currently no other means of integrity validation with these
files, this is the next best option.

# suboptimal pack - out of memory
So... the total size of these is a little larger than I anticipated.
This then results in the above error.

You'll need to increase the size of git pack.windowMemory to around
1024M.

`git config pack.windowMemory 1024`
