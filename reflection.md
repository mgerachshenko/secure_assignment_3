AppScan caught the hard-coded credentials and the unencrypted HTTP url, which Bandit and CodeQL didn't flag.
Bandit seemed to focus on python issues like command injection, and CodeQL didn't really flag anything.
So overall, AppScan did the best job out of finding issues.