in order to get timestamp we cant use read sms and call logs permission in android anymore
we can just use broadcast receiver to take the timestamp by using gettimestampinmillis() function.
we can also use sms retriever to get the timestamp it is the alternative for read sms permission offered by google itself.
