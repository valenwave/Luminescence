# Commit
If you don't commit, then your transaction will remain OPEN indefinitely - which you can see in sys.dm_tran_active_transactions / sys.dm_tran_database_transactions / sys.dm_tran_session_transactions or using DBCC OPENTRAN.

Also, what you have initiated is an explicit transaction, which should be explicitly ended with a COMMIT or ROLLBACK statement.

```sql
select * from sys.dm_tran_active_transactions order by transaction_begin_time desc
```

# Tells you the open transactions
```sql
select @@TRANCOUNT
```

## DBCC OPENTRAN
```sql
DBCC OPENTRAN
```

No open transactions
```
No active open transactions.
DBCC execution completed. If DBCC printed error messages, contact your system administrator.
```

If there are open active, it will give you the SPID. 

How to `kill SPID`? 

```sql
KILL {SPID}
KILL 84
```