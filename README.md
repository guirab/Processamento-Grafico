# P: O que é a GLSL? Quais os dois tipos de shaders são obrigatórios no pipeline programável da versão atual que trabalhamos em aula e o que eles processam? 
R: GLSL é a linguagem usada para a configuração dos shaders.Os shaders necessários são o Vertex Shader e o Fragment Shader.
# P: O que são primitivas gráficas? Como fazemos o armazenamento dos vértices na OpenGL?
R: Primitiva gráfica é a forma primordial que é usada para formar figuras mais complexas. O triângulo por exemplo, é a forma mais simples de ser desenhada em 3d, por possuir apenas 3 vértices.
  As vértices são armazenadas em um array de float.
# P: Explique o que é VBO, VAO e EBO, e como se relacionam (se achar mais fácil, pode fazer um gráfico representando a relação entre eles). 
R: 
	VBO -> Vertex Buffer Objects recebem os dados de vértices e enviam seus dados para a GPU.
	VAO -> Vertex Array Objects tem a função de descrevem os dados do vértice.
	EBO -> Element Buffer Objects utiliza índices para evitar a formação de vértices redundantes.


