# API Endpoint Reference

This file documents the recommended backend endpoints for the Resource Management system.

## Dashboard
- `GET /api/dashboard`

## Authentication
- `POST /api/auth/login`
- `POST /api/auth/register`
- `POST /api/auth/verify`
- `POST /api/auth/forgot-password`
- `POST /api/auth/reset-password`

## Inventory
- `GET /api/inventory?subtype=assets`

## Assets
- `GET /api/assets?category={category}&subtype={subtype}&page={page}`
- `POST /api/assets`
- `PUT /api/assets/:id`
- `DELETE /api/assets/:id`

## Accessories
- `GET /api/accessories?category={category}&page={page}`

## Components
- `GET /api/components?category={category}&page={page}`

## Consumables
- `GET /api/consumables?category={category}&page={page}`

## Verification
- `GET /api/verify?page={page}`
- `POST /api/verify`

## Facilities
- `GET /api/Facilities`

## Alerts
- `GET /api/alerts`
- `POST /api/alerts`

## Settings
- `GET /api/settings/categories`
- `GET /api/settings/device-types`
- `GET /api/settings/users`
- `GET /api/settings/suppliers`
- `PUT /api/settings/:section`

## Account Settings
- `GET /api/account-settings`
- `PUT /api/account-settings`

## Profile
- `GET /api/profile`
- `PUT /api/profile`

## Security
- `GET /api/security`
- `PUT /api/security`

## Maintenance
- `GET /api/maintenance/overview`
- `GET /api/maintenance/scheduled`
- `GET /api/maintenance/history`
- `GET /api/maintenance/requests`
- `POST /api/maintenance/requests`

## Analysis
- `GET /api/analysis/overview`
- `GET /api/analysis/utilization`
- `GET /api/analysis/depreciation`
- `GET /api/analysis/reports`
