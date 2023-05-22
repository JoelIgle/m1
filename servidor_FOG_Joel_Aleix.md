# Pràctica servidor FOG feta per **Aleix Oraà** i **Joel Iglesias**:

## Instal·lar i configurar un servidor FOG
- Primer ens baixem l'arxiu ***fogproject-1.5.10.tar.gz***:

 ![imatge](https://github.com/JoelIgle/m1/assets/114901284/89ee1930-bec1-41bc-969f-c500def8bfb4)

- El descomprimim:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/27c78f14-159b-419d-b310-190a466aa65d)

- Anem a la carpeta corresponent i executem el fitxer d'instal·lació ***installfog.sh***:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/de37b451-5962-40a7-af8f-7724d7760678)

- I procedim a la instal·lació:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/7bb875a4-04e9-4328-bbe5-7ef6896a4191)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/4581cc8e-430e-4405-abf6-10da84b6ef81)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/f755ccd5-5546-40e9-b7b2-881fd03e70c4)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/1bb20be4-a5d1-4a4b-8784-47c0d036fac6)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/8d0d5869-5a66-4762-aee5-d07d45473d7e)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/cb97ba64-459b-483b-96ad-f32fbc7cedce)

- Entrem a l'adreça i ens portarà a aquest lloc web per a fer la instal·lació:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/d4b39cdf-d8dc-4bb0-a33e-8ec5d8e1990a)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/82da6645-e07b-4376-a5b0-73245bd99d41)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/af3bb3ca-dffa-4a41-adbe-7a8b3b86bcee)


- Un cop feta la instal·lació tornem al terminal, per a continuar la instal·lació:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/9f8d0a31-9399-4b50-9c0e-06428f727541)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/1b902dce-4233-4994-9ae6-72116269c8de)


- Entrem a la web d'abans amb les credencials que ens han donat abans al terminal:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/e326875a-b51a-4e4c-ad5d-2c02081488d8)

- Com podem veure podem entrar correctament:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/8f1cb678-a629-4804-92c9-d60a6e540d74)


- Ara tenim que eliminar, instalar i configurar els paràmetres del nostre DNS, ho tenim que fer per a poder utilitzar la xarxa sense cap problema.

![imatge](https://github.com/JoelIgle/m1/assets/114901284/d80051af-3baa-4bfb-8940-5aec2bb76c8c)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/7c79c92f-7545-4c3f-9e42-509fcc00a673)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/d845b39f-ccf0-4a66-ab1c-146264f776b9)

- Aixó ho fem perquè en cas de tenir un servidor DHCP ja configurat, com pot ser el router de casa, en el moment d'iniciar els ordenadors per la red no ens trobarà el servidor FOG. 

![imatge](https://github.com/JoelIgle/m1/assets/114901284/2def4145-5135-4358-8b2c-ad0aa8f3cb27)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/af226a44-39ea-44b6-9f45-f3f9dd486f0d)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/c64aa995-79fb-4813-9197-eea345837832)

- Un cop fet aixó ja podrem començar en la **creació d'imatges**

## Capturar des del client un Windows

- Dins la web que hem entrat anteriorment anem a ***Images***

![imatge](https://github.com/JoelIgle/m1/assets/114901284/70fd60df-b205-4842-ac47-866d7c24e5f6)

- Ara a ***Create new image***

![imatge](https://github.com/JoelIgle/m1/assets/114901284/d80c9f1e-0298-4726-bbe6-ab918b29428f)

- I creem la imatge

![imatge](https://github.com/JoelIgle/m1/assets/114901284/ab4c43bb-22c0-4f64-b494-70c2ad2f2d9a)

## Capturar des del client un Ubuntu

- Fem el mateix, pero posem com a *operating system* un *Linux*

![imatge](https://github.com/JoelIgle/m1/assets/114901284/b62829fb-11ea-419d-a0ea-24e53ac404f2)

## Instal·lar imatge Windows
- Creem una màquina virtual que inicie desde la mateixa xarxa que el servidor i al ordre d'arrencada posem *xarxa* com a primera opció:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/f7e17e75-42e5-4714-a059-09eed41e65d2)

- Ens sortirà un menú i sel·leccionem la opció de *Quick registration and inventory*

![imatge](https://github.com/JoelIgle/m1/assets/114901284/f6d33da5-e113-43e5-974d-8d9c7ac0f0f4)

- I ens farà una petita instal·lació

![imatge](https://github.com/JoelIgle/m1/assets/114901284/087b60aa-f7bd-41db-a784-bdaa791b50ca)

- Un cop fet aixó ens sortirà com a que està *hostejada* al servidor (estic a la *administració de FOG*):

![imatge](https://github.com/JoelIgle/m1/assets/114901284/deff0cff-cfdf-45aa-991a-2d13f4b47157)

- Alli li posem com a **Host Image** *Windows 10*, que es la imatge que hem creat abans:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/be8588b6-a12d-4043-b0c2-a75d33a95166)

- I ho confirmem tot, fent *capture*

![imatge](https://github.com/JoelIgle/m1/assets/114901284/d8f27b70-26b2-478d-8353-ba4acbfd3f55)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/61ea2575-2ebc-475a-bdb3-111013f3351b)

- Reiniciem la màquina de windows 10, primer sens faran unes instal·lacions
 
![imatge](https://github.com/JoelIgle/m1/assets/114901284/603073fd-6e5c-42b2-8913-49993ad429b0)

- I després ja ens sortirà el menú, on sel·leccionem la opció *Deploy image* per a instal·lar la imatge:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/71138eed-6b46-45d7-8453-86994357e336)

- Ens demanarà les credencials

![imatge](https://github.com/JoelIgle/m1/assets/114901284/d4383985-4231-4da9-a394-86025fd0d745)

- I s'instal·larà la imatge

![imatge](https://github.com/JoelIgle/m1/assets/114901284/08f820f1-bc9d-48a9-a5fa-986f10c86007)

- Un cop instal·lada reiniciem i ja tenim el windows 10

![imatge](https://github.com/JoelIgle/m1/assets/114901284/130e398a-b001-412d-8954-158827225557)

## Instal·lar imatge Ubuntu
- Tornem a entrar a *Quick registration and inventory*

![imatge](https://github.com/JoelIgle/m1/assets/114901284/027c0043-2e65-4927-bf6d-37f1205b9008)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/77b04b48-1fa9-49ff-b902-d1904a2d2e1f)

- Li posem com a *Host Image* la imatge que hem creat abans *Ubuntu 22*

![imatge](https://github.com/JoelIgle/m1/assets/114901284/b09189f5-fab4-4585-9d89-f14b878883dc)

- Acceptem tot

![imatge](https://github.com/JoelIgle/m1/assets/114901284/7636bffd-5d2a-4f5e-b86b-f8331f4c38ad)

- Se fa una instal·lació

![imatge](https://github.com/JoelIgle/m1/assets/114901284/e946d2e0-01c8-4a60-8889-b53fdef3edbc)

- Reiniciem i sel·leccionem la opció de *Deploy Image*

![imatge](https://github.com/JoelIgle/m1/assets/114901284/4ac7d754-1a92-4d39-b68c-f23e58624a55)

- I la imatge de *Ubuntu 22*

![imatge](https://github.com/JoelIgle/m1/assets/114901284/5414f3db-e412-40fb-bb84-f52d064a5baf)

- Se fa la instal·lació de l'ubuntu

![imatge](https://github.com/JoelIgle/m1/assets/114901284/bc249a2e-5ed1-443f-bf26-dea5bbc8a59e)

- Al reiniciar la màquina ens surt un error, **no hem pogut arreglar-lo**

![imatge](https://github.com/JoelIgle/m1/assets/114901284/08a21090-2d1d-4170-a5a9-66d8ebccbaa6)

## Llençar un paquet per a que s'instal·li als clients
