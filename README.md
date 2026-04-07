# Procure-to-Project Execution Flow (End-to-End Supply Chain Process)

This document explains the complete lifecycle of material procurement and utilization in a manufacturing environment — from Purchase Requisition (PR) to Project Completion.

---

## Overview

This workflow demonstrates how different departments coordinate to:
- Procure materials
- Manage vendors
- Track logistics
- Ensure quality
- Execute manufacturing

---

## Process Flow

### 1. Department Requirement (PR)

Departments raise Purchase Requisition (PR) based on project needs.

| PR No  | Department   | Material   | Quantity | Project   |
|--------|-------------|------------|----------|-----------|
| PR1001 | Production  | Steel Rod  | 100 Kg   | Project A |
| PR1002 | Maintenance | Motor      | 2 Nos    | Project B |

---

### 2. Purchase Requisition Approval

- Manager reviews and approves requisitions.
- Only approved PRs proceed to procurement.

Approved:
- PR1001 for Project A  
- PR1002 for Project B  

---

### 3. Request for Quotation (RFQ)

RFQs are sent to vendors for pricing.

| Material   | Vendor        |
|------------|---------------|
| Steel Rod  | ABC Supplier  |
| Motor      | XYZ Pvt Ltd   |

---

### 4. Vendor Quotation Received

Vendors submit their quotations.

| Vendor        | Material   | Price        |
|---------------|-----------|--------------|
| ABC Supplier  | Steel Rod | ₹50 per Kg   |
| XYZ Pvt Ltd   | Motor     | ₹5000 per unit |

---

### 5. Vendor Selection (L1)

The lowest-cost vendor (L1) is selected.

- ABC Supplier selected for Steel Rod  
- XYZ Pvt Ltd selected for Motor  

---

### 6. Purchase Order (PO) Creation

Purchase Orders are created against approved PRs.

| PO No  | Material   | Project   |
|--------|-----------|-----------|
| PO2001 | Steel Rod | Project A |
| PO2002 | Motor     | Project B |

---

### 7. PO Approval and Dispatch

- Purchase Head approves the PO.
- Approved POs are sent to vendors.

---

### 8. Vendor Acceptance

Vendors confirm acceptance of the Purchase Order.

- PO2001 accepted by ABC Supplier  
- PO2002 accepted by XYZ Pvt Ltd  

---

### 9. Material Dispatch and ASN

Vendors dispatch the material and share Advance Shipment Notice (ASN).

| ASN No  | Details Included                    |
|---------|------------------------------------|
| ASN3001 | Vehicle, driver, dispatch details  |

---

### 10. Transportation

- Materials are transported via vendor logistics.
- Expected delivery time is 3 days.

---

### 11. Material Delivery

Materials are delivered to respective locations.

| Material   | Location           |
|-----------|-------------------|
| Steel Rod | Warehouse         |
| Motor     | Maintenance Store |

---

### 12. Gate Entry

Security records:
- Vehicle number  
- Driver details  
- Entry time  

---

### 13. GRN Creation (Goods Receipt Note)

GRN is created after successful receipt.

| GRN No  | Material   |
|---------|-----------|
| GRN4001 | Steel Rod |
| GRN4002 | Motor     |

---

### 14. Quality Inspection

Quality team inspects received materials.

- Steel Rod approved  
- Motor approved after inspection  

---

### 15. Inventory Update

- Stock is updated in the system (ERP/WMS)
- Bin locations are assigned

---

### 16. Material Issue to Project

Materials are issued based on project requirements.

| Material   | Project   |
|-----------|-----------|
| Steel Rod | Project A |
| Motor     | Project B |

---

### 17. Manufacturing Process

- Steel Rod used for machine frame fabrication  
- Motor installed during assembly  

---

### 18. Project Completion

- Final product assembled successfully  
- Ready for testing and dispatch  

---

## Systems Involved

- ERP System for PR, PO, and GRN tracking  
- WMS (Warehouse Management System) for inventory management  
- TMS (Transport Management System) for logistics tracking  

---

## Key Benefits

- End-to-end visibility across operations  
- Cost optimization through vendor selection  
- Improved inventory accuracy  
- Better vendor coordination  
- Efficient project execution  

---

## Conclusion

This structured procurement-to-production workflow ensures smooth coordination across departments, reduces delays, and improves operational efficiency in manufacturing environments.

---

## Author

Nagendra Arya  
Control Tower Operations and Data Analytics  
Mobile: +91-7309906413  
