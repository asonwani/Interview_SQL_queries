# Interview_SQL_queries
SQL query repo

####################################
SQL#1: ROLLING 7 DAY ACTIVE USERS
####################################

INTERVIEW QUESTION
Table: events(user_id, event_ts, event_type)
For each calendar day d in the data, compute:
rolling_7d_active_users = distinct users with any event in [d-6, d] (inclusive)
Return:
* day
* rolling_7d_active_users
Notes:
* Output only days present in data

SOLUTION


####################################
