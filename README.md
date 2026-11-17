\# Mobile Phone Inventory and Warehouse Management System



An academic project implementing smartphone inventory and warehouse operations using \*\*ERPNext v16\*\*.



\## Project Overview



This project demonstrates how ERPNext can manage smartphone procurement, inventory storage, warehouse transfers, customer orders, sales, and device-level serial number traceability.



\## Technology Stack



\- ERPNext v16

\- Frappe Framework v16

\- Docker and Docker Compose

\- MariaDB 11.8

\- Redis

\- Windows with Docker Desktop and WSL 2



\## Key Features



\- Smartphone item and product master management

\- Supplier and customer management

\- Purchase Orders and Purchase Receipts

\- Multiple warehouse management

\- Inter-warehouse stock transfers

\- Sales Orders, Delivery Notes and Sales Invoices

\- Stock Reconciliation

\- Serial number tracking for selected smartphones

\- Serial and Batch Bundle traceability

\- Configured 365-day manufacturer warranty

\- Stock Balance and Stock Ledger reporting

\- General Ledger integration



\## Demonstration Data



The system includes two smartphone inventory models:



\- \*\*PH-001:\*\* Conventional smartphone inventory.

\- \*\*PH-5G-001:\*\* Serialized smartphone inventory with synthetic demonstration identifiers.



All synthetic serial identifiers are for academic demonstration only and are not real device IMEIs.



\## Project Documentation



\- `ERPNext\_Inventory\_Warehouse\_Operations\_Project\_Report.pdf` — Final project report.

\- `ERPNext\_Inventory\_Warehouse\_Operations\_Project\_Report.md` — Markdown version of the report.



\## Deployment



The application was deployed using Docker Desktop and Docker Compose.



The ERPNext instance was accessed locally at:



`http://localhost:8080`



Deployment instructions and configuration will be documented separately.



\## Important Notes



\- This repository contains project documentation and deployment materials, not a database backup.

\- ERPNext transaction data is stored in the Docker-managed database.

\- Demonstration GST values are academic simulation data and are not a declaration of tax compliance.

\- The warranty period is a configured demonstration value.



\## Project Status



Academic implementation and demonstration project.



\## License



This project uses ERPNext and Frappe Docker. Refer to their respective licenses for the underlying software.



