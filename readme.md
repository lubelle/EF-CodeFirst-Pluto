#entity framework 6.2.0
code first with NEW database
steps:
1. install-package EntityFramework -Version:x.x.x
2. create models(classes) in program.cs
3. create connectioString in App.config
4. tell EF the name of the connectioString in program.cs constructor: base("name=DefaultConnection")
5. PM> enable-migrations (only run once)
6. PM> add-migration InitialModel
7. PM> update-database
8. in SSMS, verify the new database just created

