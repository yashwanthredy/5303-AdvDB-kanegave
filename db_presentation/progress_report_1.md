## Progress Report - 1

### DB: POSTGRESQL

### Group:
- SRINIVAS KANEGAVE
- RITU RAJ
- YASHWANTH REDDY
- KIRAN REDDY KANCHARLA
- STEVE KUNDERT

### Server Information:

- Server Ip address: 67.205.132.214
- User: griffin
- Password: 2D2016!!!

### Instructions:

## 1. \c testdb;
```
postgres=# \c testdb;
You are now connected to database "testdb" as user "postgres".
```
## 2. \d projectgroup;
```
 Table "public.projectgroup"
   Column    |     Type      | Modifiers
-------------+---------------+-----------
 name        | character(25) |
 mustangid   | character(9)  | not null
 phonenumber | numeric(10,0) |
 email       | character(30) |
Indexes:
    "projectgroup_pkey" PRIMARY KEY, btree (mustangid)
```
## 3. select * from projectgroup;
```
           name            | mustangid | phonenumber |             email
---------------------------+-----------+-------------+--------------------------------
 SRINIVAS KANEGAVE         | M20223847 |  9409230346 | SRINU.DD2012@GMAIL.COM
 RITU RAJ                  | M20222819 |  9727651458 | RTRAJ88@GMAIL.COM
 YASHWANTH REDDY           | M20219871 |  9409230346 | YASHWANTH322@GMAIL.COM
 KIRAN REDDY               | M20227896 |  9409230343 | KIRAN.KANCHARLA@GMAIL.COM
 STEVE KUNDERT             | M20219801 |  9409230346 | member5@GMAIL.COM

```
