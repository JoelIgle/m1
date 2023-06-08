# Instal·lació desatesa

## Realitzar la instal·lació desatesa amb el kickstart d'un SO Ubuntu

- Primer que tot hem de actualitzar repositoris:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/942ff9dd-ba98-4dab-a2b1-a8effcf7936b)

- En segon lloc hem d'instal·lar el **system-config-kickstart**

![imatge](https://github.com/JoelIgle/m1/assets/114901284/9a2c6753-90d0-457d-9ec6-995dc3bccb08)
![imatge](https://github.com/JoelIgle/m1/assets/114901284/cc3cb464-df93-4ba5-9b4e-edc8d3fe7a46)
![imatge](https://github.com/JoelIgle/m1/assets/114901284/e1f47b0b-eb1f-4dfc-9ae9-0a4dc224a8b8)
![imatge](https://github.com/JoelIgle/m1/assets/114901284/ecb7ddc8-9476-44c6-aea3-0078e3d35208)

- Un cop tenim aixó, ens podem instal·lar el **isomaster**
![imatge](https://github.com/JoelIgle/m1/assets/114901284/b656eb31-a86b-4429-a9cd-b32e85aaec04)
![imatge](https://github.com/JoelIgle/m1/assets/114901284/53f313ff-b574-4e1e-95ea-e698d5863550)

- Ara ja podem obrir el **ystem-config-kickstart** que hem instal·lat abans, aquí podem configurar ela paràmetres com vulgem, en el meu cas es així:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/8fd84e82-0d62-466e-9eea-762cf8371f67)

- I guardem l'arxiu ks.cfg a l'escritori

![imatge](https://github.com/JoelIgle/m1/assets/114901284/7e05a9d9-24a7-4fb3-87b7-2e202e472f5f)

- I li donem permisos de tot

![imatge](https://github.com/JoelIgle/m1/assets/114901284/03fc0e73-b549-495c-a0e7-3febc4fe8106)

- Ara obrim la **.iso** que hem guardat amb l'isomaster instal·lat previament, i el posem a l'arrel l'arciu ks.cfg

![imatge](https://github.com/JoelIgle/m1/assets/114901284/3cc699c4-4a60-420b-ae1b-2f2d62aa1826)

- Amb l’isomaster extrec l’arxiu txt.cfg a l’escritori, i el modifico per tal d’afegir una opció més al menú.

![imatge](https://github.com/JoelIgle/m1/assets/114901284/e4e5256c-9c08-4118-ad48-701d28ba0594)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/a7d86876-edde-4ec4-9091-e5defec614e1)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/01b8abcc-1c64-4cd7-bbde-ec85ba9640be)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/bb42c9dd-c3a3-4613-ace6-f30993d42980)

- Ara provarem que funcioni a una nova màquina virtual

![imatge](https://github.com/JoelIgle/m1/assets/114901284/d71186c7-7e2a-4a00-87af-83fdd67f8230)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/bb9f5a79-83ad-4902-80c2-b7b6c55e1f42)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/47a7ba33-9c05-4695-956e-93e8d42b182c)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/2d7cfa75-becf-41ce-a6ca-72c75eeffb7e)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/19036fed-1409-4509-aabb-1a94f4ea9df3)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/55456bb3-8fc3-43d3-aa96-da6bda9da328)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/7a8e2d0b-479a-4659-a224-b6dfeaef0ed4)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/3adfb17f-17a5-4a23-b252-11cc4ae420dc)

## Realitzar la instal·lació desatesa amb el pressed d'un SO Ubuntu.

- Busquem a internet un arxiu pressed.cfg i el modifiquem per a nosaltres, aquest es el meu:

![imatge](https://github.com/JoelIgle/m1/assets/114901284/9bb64fc4-bc97-402c-b7c0-96c4f26cbeb5)

- Ara posem aquest archiu dins la iso, i modifiquem l'archiu **txt.cfg** afegint una nova opvió per a que l'agafi

![imatge](https://github.com/JoelIgle/m1/assets/114901284/4c8dd3e7-d823-4523-8c47-8e68113caf83)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/77b8fbb1-aa18-42fb-bc27-8fd4e3bf41b1)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/614ca7ae-d55d-4b32-a5f0-3ba60b3dc6a0)

- I finalment provem la iso en una nova màquina virtual per a veure si el que hem fet és correcte

![imatge](https://github.com/JoelIgle/m1/assets/114901284/66f8dbc8-66db-45c1-8146-d4524daeffaa)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/cd11c22d-3fa9-4e9c-ad49-166c6489f798)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/ab6d4222-be45-4a77-bd93-8709268c8f61)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/fdf281fb-34a4-4391-8a7f-80f1ac63f5f9)

![imatge](https://github.com/JoelIgle/m1/assets/114901284/0095395a-71c9-4e4b-a622-e33c9da724d5)
