# BulkBazzar Admin Panel User Guide

This document explains how to use the BulkBazzar admin panel for daily operations.

## 1. Open Admin Panel

- Local URL: `http://88.223.92.232:3000/login.html`
- After login, dashboard opens at: `http://88.223.92.232:3000/dashboard.html`

## 2. Login

Use admin credentials:

- Email: `admin@bulkbazzar.com`
- Password: `Admin@123`

If login fails, verify backend server and database are running.

## 3. Main Admin Menu

Left sidebar pages:

- Dashboard
- Products
- Orders
- Users
- Categories
- Brands
- Inventory
- Reports
- Settings

## 4. Products Management

Page: `http://88.223.92.232:3000/admin/products.html`

Use this page to:

- Add product
- Edit product
- Enable/disable product
- Set category and brand
- Set price and discount
- Manage product image
- Manage product variants

### Product Variants (Important for bulk/pack sales)

While adding/editing product, use variant section to create:

- `Single`
- `Pack of 5`
- `Box of 10`
- Any custom variant

For each variant, configure:

- Variant code
- Variant name
- Unit multiplier
- Optional price override
- Default variant toggle

If `price override` is empty, system calculates variant price from base product price and multiplier.

## 5. Bulk Order Pricing (Global Discount)

Page: `http://88.223.92.232:3000/admin/settings.html`
Tab: `Shipping`

Set these fields:

- `Bulk Order Minimum Units`
- `Bulk Order Discount (%)`

How it works:

- System counts total units in cart (`quantity x variant multiplier`)
- If units reach minimum threshold, bulk discount is applied automatically
- Discount affects cart summary totals

## 6. Orders Management

Page: `http://88.223.92.232:3000/admin/orders.html`

You can:

- View all orders
- Search/filter orders
- Check payment status
- Update order status

## 7. Users Management

Page: `http://88.223.92.232:3000/admin/users.html`

You can:

- View registered users
- Check role and activity
- Manage user status

## 8. Categories and Brands

Pages:

- `http://88.223.92.232:3000/admin/categories.html`
- `http://88.223.92.232:3000/admin/brands.html`

Best practice:

- Create categories and brands first
- Then create products using those values

## 9. Inventory

Page: `http://88.223.92.232:3000/admin/inventory.html`

Use inventory page to monitor stock and update product quantities.

## 10. Settings

Page: `http://88.223.92.232:3000/admin/settings.html`

Sections available:

- General store details
- Payment settings
- Shipping settings
- Notification settings
- Security/password change

## 11. Recommended Admin Workflow

1. Configure store settings
2. Create categories and brands
3. Add products with variants and images
4. Set bulk order discount in Settings > Shipping
5. Verify products on web/mobile app
6. Manage incoming orders daily


## 13. Quick Links

- Login: `http://88.223.92.232:3000/login.html`
- Dashboard: `http://88.223.92.232:3000/dashboard.html`
- Products: `http://88.223.92.232:3000/admin/products.html`
- Orders: `http://88.223.92.232:3000/admin/orders.html`
- Settings: `http://88.223.92.232:3000/admin/settings.html`
