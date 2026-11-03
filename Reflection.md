#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
Created on Tue Nov  3 15:39:59 2026

@author: manonkling
"""

REST-GUI-API Project Reflection

Developing this project helped me better understand how a graphical user interface (GUI) communicates with a RESTful API using Python. I used Tkinter to create a purchase form that collects product information, customer details, pricing, and purchase type. The application validates user input, converts it to JSON, and sends it via an HTTP POST request to a Flask API.

One of the greatest challenges was configuring my Python environment and connecting Spyder to its kernel. I was surprised by how much troubleshooting was involved before the application could run successfully. Initially, my code collected basic personal information, but I modified it to process purchases and enforce a $1,000 price limit.

Through this assignment, I gained a better understanding of input validation, JSON serialization, client-server communication, and API endpoints. Seeing the GUI successfully communicate with Flask helped connect the concepts covered in class to a functioning application. Moving forward, I would like to explore database integration and protected data handling.