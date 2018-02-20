unbound_dict
=============

Serve other data from Unbound, like a dictionary or a thesaurus or any
other text data.


Features:
---------

* Run in your Unbound DNS server and serve data from a sqlite3 database.
* Allows queries from any client that can access your DNS.
* Portable across any host that has a DNS query command like drill or dig.
* Adds very little overhead to the server



Requirements:
-------------

* Unbound DNS server.
* Python 2.7
* Sqlite3
* Your dictionary, thesaurus, contacts db, etc., etc.



TODO:
-----

* Port to Unbound > 1.5.10 (may not need porting and may just work)
* Port to python 3.


https://github.com/romeojulietthotel/unbound_dict
