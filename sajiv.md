### **Member 4: Sajiv - Fixed Deposit & Plans Management Module**

**Files to create/modify:**
- `app/api/fd_plans_routes.py`
- `app/repositories/fd_plans_repo.py`
- `app/services/fd_plans_service.py`
- `app/schemas/fd_plans_schema.py`

**SQL Functions needed:**
```sql
-- Create new FD account
-- Get FD details by account
-- Calculate FD maturity amount
-- Get all FD plans
-- Create/Update FD plans
-- Get all savings plans
-- Create/Update savings plans
-- Get FD reports by branch
```

**API Routes to implement:**
- POST `/fd/create` - Create fixed deposit
- GET `/fd/account/{account_no}` - Get FD details
- GET `/fd/maturity/{fd_id}` - Calculate maturity amount
- GET `/plans/fd` - Get all FD plans
- POST `/plans/fd` - Create FD plan
- GET `/plans/savings` - Get all savings plans
- POST `/plans/savings` - Create savings plan
- PUT `/plans/fd/{fd_plan_id}` - Update FD plan
