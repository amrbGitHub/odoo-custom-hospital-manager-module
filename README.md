# odoo-custom-hospital-manager-module
This is a custom module I made using the Odoo framework.
This module was something I made during my internship, it utilizes a multitude of Odoo Python functionality that were readily availble to me through the community edition of Odoo V18 and Odoo PostgreSQL ORM.

Features: 
- CRUD operations for classes such as Doctor, Appointments, Patient, Customer Tickets
- IMAP protocol for recieving emails outside of the Odoo module and parse them into a ticket format as well as providing a ticket number and adding the name and email of the sender as a new patient
- SMTP protocol for sending automated messages to patients who have created a new appointment with a doctor.

You can download this module as a zip folder, extract it, then add it to your current odoo branch.
