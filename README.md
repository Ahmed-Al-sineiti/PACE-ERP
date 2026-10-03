# PACE ERP

**PACE** stands for **Parcel And Courier Enterprise**: an ERP for shipping and courier companies in Egypt.

**Repository:** https://github.com/Ahmed-Al-sineiti/PACE-ERP

## Project Overview

Parcel delivery companies in Egypt (like Bosta) move thousands of parcels a day between merchants, branches and customers. When the work is spread across spreadsheets, phone calls and separate tools, parcels get lost, branches don't know what they hold, and nobody can see where a shipment is right now.

PACE is a unified ERP that a shipping company runs its daily work on: one system that follows every parcel from the moment a merchant requests a pickup until it reaches the customer or returns to the merchant. It covers the merchant portal, pickup and delivery dispatch, the courier app, hub operations (receiving, sorting and transfers between branches), master data, finance, and a public tracking page where customers follow their shipments. All modules share one set of statuses, events, permissions and an audit log.

The final deliverable is a **working front-end prototype**: the real screens of each module, built in code and running on mock data, without a backend.

The system is built on a realistic network: one sorting center in Obour, 33 hubs across Egypt's 7 economic regions, and coverage of 344 official districts (qism/markaz) using official government codes.

## Team Members

| Name | Role / Module |
|---|---|
| Ahmed Mohamed Abdelsalam Alsineiti | **Team Leader** – Core + Operations (Hub Operations: receiving, sorting, transfers, inventory) |
| Ahlam Magdy Abdelmonem Taha | Merchant Portal |
| Bardis Mohamed Mohamed AbdelHamid | Operations (Pickup & Delivery Dispatch) + Customer Tracking |
| Arwa Osama Hamed Aboudeba | Courier App |
| Ahmed Mohammed Mohammed Alkady | Finance |
| Renad Abdelraheem Abdelhameed Kamel | Master Data |

## Instructor

Mohamed Kamar

## Project Objectives

1. Track every parcel end to end, from pickup request to delivery or return, with a clear status and event history at every step.
2. Give each user group (merchants, couriers, hub staff, dispatchers, finance, admins) the screens and permissions it needs, and nothing more.
3. Model a real hub-and-spoke delivery network for Egypt, with routing rules, delivery time estimates (SLA) and remote-area handling.
4. Keep data consistent across modules through shared master data, unified statuses and a full audit log.
5. Reduce lost parcels and delays by making custody clear: at any moment, one hub or one courier is responsible for each parcel.

## Project Scope

### In scope
- **Core:** parcel statuses, events, permissions, audit log and shared glossary.
- **Merchant Portal:** creating shipments, pickup requests, tracking and merchant reports.
- **Operations**, split into two parts:
  - **Hub Operations:** receiving and sorting at hubs, transfers between hubs, hub inventory.
  - **Pickup & Delivery Dispatch:** assigning pickup and delivery tasks to couriers.
- **Courier App:** pickup and delivery tasks, scanning and proof of delivery.
- **Customer Tracking:** a public web page where the customer enters a tracking number and follows the shipment status until delivery.
- **Master Data:** locations, areas, lanes and other shared reference data.
- **Finance:** cash on delivery (COD) collection, merchant settlements and fees.
- **Network design:** hubs, sorting center, coverage areas, lanes and delivery times.
- **Front-end prototype:** coded screens for every module, connected flows and mock data that behaves like the real system.

### Out of scope
- Backend, real database and APIs (the prototype runs on mock data).
- International shipping and customs.
- Warehousing and fulfillment for merchants.
- Fleet maintenance and HR / payroll.
- Integration with real payment gateways or real carrier APIs.

## Project Plan (5 Weeks)

| Week | Focus | Main deliverables |
|---|---|---|
| **1** | Research & foundations | Industry research (Bosta and similar companies), user groups, shared statuses and events, glossary, module boundaries |
| **2** | Information architecture & network | Delivery network (hubs, lanes, coverage, delivery times), master data structure, permissions, sitemap for each module |
| **3** | User flows & wireframes | End-to-end flows for each module (pickup, sorting, transfer, delivery, returns, settlements), exception handling, screen list per user group and wireframes |
| **4** | UI & front-end build | High-fidelity UI and design system, then building the screens in code with mock data |
| **5** | Front-end prototype & delivery | Completing and connecting all screens, testing the flows end to end, fixes, final documentation and presentation |
