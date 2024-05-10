# Vendor Management System
---
Develop a Vendor Management System using Django and Django REST Framework. This
system will handle vendor profiles, track purchase orders, and calculate vendor performance
metrics.

# Usage
### Clone the repository
```
git clone https://github.com/aditi1145/VendorManagementSystem.git
```
### Install requirements
```
pip install -r requirements.txt
```
### Start Django at localhost:8000
```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

# Core Features
- Vendor Profile Management:
    API Endpoints:
      ● POST /api/vendors/: Create a new vendor.
      ● GET /api/vendors/: List all vendors.
      ● GET /api/vendors/{vendor_id}/: Retrieve a specific vendor's details.
      ● PUT /api/vendors/{vendor_id}/: Update a vendor's details.
      ● DELETE /api/vendors/{vendor_id}/: Delete a vendor.
- Purchase order tracking
    API Endpoints:
      ● POST /api/purchase_orders/: Create a purchase order.
      ● GET /api/purchase_orders/: List all purchase orders with an option to filter by vendor.
      ● GET /api/purchase_orders/{po_id}/: Retrieve details of a specific purchase order.
      ● PUT /api/purchase_orders/{po_id}/: Update a purchase order.
      ● DELETE /api/purchase_orders/{po_id}/: Delete a purchase order.
- Vendor Performance Evaluation
    API Endpoints:
      ● GET /api/vendors/{vendor_id}/performance: Retrieve a vendor's performance metrics.

# References
- https://github.com/ankitshaw09/Vendor_Management_System_with_Performance_Metrics_django/tree/main
- https://medium.com/@buddyminds/building-a-multi-vendor-django-ecommerce-site-a-step-by-step-guide-part-1-b94c3577a1b8
- https://github.com/Nareshnk1672/django-vendor-management

    
