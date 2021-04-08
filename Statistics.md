These are some (static) statistics of this index. The last calculation was in November 2018.

* Date of Creation
  * July 26th, 2014
* Quantity of lines
  * 4159
  * wc -l Home.md
* Quantity of topics
  * 1041
  * grep '^* ' Home.md | wc -l
* Quantity of entries
  * 3053
  * grep '^  \* ' Home.md | wc -l
  * grep '^    \* ' Home.md | wc -l
* Quantity of different entries
  * 1165
  * grep '^  \* ' Home.md | sort | uniq | wc -l
  * grep '^    \* ' Home.md | sort | uniq | wc -l 
* The most referenced entries are
  * 71 - DB2 System Command Examples. techs@work. Michael Dang, Sylvia Qi. 2009. Blog - http://techsatwork.com/blog/wp-content/uploads/2009/04/db2systemcommands.pdf
  * 38 - Compare the distributed DB2 10.5 database servers. DeveloperWorks. Amyris Rada and Roman Melnyk. 2015. Article - https://www.ibm.com/developerworks/data/library/techarticle/dm-1311db2compare/index.html
  * 20 - Data concurrency in DB2 deep dive. Vinay's DB2 blog. Vinay Bommana. 2016. Blog - http://vinaysdb2blog.blogspot.com.co/2016/08/data-concurrency-in-db2-deep-dive.html
  * grep '^  \* ' Home.md | sort | uniq -c | sort -n
* Entries per year.
  * 2018 - 207
  * 2017 - 361
  * 2016 - 538
  * 2015 - 94
  * 2014 - 119
  * 2013 - 92
  * 2012 - 106
  * 2011 - 31
  * 2010 - 315
  * 2009 - 126
  * 2008 - 56
  * 2007 - 25
  * 2006 - 18
  * 2005 - 13
  * 2004 - 4
  * grep '\. 20..' Home.md | awk -F. '{print $4}' | sort | uniq -c | sort -
* Quantity of sources
* The source with more entries
* The source with more different entries
* Quantity of different languages
  * 3 (English, Spanish, French)
* Quantity of curators
  * 1