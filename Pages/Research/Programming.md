# Programming

## Code Smell

Examples

* Long methods
* Large classes
* Duplicate code
* Magic numbers

Bloaters

* Long Method
* Large Class
* Data Clumps

Couplers

* Long Parameter List
* Feature Envy
* God Class

Complexity Smells

* Switch Statements
* Nested Control Flow

Dispensables

* Dead Code
* Unused Variables

## Commit

SQL Commit

If you don't commit, then your transaction will remain OPEN indefinitely - which you can see in sys.dm_tran_active_transactions / sys.dm_tran_database_transactions / sys.dm_tran_session_transactions or using DBCC OPENTRAN.

Also, what you have initiated is an explicit transaction, which should be explicitly ended with a COMMIT or ROLLBACK statement.

```sql
select * from sys.dm_tran_active_transactions order by transaction_begin_time desc
```

## Tells you the open transactions

```sql
select @@TRANCOUNT
```

### DBCC OPENTRAN

```sql
DBCC OPENTRAN
```

No open transactions

```log
No active open transactions.
DBCC execution completed. If DBCC printed error messages, contact your system administrator.
```

If there are open active, it will give you the SPID.

How to `kill SPID`?

```sql
KILL {SPID}
KILL 84
```

## Visual Studio

Convert to uppercase: CTRL+SHIFT+U
Covnert to lowercase: CTRL+U
Duplicate line: CTRL+E, V
Select word: CTRL+W
Select word, make lowercase: CTRL+W, CTRL+U
