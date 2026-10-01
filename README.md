# PrettyCRM

**Open-source CRM for independent hair and makeup artists.**

PrettyCRM is a work-in-progress fork of [Frappe CRM](https://github.com/frappe/crm), being shaped for solo mobile hair and makeup artists in Hawaii. The goal is to connect client inquiries and bookings with the creative preparation that happens before an appointment. It is not yet a finished beauty-industry product.

## Product direction

The planned first build centers on **Look Studio**, an artist-controlled workspace connected to a client and booking:

- Reference images and notes about the client's preferences.
- Artist-selected color swatches and hairstyle plans.
- Products, shades, and application notes chosen by the artist.
- Trial feedback and an approved final look.
- A mobile-friendly day-of view and packing checklist.

These are planned features, not claims about functionality already available in this fork. The artist makes the final decisions on looks, palettes, and products. Any future AI features should be optional, minimal, and limited to administrative assistance such as drafting invoices or follow-ups for artist review.

## Current foundation

PrettyCRM currently retains Frappe CRM's lead, deal, contact, product, and task foundation, with a Frappe backend and Vue frontend. See the [upstream Frappe CRM repository](https://github.com/frappe/crm) and its [documentation](https://docs.frappe.io/crm) for information about the underlying application. Beauty-specific workflow and Look Studio development are still ahead.

## Business model

The software is intended to remain open source. Setup, hosting, maintenance, and support may be offered as paid services; customers are not being charged for a proprietary license to PrettyCRM.

## Development

This repository is an early-stage fork. Before deploying it for clients, review the upstream setup instructions, confirm the Frappe and frontend dependencies for the chosen version, and test your installation and backups. Contributions and feedback from working hair and makeup artists are welcome through GitHub issues.

## Attribution and license

PrettyCRM is based on [Frappe CRM by Frappe Technologies](https://github.com/frappe/crm). Credit and existing third-party notices should be preserved. This project follows the upstream GNU Affero General Public License v3.0; see [LICENSE](LICENSE). Dependency licenses remain their respective authors' licenses.
