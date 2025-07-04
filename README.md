# P3_Comp_Grafica  
**Prova 3 da Matéria de Computação Grafica - UNICAMP**  

## Descrição
Esse repositório contém os arquivos necessários para compilar e rodar o que foi feito e pensado para a resolução da P3 da matéria.
A prova pedia para implementar AABB trees de maneira visual tal que seria possível ver o desenvolvimento das análises de colisão entre objetos.
Para isso, ao invés de utilizar a função sleep para expor passo a passo, diminuimos consideravelmente a gravidade da cena e fizemos um objeto cair em cima do outro.
Assim, conseguimos fazer visualmente com que as AABB trees se desenvolvam de maneira dinâmica.
Não implementamos nenhum resposta à colisão pois a arvore se desenvolve mais caso os objetos se sobreponham.
Porém há uma pseudo colisão com o chão para que o objeto caindo não passe direto pelo objeto estacionário.

## Installation  

### Prerequisites  
- OpenGL
- GLFW
- GLEW
- glm 
- CMake
- stb_image 

### Build Instructions  
1. Clone the repository:  
   ```sh
   git clone https://github.com/TheBorts/P3_Comp_Grafica.git
   cd P3_Comp_Grafica
   mkdir build
   cd build
   cmake ..
   make
   ./p3 ../models/ground.obj ../models/Untitled.obj ../models/bola.obj ../models/bunny.obj ../models/Cube1.obj ../models/Cube2.obj

Caso nada aconteça por favor mandar email para mim...
