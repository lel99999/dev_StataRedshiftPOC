# dev_StataRedshiftPOC
Development for Connecting Stata to Redshift via ODBC

##### ODBC Insatall
```
$sudo yum install -y unixODBC*.x86_64

Verify the directory location of odbc.ini and odbcinst.ini (/etc)
$odbcinst -j
```

##### Download and Install Redshitf ODBC Driver
[https://s3.amazonaws.com/redshift-downloads/drivers/odbc/1.4.20.1001/AmazonRedshiftODBC-64-bit-1.4.20.1001-1.x86_64.rpm](https://s3.amazonaws.com/redshift-downloads/drivers/odbc/1.4.20.1001/AmazonRedshiftODBC-64-bit-1.4.20.1001-1.x86_64.rpm) <br/>

```
$sudo yum install -y AmazonRedshiftODBC-64-bit-1.4.20.1001-1.x86_64.rpm
```

