public: yes
tags: [iPhone, proxy]

How to use check iPhone's http requests with Charles HTTP proxy on Mac
======================================================================

You need:

- `Charles`_ HTTP proxy

- An iPhone

- A Mac

First, setup your mac to share internet connexion throug Wifi.

- In ``System preferences > Sharing``

- Under "Internet Sharing" option, setup ``Share your connection from``
  **Ethernet** ``to computers using:`` **Airport**

- Check ``Internet Sharing`` checkbox

- In ``System preferences > Network``

- Get your Airport's network name

Then launch Charles.

End, with your iPhone:

- ``Settings > Wi-Fi``

- Choose your mac's network, and tap the blue arrow on the right

- Go down and tap: ``HTTP Proxy > Manual``

- Set ``Port`` to **8888**

Charles should display a warning asking authorization for your iPhone to
connect.

And that's it!

You can change the proxy port of Charles in ``Proxy > Proxy settings...``.

.. _Charles: http://www.charlesproxy.com/
