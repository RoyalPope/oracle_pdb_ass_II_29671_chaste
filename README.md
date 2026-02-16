# Oracle Pluggable Database Assignment II  
## Database Development with PL/SQL (INSY 8311)

---

## 👤 Student Information
- **Name:** CYUSA Chaste 
- **Student ID:** 29671
- **Course:** INSY 8311 – Database Development with PL/SQL  
- **Instructor:** Eric Maniraguha  

---

## 🖥 Oracle Environment
- **Oracle Database Version:** 21c Enterprise Edition  
- **Architecture:** Multitenant (CDB + PDB)  
- **Primary Container:** CDB$ROOT  
- **Tools Used:**
  - Oracle SQL Developer
  - CMD
  - Oracle Enterprise Manager Express (EM Express)
- **Operating System:** Windows  

---

## 📌 Assignment Objective

This assignment demonstrates practical knowledge of Oracle 21c Multitenant Architecture, specifically:

- Creation and management of Pluggable Databases (PDBs)
- Switching between containers
- Creating local users inside a PDB
- Controlled deletion of a PDB including its datafiles
- Administrative monitoring using EM Express
- Structured technical documentation via GitHub

---

# ✅ Task 1: Creation of Main Pluggable Database

### 🔹 PDB Name
`ch_pdb_29671`

### 🔹 PDB Administrator
`pdbadmin`

### 🔹 Local Application User
`chaste_plsqlauca_29671`

### 🔹 Implementation Summary

1. Connected to the Container Database (CDB) as SYS with administrative privileges.
2. Confirmed the active container was CDB$ROOT.
3. Created a new Pluggable Database using the required naming convention.
4. Opened the PDB and verified its status.
5. Switched the session to the newly created PDB.
6. Created a local user inside the PDB.
7. Granted appropriate roles to the user.
8. Verified successful user creation.

📸 **Evidence Provided:**
- `01_pdb_creation_command.png`
- `02_pdb_open_status.png`
- `03_session_set_container.png`
- `04_user_created_inside_pdb.png`

---

# ✅ Task 2: Temporary PDB Creation and Deletion

### 🔹 Temporary PDB Name
`ch_to_delete_pdb_29671`

### 🔹 Implementation Summary

1. Created a temporary Pluggable Database.
2. Opened and verified its existence.
3. Closed the temporary PDB properly.
4. Dropped the PDB including all associated datafiles.
5. Confirmed the PDB was completely removed from the system.

📸 **Evidence Provided:**
- `05_temp_pdb_created.png`
- `06_temp_pdb_closed.png`
- `07_temp_pdb_deleted.png`

---

# ✅ Task 3: Oracle Enterprise Manager Express (21c)

Oracle Database 21c uses Oracle Enterprise Manager Express (EM Express) for database administration.

### 🔹 Access Method
`https://localhost:5500/em`

### 🔹 Verification Performed

- Successfully accessed EM Express via browser.
- Logged in with administrative privileges.
- Verified database instance status.
- Confirmed visibility of the created PDB.
- Confirmed access to the administrative dashboard.

📸 **Evidence Provided:**
- `08_oem_dashboard.png`

---

# 📂 Repository Structure
oracle_pdb_ass_II_29671_chaste
│
├── README.md
└── Screenshots/
├── 1_pdb_creation.png
├── 2_pdb_open.png
├── 3_user_created.png
├── 4_session_set_container.png
├── 5_tempdb_create.png
├── 6_tempdb_close.png
├── 7_tempdb_delete.png
└── 8_oem_dashboard.png


---

## 🔐 Integrity Declaration

I confirm that this assignment was completed independently using Oracle Database 21c. All screenshots reflect my personal execution of the required tasks.

