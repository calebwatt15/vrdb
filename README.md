# Vulnerability Reporting Database

This is an open-source, vulnerability reporting database. The idea is to have a standard database for pentesters and vulnerability assessors to be able to reference while writing reports. Most vendors have a standard descriptions for any given vulnerability, this is to make an open source version.

The idea is to take OWASP vulnerabilities (a good standard for Web App vulns), and add in vulns for other architectures (thick client, SAP, infrastructure, network, etc.)

The vrdb is written in JSON, so that data can easily be added and read from it in a variety of languages, but it remains human readable with just a text editor (unlike a SQL database.) If the database ever becomes too large and slow for JSON parsers, it may have to be switched over to SQL or something more efficient.
