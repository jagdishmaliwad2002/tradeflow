# TradeFlow – Import & Export Management

A lightweight, single-file web app for managing import and export business operations, including container shipments from one country to another.

**Created by [Mahisagarsoft](https://github.com/mahisagarsoft)**

## Features

- **Dashboard:** active shipments, containers on the move, total value, imports vs. exports, pending documents, shipments by status, containers by country route, and a "needs attention" list.
- **Shipments:** add, search, filter, and delete shipments. Update status (Booked, In transit, At customs, Delivered, Delayed).
- **Container tracking:** origin and destination country and port, container type (20ft/40ft standard, high cube, reefer), number of containers, and container number.
- **Document checklist:** commercial invoice, packing list, bill of lading, certificate of origin, and customs declaration for each shipment.
- **Partners:** manage suppliers and buyers, with shipment counts and total value per partner.
- **Light and dark mode:** follows the device setting.

## Getting started

No build step or dependencies are needed.

1. Download `index.html`.
2. Open it in any modern browser, or upload it to any static host (GitHub Pages, Netlify, Vercel, etc.).

## Notes

- The sample data is placeholder. Data is kept in memory only, so a page refresh resets everything.
- To make it production-ready, connect it to a database or backend API to save shipments and partners.

## Roadmap ideas

- Persistent storage
- Freight cost per container
- Tracking timeline (loaded, sailed, arrived, cleared)
- Customs duty calculator by country
- Invoice generation

## Credits

Built by **Mahisagarsoft**.

## License

All rights reserved by Mahisagarsoft unless a license is added.
