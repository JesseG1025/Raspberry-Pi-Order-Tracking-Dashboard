# Raspberry-Pi-Order-Tracking-Dashboard <br>

## Overview
This project aims to create a live order tracking system through the use of a Raspberry Pi and a Mac-hosted database. Allows office staff to view open orders, see how long they've been active, and mark them as "picked".<br>

* Orders are stored in a **SQLite database** on a Mac <br>
* Flask API (running on the Mac) makes the orders available over the local network <br>
* Flask web dashboard (runs on the Raspberry Pi) fetches the data and displays it with timers, a color-coded legend, and user controls. <br>

This allows for the real-time monitoring of orders from any web browser in the network.

