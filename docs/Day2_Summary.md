# HISApp - Day 2 Summary

**Date:** 2025-04-06

---

## ✅ Tasks Completed:

### 1. Database Configuration
- Created `HISDbContext` for managing EF Core entities.
- Registered the DB context in `Program.cs` using:

```csharp
builder.Services.AddDbContext<HISDbContext>(options =>
    options.UseSqlServer(builder.Configuration.GetConnectionString("DefaultConnection")));

Add-Migration InitialCreate
Update-Database

2. Patient Model
Created Patient model with fields:

Id, Name, Age, Gender, Address

3. Patient Controller
Implemented CRUD endpoints:

GET /api/patient - Get all patients

GET /api/patient/{id} - Get patient by ID

POST /api/patient - Create new patient

PUT /api/patient/{id} - Full update

DELETE /api/patient/{id} - Delete patient

4. PATCH Endpoint for Partial Updates
Created UpdatePatientDto class to allow optional fields.

Added PATCH /api/patient/{id} endpoint:

Updates only the fields sent in the request body.

5. Swagger Testing
Successfully tested all endpoints via Swagger UI.

🔁 Git Commit
bash
Copy
Edit
git add .
git commit -m "✅ Day 2: Completed Patient API with PATCH support"
git push
🔮 Next Steps (Day 3)
Build React UI for:

Patient List View

Patient Create/Update Form

Integrate with API via Axios

Add client-side form validation

