### **Member 3: Dewni - Customer & Branch Management Module**

**Files to create/modify:**
- `app/api/customer_branch_routes.py`
- `app/repositories/customer_branch_repo.py`
- `app/services/customer_branch_service.py`
- `app/schemas/customer_branch_schema.py`

**SQL Functions needed:**
```sql
-- Create new customer
-- Update customer details
-- Get customer by NIC
-- Get all customers
-- Get customer's account details
-- Get all branches
-- Create new branch
-- Update branch details
-- Get branch details with employee count
```

**API Routes to implement:**
- POST `/customers` - Create customer
- PUT `/customers/{customer_id}` - Update customer details
- GET `/customers/{nic}` - Get customer by NIC
- GET `/customers` - Get all customers
- GET `/customers/{customer_id}/accounts` - Get customer's accounts
- GET `/branches` - Get all branches
- POST `/branches` - Create branch
- PUT `/branches/{branch_id}` - Update branch

---
