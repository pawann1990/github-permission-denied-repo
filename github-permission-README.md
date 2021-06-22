git Permission denied

# git@github.com: Permission denied (public key).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

open terminal cmd:

Pawan@DESKTOP-1VRSM3C MINGW64 ~
$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Pawan/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/Pawan/.ssh/id_rsa
Your public key has been saved in /c/Users/Pawan/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:QgpDf18CJC9/A+T09XE8FP+RXcQtIIsn2pHNijsTJ4w Pawan@DESKTOP-1VRSM3C
The key's randomart image is:
+---[RSA 3072]----+
|  . ..=   o o++++|
| . . * o * + o+.*|
|  o o * B * .  =o|
|   o O * B      o|
|    E O S       .|
|       B .       |
|      +          |
|       o         |
|                 |
+----[SHA256]-----+

Terminal cmd :: 
Pawan@DESKTOP-1VRSM3C MINGW64 ~
$ cat /c/Users/Pawan/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDdvhwc4w2DPA026bV+lhARQCUf81qOcTnW8ge3k2qLyta5fdtOYvyZe84L0xsPkASh8OSoP1y8BZSGu0R0gdahBcC3ZG/bZCbWctG8EQlfuQR8lCi+zwzSOn0pdRwIY0BFy4zI/NQkwio6a3nXrgQljw2OJOH8DDNW1TR2ElNeRLcqGZ9DyE543lmrYQ7ldTbSvKUhSpulXUi2dZXGRVoQBaZOnY2WWC1dHMFKnvuieRuPkexc1GjRvhcB/WP2yk8/YaBPAXzm9pR59v0y19WuJ7AYCkkXny6BQfHpTtiXZpJ39x/0X2k6v9xsdyYgoExmpQyjkfZ6ehpaSur51z501h3eKdDXKxpdIxDtHbHnXHfZhIayskAYO2Dy3ecH06zgt4vupu6IBTERlu1d4co4pnrrgBauRjXJ8hn5eZS8wSUVZlK3OIIBYfu6eD9RGzSIYZ4yNXwqXE2ZnoDUhuXBBsj6b/N0ESseS55uaer2Ps7D6v8CVd6cB7OTxICnKV0= Pawan@DESKTOP-1VRSM3C


open github account go to setting >> SSH and GPS keys >> add new key >> give name and paste 
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDdvhwc4w2DPA026bV+lhARQCUf81qOcTnW8ge3k2qLyta5fdtOYvyZe84L0xsPkASh8OSoP1y8BZSGu0R0gdahBcC3ZG/bZCbWctG8EQlfuQR8lCi+zwzSOn0pdRwIY0BFy4zI/NQkwio6a3nXrgQljw2OJOH8DDNW1TR2ElNeRLcqGZ9DyE543lmrYQ7ldTbSvKUhSpulXUi2dZXGRVoQBaZOnY2WWC1dHMFKnvuieRuPkexc1GjRvhcB/WP2yk8/YaBPAXzm9pR59v0y19WuJ7AYCkkXny6BQfHpTtiXZpJ39x/0X2k6v9xsdyYgoExmpQyjkfZ6ehpaSur51z501h3eKdDXKxpdIxDtHbHnXHfZhIayskAYO2Dy3ecH06zgt4vupu6IBTERlu1d4co4pnrrgBauRjXJ8hn5eZS8wSUVZlK3OIIBYfu6eD9RGzSIYZ4yNXwqXE2ZnoDUhuXBBsj6b/N0ESseS55uaer2Ps7D6v8CVd6cB7OTxICnKV0= Pawan@DESKTOP-1VRSM3C


