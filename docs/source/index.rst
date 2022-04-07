**EduForAll** - Solving the Education Accessibilty.
===================================


*A Proposal for the Community Development Project.*

*About*:
Since the advent of the internet, free high-quality education is now in abundance, although a vast majority of people still struggle to have access to high-speed stable internet. This potentially hampers the growth of primarily rural students who have to resort to studying by the methods of days of Yore. This project aims to solve that problem.

**EduForAll** is a Django Web App built to be hosted completely offline - on a LAN network providing features of getting Study Resources, taking chapterwise Tests and maintaining a Forum for the students to ask and answer each others' doubts within the Network.



How to Host on the LAN:

- When you run the Server, use the following line: `python manage.py runserver <ipv4 address>:<port number>`
  - You may get your IPv4 address from Netowrks in your settings. Example: `192.168.0.107`. Make sure you're connected to a LAN network.
  - Port Number can be any number from `1024 to 65353`. We typically use `8000`.
- Your final code may therefore look something like - `python manage.py runserver 192.168.0.107:8000`. Unless you encounter a fire-wall, this would host EduForAll on your Local Server. Any device on the LAN can now access the website using the same URL you entered viz. `192.168.0.107:8000`.


Stack Used:
- **Backend** - Python, Django.
- **Database** - SQLite.
- **Frontend**- HTML, CSS, JS, jQuery, Bootstrap.

Do watch the Video for all the explanation, working and flow: https://youtu.be/us9VEqRAULI 




Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   features
   installation
   developers

