# Converter-of-a-list-of-vertices-and-faces-to-a-OBJ-model-on-babylon.js

Не нашел создал! Я сделал конвертер вершин, и граней масивов vertex, и faces по которым создается OBJ модель.

[Converter of a list of vertices and faces to a OBJ model on babylon.js | Babylon.js Playground](https://playground.babylonjs.com/#X3KZOO#0)

Теперь мне нужно натянуть текстуру на созданную 3D модель.

[Converter of a list of vertices and faces to a OBJ model on babylon.js (Version 2) | Babylon.js Playground](https://playground.babylonjs.com/#8ZQG1V#0)

Но мне нужно генерировать текстуру не через URL ссылку а процедурно.

[Converter of a list of vertices and faces to a OBJ model on babylon.js (Version 3 - Procedural image) | Babylon.js Playground](https://playground.babylonjs.com/#I3E1HB#0)

Теперь нужно сделать процедурную текстуру цветной а не бесцветной.

[Converter of a list of vertices and faces to a OBJ model on babylon.js (Version 4 - Procedural image generation color) | Babylon.js Playground](https://playground.babylonjs.com/#MRB975#0)

Теперь для разных faces нужно сделать разные текстуры URL.

[Converter of a list of vertices and faces to a OBJ on babylon.js (Version 5-With marked faces for each side of each OBJ) | Babylon.js Playground](https://playground.babylonjs.com/#C1T0EK#0)

Отлично теперь мне нужно измерить нижние, средние, и верхние faces что для каждого набор сделать отдельные тип текстуры.

[Converter of a list of vertices and faces to a OBJ model on babylon.js (Version 5.1 - Tester pre-alpha) | Babylon.js Playground](https://playground.babylonjs.com/#32KLNF#1)

Теперь нужно растянуть UV faces что-бы сделать видимыми все текстуры.

[Converter of a list of vertices and faces to a OBJ model on babylon.js (Version 5.2 - Tester pre-alpha) | Babylon.js Playground](https://playground.babylonjs.com/#BNUJ5K#0)

Теперь нужно сделать разные наборы текстур для тех которые нижние, средние, и верхние faces что-бы был полноценный бэкрумс с разными биомами текстур.

[Converter of a list of vertices and faces to a OBJ (Version 6 - With random textures of the selected faces group) | Babylon.js Playground](https://playground.babylonjs.com/#69YY8U#0)

Но каждый раз разные наборы текстур для разных биомов текстур нижних, верхних, и средних faces должны генерироваться разные текстуры в случайных faces а не всегда заранее одинаково заданно! 

[Converter of a list of vertices and faces to a OBJ model (Version 7 - With the choice of a random sequence of numbers) | Babylon.js Playground](https://playground.babylonjs.com/#BG3QQB#0)

Отлично теперь нужно сделать ровным UV что-бы смотрелось ровно а не рванно! 

[Converter of a list of vertices and faces to a OBJ (Version 8 - Different texture groups faces and smooth UV) | Babylon.js Playground](https://playground.babylonjs.com/#246TAV#0)

Теперь нужно добавить кнопки для открытия табло в которых можно было бы онлайн изменять faces, и vertex что-бы постоянно смотреть на изменения.

[Converter of a list of vertices and faces to a OBJ (Version 9 - With an OBJ generation window via vertex, and faces) | Babylon.js Playground](https://playground.babylonjs.com/?inspectorv2=true#CVIFTU#2)

Тоже что и предыдущий код только с текстурами.

[Converter of a list of vertices and faces to a OBJ (Version 10 - With an OBJ generation window via vertex,faces,texture) | Babylon.js Playground](https://playground.babylonjs.com/#OBHR5E#1)

Стурктуры OBJ с зарнее установленными местами генерации.

[Converter of a list of vertices and faces to a OBJ (Version 11-With preset OBJ structures and a preset generation local) | Babylon.js Playground](https://playground.babylonjs.com/#CZ8JJX)

И наооборот что-бы превратить список vertex, и faces в blend модель код python:

[Converter-of-a-list-of-vertices-and-faces-to-a-OBJ-model](https://github.com/MakarovDs777/Converter-of-a-list-of-vertices-and-faces-to-a-OBJ-model/blob/main/convert-a-blend-file-to-a-vertex-list-and-mesh.py)

Для того что-бы превратить blend модель в список vertex, и faces код python: 

[Convert-a-blend-file-to-a-vertex-list-and-mesh.py](https://github.com/MakarovDs777/Convert-a-blend-file-to-a-vertex-list-and-mesh/blob/main/Convert-a-blend-file-to-a-vertex-list-and-mesh.py)

Или если надо превратить OBJ модель в единный массив чисел:

[Convert-OBJ-to-a-single-array-of-numbers](https://github.com/MakarovDs777/Convert-OBJ-to-a-single-array-of-numbers/blob/main/Convert-OBJ-to-a-single-array-of-numbers.py)

И наооборот единый массив чисел в OBJ модель.

[Convert-a-single-array-of-numbers-to-an-OBJ](https://github.com/MakarovDs777/Convert-a-single-array-of-numbers-to-an-OBJ/blob/main/Convert-a-single-array-of-numbers-to-an-OBJ.py)
