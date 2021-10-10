in order to get timestamp we cant use read sms and call logs permission in android anymore
we can just use broadcast receiver to take the timestamp by using gettimestampinmillis() function.
we can also use sms retriever to get the timestamp it is the alternative for read sms permission offered by google itself.
its not possible to directly write data in broadcast receiver.
either you have to store it in shared preferences or in room database to store the data and later use it in saving
permissions like recieve sms is also not required while using broadcast
the permissions like read sms and call logs are the core permissions and are available in use only for old customers by google.
