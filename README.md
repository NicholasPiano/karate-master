karate-master
=============

A master-student model of small business web hosting.

This package consists of two django application frameworks. I have not yet decided which system they will run on. Some I am familiar with are:
1. Pythonanywhere
2. GAE
3. Heroku

The Sensei framework is the central hosting website. It manages the daughter applications that comprise the client websites hosted with Karate.
The Deshi framework is a general template for a client website that integrates with the Sensei instance. There will be one Sensei instance per host.

Sensei provides client (small business) facing frontend and stats utilities along with guides to using the website.
Deshi contains user-facing material and core custom functionality required by the client.
