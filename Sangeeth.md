
### **Sangeeth - Authentication & Authorization System**

**Files to create/modify:**
- `app/api/auth_advanced_routes.py`
- `app/api/role_management_routes.py`
- `app/repositories/auth_repo.py`
- `app/repositories/role_repo.py`
- `app/services/auth_service.py`
- `app/services/role_service.py`
- `app/middleware/role_middleware.py`
- `app/middleware/permission_middleware.py`
- `app/schemas/auth_schema.py`
- `app/schemas/role_schema.py`
- `app/core/security.py`
- `app/core/permissions.py`

**Advanced Features to implement:**

**Authentication System:**
```sql
-- Advanced login with activity logging
-- Password reset functionality
-- Session management
-- Multi-factor authentication setup
-- Login attempt tracking and lockout
-- Token refresh and revocation
-- Activity logging for security events
```

**Role-Based Access Control:**
```sql
-- Dynamic role assignment
-- Permission matrix management
-- Branch-based role restrictions
-- Hierarchical role inheritance
-- Role-based data filtering
-- Audit trail for role changes
```

**API Routes to implement:**
- POST `/auth/login` - Advanced login with role validation
- POST `/auth/refresh-token` - Token refresh mechanism
- POST `/auth/logout` - Secure logout with token invalidation
- POST `/auth/reset-password` - Password reset workflow
- GET `/auth/permissions` - Get user permissions
- POST `/roles/assign` - Assign roles to users
- GET `/roles/hierarchy` - Get role hierarchy
- POST `/roles/permissions/update` - Update role permissions
- GET `/audit/login-attempts` - Security audit logs
- POST `/auth/change-password` - Secure password change

**Advanced Middleware Functions:**
- JWT validation with role checking
- Branch-based access control
- Permission-based route protection
- Rate limiting for auth endpoints
- Activity logging middleware
- Session management
- Multi-tenant branch isolation

---
