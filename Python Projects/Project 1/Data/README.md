The data here needs to be restored inside PostgreSQL:

3. Open pgAdmin 4 and connect to your PostgreSQL server.
4. Right-click Databases → Create → Database..., and name it dvdrental.
5. Right-click your new dvdrental database → Restore....
6. In the Filename field, select dvdrental.tar.
7. Set Format to Custom or Tar.
8. Click Restore and wait for the success message.
9. Refresh the database and check that all 15 tables are visible under Schemas → public
→ Tables.
