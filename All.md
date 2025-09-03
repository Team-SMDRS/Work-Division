**What each member needs to do:**

1. **Create the repository file** - Write SQL functions using database connections
2. **Create the service file** - Call repository functions and handle business logic
3. **Create the schema file** - Define Pydantic models for request/response
4. **Create the routes file** - Define FastAPI endpoints that call services
5. **Write SQL functions** - Focus on database functions rather than complex Python logic

**Example structure each member should follow:**

```python
# Repository - Write SQL queries
def get_account_balance(account_no: str):
    query = "SELECT balance FROM account WHERE account_no = %s"
    # Execute query and return result

# Service - Business logic
def fetch_account_balance(account_no: str):
    # Call repository function
    # Add any business logic if needed
    return result

# Routes - API endpoints
@router.get("/accounts/{account_no}/balance")
def get_balance(account_no: str):
    # Call service function
    # Return response
```
