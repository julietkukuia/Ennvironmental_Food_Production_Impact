🗓 Day 2 – Data Understanding & Preprocessing

Date: 2025-09-02

✅ Tasks Completed

Inspected dataset for missing values and duplicates.

Removed unnecessary rows (short dashes in product names).

Standardised IDs across all dimension tables.

Established model relationships (one-to-many joins across tables).

📊 Key Findings

Null values existed but were not imputed (to avoid excessive DAX complexity).

Food product duplicates removed incorrectly at first; resolved by de-duplicating on Food_ID only.

⚠️ Challenges & Fixes

Challenge	Fix
Removing duplicates erased non-identical products in the same group	Fixed by setting Food_ID as unique key

🔜 Next Steps

Define analytical questions using CRISP-DM.

📂 Files Updated / Created

PowerBI/environmental_dashboard.pbix (data model complete)

🧠 Key Learnings

Cleaning in Power Query should be minimal; leave calculations to DAX for flexibility.
