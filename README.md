## Sourcing up OpenMRS empty database

Follow these steps to set up OpenMRS on your system:

1. **Copy Files:**
   - Transfer the `openmrs.war` file and modules to their respective directories.

2. **Database Setup:**
   ```bash
   mysql -uroot -p
   drop database openmrs;
   create database openmrs;
   source ~/openmrs.sql;
   exit;


