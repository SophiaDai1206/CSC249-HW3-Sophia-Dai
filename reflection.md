Name: Sophia Dai

Helped by TA

What worked, what didn't, what advice would you give someone taking this course in the future?
At first, it was confused to understand what we should do to make the code complete. It was helpful to look 
ICMPtraceroute file while doing the ICMPpinger, I found they are sort of complementary. 
ICMPtraceroute.py helped me get a better understand of ICMP and what the two files are doing. But at first,
it was hard to get started. 
My advice is before start coding, take a look of the whole files and get a basic 
understanding of what they are doing and ask for help if you need. 




Test your `ping` and `traceroute` programs on 4 target hosts, each on a different continent and include the output below.

# **ping**

host1: www.free.fr, which is in Europe. 
Output:
Pinging 212.27.48.10 using Python:

0.08476805686950684
0.08411812782287598
0.14214515686035156
0.08411502838134766
0.08758902549743652


host2: www.google.com, which is in North America. 
Output:
Pinging 142.250.80.110 using Python:

0.015174150466918945
0.05543804168701172
0.01711893081665039
0.04798626899719238
0.04814600944519043

host3: www.baidu.com, which is in Asia. 
Output:
Pinging 39.156.66.10 using Python:

0.29118990898132324
0.2739372253417969
0.3367500305175781
0.2607457637786865
0.2620422840118408

host4: caliente.mx, which is in South America
Pinging 104.18.14.140 using Python:

0.23194503784179688
0.016995668411254883
0.04985213279724121
0.04622483253479004
0.04984903335571289


# **traceroute**
host1: www.google.com, which is in North America. 
Output:
 1 rtt=3 ms 131.229.237.254
 2 rtt=34 ms 131.229.11.105
 3 rtt=19 ms 131.229.10.104
 4 rtt=2 ms 134.241.249.33
 5 rtt=3 ms 69.16.1.33
 6 rtt=3 ms 18.2.136.89
 7 rtt=15 ms 192.5.89.46
 8 rtt=13 ms 18.2.145.18
 9 rtt=14 ms 108.170.248.97
 10 rtt=13 ms 142.251.65.115
 11 rtt=16 ms 142.250.80.110

host2: www.baidu.com, which is in Asia. 
Output:
1 rtt=15 ms 131.229.237.254
 2 rtt=26 ms 131.229.11.105
 3 rtt=17 ms 131.229.10.104
 4 rtt=2 ms 134.241.249.33
 5 rtt=2 ms 69.16.1.33
 6 rtt=6 ms 69.16.0.9
 7 rtt=6 ms 38.104.218.13
 8 rtt=8 ms 154.54.82.57
 9 rtt=20 ms 154.54.29.173
 10 rtt=26 ms 154.54.7.129
 11 rtt=38 ms 154.54.44.169
 12 rtt=49 ms 154.54.31.89
 13 rtt=59 ms 154.54.42.97
 14 rtt=74 ms 154.54.44.141
 15 rtt=76 ms 154.54.43.14
 16 rtt=78 ms 38.142.244.250
 17 rtt=209 ms 219.158.97.181
 18 rtt=298 ms 219.158.113.138
 * * * Request timed out.
 * * * Request timed out.
 20 rtt=345 ms 219.158.23.34
 21 rtt=601 ms 110.242.66.166
 * * * Request timed out.
 * * * Request timed out.
 * * * Request timed out.

host3:www.free.fr, which is in Europe
output:
 1 rtt=2 ms 131.229.237.254
 2 rtt=7 ms 131.229.11.105
 3 rtt=23 ms 131.229.10.104
 4 rtt=3 ms 134.241.249.33
 5 rtt=2 ms 69.16.1.33
 6 rtt=6 ms 69.16.0.9
 7 rtt=7 ms 38.104.218.13
 8 rtt=10 ms 154.54.82.57
 9 rtt=13 ms 154.54.41.62
 10 rtt=84 ms 154.54.27.170
 11 rtt=84 ms 149.11.204.10
 12 rtt=85 ms 78.254.254.166
 13 rtt=84 ms 194.149.161.246
 14 rtt=86 ms 212.27.48.10

host4:www.caliente.mx, which is in south America
output
 1 rtt=12 ms 131.229.237.254
 2 rtt=16 ms 131.229.11.105
 3 rtt=14 ms 131.229.10.104
 4 rtt=2 ms 134.241.249.33
 5 rtt=2 ms 69.16.1.33
 6 rtt=3 ms 18.2.136.89
 7 rtt=5 ms 192.5.89.57
 8 rtt=7 ms 206.53.143.9
 9 rtt=7 ms 104.18.15.140

