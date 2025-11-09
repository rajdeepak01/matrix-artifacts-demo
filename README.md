# Matrix Build with Artifacts (88cb432)

This repository demonstrates a GitHub Actions **matrix build** workflow with artifact management.  
Each matrix variant runs in parallel and generates a unique artifact uploaded to the workflow run page.

## 📦 Workflow Details
- **Matrix Strategy:** Node.js versions 14, 16, and 18  
- **Parallel Execution:** All three variants run concurrently  
- **Artifacts:** Each job uploads an artifact named `build-88cb432-node<version>`  
- **Step Identifier:** Contains `matrix-88cb432` in the workflow  
- **Location:** `.github/workflows/matrix-build.yml`

## ✅ Validation Checklist
- [x] At least 3 matrix jobs run successfully  
- [x] Each job uploads a non-empty artifact  
- [x] Workflow includes `matrix-88cb432`  
- [x] README includes my email address  

---

**Author Email:** 22f2001354@ds.study.iitm.ac.in
