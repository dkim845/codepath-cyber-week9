# codepath-cyber-week9
Codepath Cybersecurity assignment for Week 9

Total Time Spent: 5 hours

## Honeypot deployed
The basic Ubuntu - Dionea with HTTP honeypot was deployed.

## Issues Encountered
Most of the issues from the assignment came from installation issues. The insturctions were somewhat outdated.
For example, some of the github forks did not exist anymore and some steps were missing in order to properly set
up the honeypot. In terms of the honeypot itself, everything ran fine.

## Data Summary
In roughly an hour, there were around 808 attacks!

When analyzing the attacks, there were a number of details that stood out to me.
* One notable source of attacks was from India (650 attacks). The IP Address 122.172.70.93 showed that the city was Bengaluru. And the attack focused on Dst port 8455 (650 times!), which uses TCP and UDP protocols. TCP is the most commonly used port protocol on the Internet so it would make sense a larger amount of attacks would come from there.
* Other sources of attacks from the United States, Germany, the Netherlands, and many others targetted port 8088. Like the earlier port, it falls into the Registered category of ports, so while it is commonly used, the attacks targetted a known registered port that isn't quite in the "Well-known" category to avoid some popular defenses possibly. This port would be the second most popular port for attacks recorded.

## Questions
One question that I would have is that why after several minutes into the run time for the honeypot did a sudden influx of attacks from Bengaluru take over? No other countries appeared on the attack list while the attacks poured in from a single location. A question would be 
