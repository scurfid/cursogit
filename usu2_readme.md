# Curso de Git usu2

Readme usuario 2

![Git](/assets/gitLogo.png)


## Introducción

Bienvenido al **curso de Git**. En este curso aprenderás a manejar el control de versiones con Git y a visualizar el flujo de trabajo mediante _grafos_.

---

## Información del Autor

👨‍🏫 **Autor:** *usu2*  
📍 **Experiencia:** *13 años como ingeniero de software, ahora profesor de secundaria especializado en tecnología.*  
🎯 **Objetivo:** *Ayudar a los estudiantes a comprender Git y aplicar buenas prácticas en el desarrollo de software.*

---

## Instalación

Para instalar Git en tu sistema, sigue las instrucciones correspondientes:

- **Windows:** Descarga el instalador desde [git-scm.com](https://git-scm.com/) y sigue los pasos.
- **Linux/macOS:** Ejecuta el siguiente comando:
  ```sh
  sudo apt-get install git  # En Debian/Ubuntu
  brew install git          # En macOS
  ```

---

## Prácticas

### 0. Git setup
```sh
it config --global user.name "John Doe"
git config --global user.email "johndoe@example.com
```

### 1. PRACTICA 1 INTRO A GIT
```sh
git log --graph
```

### 2. GIT LOCAL - conflictos

![conflicto](/assets/resolucionConflicto.png)

Puedes visualizar el grafo de commits en forma de diagrama utilizando herramientas como:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
---

## Recursos Adicionales

- [Documentación Oficial de Git](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)
- [Curso ISMIE Git](https://github.com/oscarnovillo/Curso-de-Git-ISMIE)

🖥️ ¡Feliz coding con Git! 🚀

*Realizado con ayuda de ChatGPT*