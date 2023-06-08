# Servidor d'actualitzacions
# Fes un repositori local amb Ubuntu.
- Començem fent un ip a al servidor per a saber la IP, ja que la necessitarem després:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/39f22d74-03d3-41c7-b7c5-172859fa718d)

- Ara instalem el apache2 i apt-mirror

![imatge](https://github.com/JoelIgle/m1/assets/114901284/b7e37e23-4913-463d-9af8-b55f230262ec)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/c93e7d33-45c4-4188-ae1f-30b4c3c3b509)

- Entrem dins de etc/apt/mirror.list I comentem els altres per a agilitzar el procés

![imatge](https://github.com/JoelIgle/m1/assets/114901284/3dd718a6-0a16-42b7-b0ba-4f5424fe9e0f)

- Amb apt mirror ho descarreguem:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/a5e353b1-b7ba-476a-8b81-8ea61da38c1c)

- Ens movem de carpetes i posem aixo:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/95494ed4-5fcb-4567-a87d-6ed7921fb773)

- Ara anem al ***CLIENT*** I posem la següent comanda

![imatge](https://github.com/JoelIgle/m1/assets/114901284/5a00e2de-418d-4724-83bf-109b694712f7)

- Anem al mateix fitxer que abans I posem el mateix, pero posant la IP del servidor:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/b71a6081-b5d2-4fc6-9732-91ccac9fb7c2)

- Ara ja fem el apt update i install:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/3f25e698-48d3-4e96-b22b-d8fa8b01ed84)

Com podem veure aqui ens surt el repositori del **server** 

![imatge](https://github.com/JoelIgle/m1/assets/114901284/a169ed4f-f5e8-40e4-9b06-cfc7511d8688)

I aqui igual, aquesta:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/a50920e1-5603-4b36-bdbf-bad8d99edcaa)

- Podem veure que ha funcionat perque al client sens ha instal·lat el Chrome, I podem executar-lo

![imatge](https://github.com/JoelIgle/m1/assets/114901284/b4f11eda-4b67-4505-851b-f2a9c82ff3ce)

***He afegit les captures que faltaven, demostrant que al fer el update i install es feia del repositori, mostrant les ip, apart puc fer PING a aquella IP, es a dir al servidor:***

![imatge](https://github.com/JoelIgle/m1/assets/114901284/bf9fbd50-62f6-4009-aab0-4fdf8f95433d)

