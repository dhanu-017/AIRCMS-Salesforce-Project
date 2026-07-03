# Salesforce Relationship & Field Creation

## 📌 Objective

The objective of this activity is to learn how to create custom fields and relationships in Salesforce using the Object Manager.

---

# Activity 1: Create a Picklist Field

## Goal

Create a custom **Picklist** field named **Experience Level** in the **Contact** object.

## Steps Performed

1. Navigate to **Setup**.
2. Open **Object Manager**.
3. Search for and select **Contact**.
4. Click **Fields & Relationships**.
5. Click **New**.
6. Select **Picklist** as the data type.
7. Click **Next**.
8. Enter the Field Label:

   ```
   Experience Level
   ```

9. Add the following picklist values:

   - Fresher
   - Mid-Level
   - Senior

10. Click **Next**.
11. Configure field-level security.
12. Add the field to the required page layouts.
13. Click **Save**.

---

## What I Learned

- A Picklist field restricts users to predefined values.
- It helps maintain consistent and accurate data.
- It reduces spelling mistakes and duplicate values.
- Picklists improve data quality and reporting.

---

# Activity 2: Create a Master-Detail Relationship

## Goal

Create a **Master-Detail Relationship** field for the **Candidate Application** object.

## Steps Performed

1. Navigate to **Setup**.
2. Open **Object Manager**.
3. Search for **Candidate Application**.
4. Open **Fields & Relationships**.
5. Click **New**.
6. Select **Master-Detail Relationship**.
7. Choose the parent object.
8. Enter the required field details.
9. Configure field-level security.
10. Add the field to the page layout.
11. Save the changes.

---

## What I Learned

A Master-Detail Relationship creates a strong parent-child relationship between two objects.

### Features

- Child records depend on the parent record.
- Ownership is inherited from the parent.
- Sharing settings are inherited.
- Deleting the parent automatically deletes all child records (Cascade Delete).
- Roll-Up Summary fields can be created on the parent object.

---

# Key Concepts Learned

- Salesforce Object Manager
- Custom Fields
- Picklist Fields
- Field-Level Security
- Page Layouts
- Master-Detail Relationship
- Parent-Child Relationship
- Cascade Delete
- Roll-Up Summary Fields

---

# Outcome

Successfully learned how to:

- Create a custom Picklist field.
- Configure predefined picklist values.
- Create a Master-Detail relationship.
- Understand how Salesforce maintains parent-child relationships.
- Improve data consistency using Picklists.
- Maintain data integrity using Master-Detail relationships.

---

# Salesforce Navigation

## Create Picklist Field

```
Setup
 └── Object Manager
      └── Contact
           └── Fields & Relationships
                └── New
                     └── Picklist
```

---

## Create Master-Detail Relationship

```
Setup
 └── Object Manager
      └── Candidate Application
           └── Fields & Relationships
                └── New
                     └── Master-Detail Relationship
```

---

# Conclusion

This activity provided hands-on experience with Salesforce customization by creating custom fields and object relationships. It demonstrated how Picklist fields improve data consistency and how Master-Detail Relationships enforce strong parent-child relationships while supporting features such as ownership inheritance, cascade delete, and roll-up summary fields.
