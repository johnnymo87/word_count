Hadoop setup guides:
* http://www.michael-noll.com/tutorials/running-hadoop-on-ubuntu-linux-single-node-cluster/
* http://www.drdobbs.com/database/pydoop-writing-hadoop-programs-in-python/240156473?pgno=1

Word count map reduce scripts:
* http://www.michael-noll.com/tutorials/writing-an-hadoop-mapreduce-program-in-python/
* https://github.com/glennklockwood/hpchadoop/tree/master/wordcount.py

Equivalent series of pipes in terminal:
`cat /home/hduser/data/ulysses | /home/hduser/scripts/mapper.py | sort -k1,1 | /home/hduser/scripts/reducer.py | sort -nrk2 | head -10`
