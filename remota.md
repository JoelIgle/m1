# Administració remota 
## Escriptori remot

- Habilito l’escriptori remot del server

![imatge](https://github.com/JoelIgle/m1/assets/114901284/e1fbab2e-02aa-4a4b-b884-d8a720e70d43)

- Agrego un usuari de domini

![imatge](https://github.com/JoelIgle/m1/assets/114901284/184c0a92-c09d-4094-a231-b2f61abd820f)

- I li dono el nivell **Administrador**

![imatge](https://github.com/JoelIgle/m1/assets/114901284/98544ef6-8bbb-4548-b754-1bc2176e48fe)

- Vaig al client en este usuari i entro en escritori remot, posant la ip, credencials...

![imatge](https://github.com/JoelIgle/m1/assets/114901284/fc3cf4bf-f5fd-45e2-8723-46042d95714b)

- Si tot es correcte desde el client veiem el servidor, que es aquesta finestra. Dalt se veu que estem en *remot*

![imatge](https://github.com/JoelIgle/m1/assets/114901284/9a2babad-48c1-47bb-8e65-75b4fb8f63d1)

- Creo un client que formi part del domini

![imatge](https://github.com/JoelIgle/m1/assets/114901284/aae918ff-a0c6-45c4-82d3-71777171dbb5)

## Team Viewer
- Tant al client com al servidor fem aquesta instal·lació del *TeamViewer*

![imatge](https://github.com/JoelIgle/m1/assets/114901284/69550cc1-8d46-44fe-b4c0-1f55f6762da4)

- Ara anem al client i posem la ID del servidor(la tenim obrint el teamviewer al server)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/218e41fa-70bd-476e-a2b0-92bb63db4b84)

- I després la constrasenya

![imatge](https://github.com/JoelIgle/m1/assets/114901284/1f146f49-d7c0-4023-ac1c-7680ee38edd9)

- Un cop connectats tenim dos finestres diferents, al servidor i client:
- Al servidor, baix a la dreta:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/c355675e-5650-47f0-bf5b-827de0d304ef)

- I al client obviament veurem una finestra amb el servidor:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/17f58619-c5e3-4444-924b-4f4c1e384d8c)

## Administració remota Ubuntu 
 
El que he fet es instal·lar el *tightvncserver* al servidor, i al client el *VNC Viewer*, per a poder veure el servidor des de el client

- Per a començar la instal·lació al **servidor** faig un update

![imatge](https://github.com/JoelIgle/m1/assets/114901284/45045d12-97bf-499d-a3a7-05fe851ec318)

- Després instal·lo el *tightvncserver*

![imatge](https://github.com/JoelIgle/m1/assets/114901284/a69b9a89-2ef6-4d3e-82ee-040e11606cb4)

- Aquesta comanda es per a posar contrasenya:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/c95464b2-0276-4986-bfc4-29bc49be8d40)

- I executem el vncserver:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/1143f171-2b34-48ff-b21b-48046ed7bc3f)

- El deixem obert i anem al *client* per a instal·lar l'altra part, el VNC Viewer

![imatge](https://github.com/JoelIgle/m1/assets/114901284/10b6f01f-9dfd-450b-b3ff-da72cc16a349)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/b0203d20-25c7-4e7c-b5f1-8ff91163c795)

- Un cop instal·lada posem la IP del server i 5901 (aquest número ens el dona el servidor quan executem):

![imatge](https://github.com/JoelIgle/m1/assets/114901284/d55176cc-445a-4573-a980-8c2cfc3c263e)

- Ens demanarà la contrasenya que abans hem posat al Server, com se pot veure en demana **Aqutentíquese en VNC Server**, que es la part instal·lada al servidor, no al client

![imatge](https://github.com/JoelIgle/m1/assets/114901284/f9bcb446-3619-4202-a8ef-7e486c9a22d6)

- Ens surt la finestra, visualitzanr el client, però al ser màquines virtuals no ho enén bé i surt en gris. Però est

![imatge](https://github.com/JoelIgle/m1/assets/114901284/bbc007df-97dd-4dda-8c7c-f861f21bef5b)


