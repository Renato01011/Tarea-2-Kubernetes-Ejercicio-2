# Tarea-2-Kubernetes-Ejercicio-2

## Single Node

La aplicación que escogimos para esta tarea es una aplicación web basada en containers. Esta es una aplicación donde se pueden añadir nuevos ítems con un botón y eliminarlos si se quiere.
La siguiente imagen muestra esta app:

![Single Node App](https://github.com/Renato01011/Tarea-2-Kubernetes-Ejercicio-2/blob/main/Images/SingleNode.png)

Link de Referencia:

https://docs.docker.com/get-started/02_our_app/

## Multi Node

Además de esta primera app, y debido a que esta es considerablemente simple, haremos uso de otra app parecida, pero hecha de forma más compleja con un backend y una base de datos. En esta app solo es posible añadir nuevos ítems y no quitar, sin embargo, estos son guardados en una base de datos con el uso del api que proporciona el backend. El propósito de esta aplicación es de ser usada como Libro de Invitados, es decir, invitados pueden guardar su información.
La siguiente imagen muestra esta app:

![Multi Node App](https://github.com/Renato01011/Tarea-2-Kubernetes-Ejercicio-2/blob/main/Images/MultiNode.png)

Link de Referencia:

https://kubernetes.io/docs/tutorials/stateless-application/guestbook/
