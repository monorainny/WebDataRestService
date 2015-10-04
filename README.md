# WebDataRestService
Remote Data Restful API Service

- Multiple database connection  manage

- Restful API support
  - POST(create) / GET(read) / PUT(update) / DELETE(delete)
  - URL Sample : [URL Domain]/API/[database name]/[table name]

- Predefined query execute support
  - POST, GET : Query parameter support (QUERY_ID, QUERY_PARAM)
  - URL Sample : [URL Domain]/QUERY/[database name]/[QUERY ID]

- User query execute support
  - POST, GET : Query support (QUERY)
  - URL Sample : [URL Domain]/EXECUTE/[databasename]
  - URL Sample : [URL Domain]/UPDATE/[databasename]

- Response
  - Data Type : JSON, XML
  - Return code
    - 200 : OK
    - 201 : Created
    - 202 : Accepted
    - 301 : Moved Permanently
    - 400 : Bad Request
    - 401 : Unauthorized
    - 403 : Forbidden
    - 404 : Not Found
    - 405 : Method Not Allowed
    - 406 : Not Acceptable
    - 409 : Conflict
    - 500 : Internal Server Error
    - 503 : Service Unavailable

# Required
- pip install lxml
- pip install SQLAlchemy
