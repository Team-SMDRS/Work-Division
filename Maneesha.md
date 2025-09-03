
### **Member 1: Maneesha - Account Management Module**

**Files to create/modify:**
- `app/api/account_management_routes.py`
- `app/repositories/account_management_repo.py` 
- `app/services/account_management_service.py`
- `app/schemas/account_management_schema.py`

**SQL Functions needed:**
```sql
-- Get all accounts with customer details
-- Get account balance by account number
-- Get account owner details by account number
-- Create new savings account
-- Update account details
-- Get accounts by branch
-- Get customer's all accounts by NIC
```

**API Routes to implement:**
- GET `/accounts` - Get all accounts
- GET `/accounts/{account_no}/balance` - Get account balance
- GET `/accounts/{account_no}/owner` - Get account owner details
- POST `/accounts/create` - Create new account
- PUT `/accounts/{account_no}` - Update account details
- GET `/accounts/branch/{branch_id}` - Get accounts by branch

---
