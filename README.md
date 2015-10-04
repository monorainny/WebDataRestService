# WebDataRestService
Remote Data Restful API Service

- Multiple database connection  manage

- Restful API support
  - POST(create) / GET(read) / PUT(update) / DELETE(delete)
  - URL Sample : [URL Domain]/API/[database name]/[table name]

- Predefined query execute support
  - POST, GET : Query parameter support
  - URL Sample : [URL Domain]/QUERY/[database name]/[QUERY ID]

- User query execute support
  - POST, GET : Query support
  - URL Sample : [URL Domain]/EXECUTE/[databasename]


# Required
- pip install lxml
- pip install SQLAlchemy
