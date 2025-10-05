# training-ansible

## Primer paso instalación de Ansible

```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
```
![img.png](img.png)

Usaremos la siguiente maquina virtual
![img_1.png](img_1.png)

y adaptamos nuestro host.ini a esta maquina virtual
![img_2.png](img_2.png)

## Segundo paso: Instalar docker

![img_3.png](img_3.png)

## Tercer paso: Ejecutar el contenedor

![img_4.png](img_4.png)

Pero si intentamos acceder en este momento no nos muestra nada :(

Esto se debe a que el puerto 8080 y 8087 no esta abierto en la maquina virtual Asi que vamos a abrirlo

![img_5.png](img_5.png)

Despues de esto ya podemos acceder al contenedor y ejecutar en web

![img_6.png](img_6.png)
