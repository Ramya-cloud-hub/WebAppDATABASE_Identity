# WebAppDATABASE_Identity
MVC IdentityASP.NET FundamentalsSystems Developer, .NETLexicon VäxjöIn this assignment, we will expand the earlier peoplelist to include a Content Management System (a CMS), that will let anauthorized user log into the page and edit the data in the database.Required Features:•Anyvisitor to the siteshould be able to register a user account, and once an account has been created, they should be able to: oView the list of people.oAddanew personto thepeoplelist.oEdit existing people.•User must fill in the following additional information about themselvesduring registrationto be saved in theiruser information:oFirstname & Lastname.oBirth date.•Once an account has been created, it should be possible to flag it as an admin. oAdmins should be able to do everythingnormal users can. oAdmins should be able toview,create, edit and delete people, cities, countries.•If you are not an admin, the City/Countrycontrollershould not be accessible, but they should be available as selectableoptionsin thepeople pages(Ex: Add person to city).Code Requirements:•Use ASP.NETCoreIdentity to manage roles and accounts.oMust create/use your own Models/Views/Controllers.•Authorization should be done through roles, whichare assigned to users.oMinimum of two roles are to be used.
