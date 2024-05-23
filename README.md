![detecção-objetos-banner](https://github.com/git-jr/3648-Android-MLKit-Object-Detection/assets/35709152/364eac0f-4f3a-4474-bec4-2b05f6db2ac4)

# AI Found 
O protótipo de aplicativo de compras que lista uma série de produtos com imagem, descrição, preço e permite adicioná-los ao carrinho. Graças ao reconhecimento de objetos é possível pesquisar por produtos apenas apontando a câmera do Android e o que for identificado vai ser buscado na base de dados do App. 


## 🔨 Funcionalidades do projeto
https://github.com/git-jr/3648-Android-MLKit-Object-Detection/assets/35709152/6996f637-7b22-4ca2-a6a4-b1758096c038

### ✨ Detecção de objetos
- Ao abrir a busca de produtos, a câmera passa os frames para análise do detector em tempo real, permitindo a análise por parte do modelo. 
- Cada frame é analisado em busca de informações através do modelo em uso (padrão ou customizado com TensorFlow Lite) 
- Quando um produto é identificado pelo modelo, uma sobreposição é exibida no preview da câmera nas exatas coordenadas do objeto em questão. 
- O produto detectado é buscado na base dados e exibido em tela automaticamente, permitindo sua adição ao carrinho de compras 
  
### 📱Telas
- Lista inicial: produtos disponíveis para compra
- Detalhes: informações como preço e descrição além da possibilidade de adição ao carrinho. 
- Carrinho: lista de todos produtos adicionados via tela de detalhes ou detecção da câmera.



## ✔️ Técnicas e tecnologias utilizadas

As técnicas e tecnologias utilizadas pra isso são:

- `Jetpack Compose`: kit de ferramentas moderno para criar IUs em dispositivos móveis
- `Kotlin`: linguagem de programação
- `Gradle Version Catalogs`: nova forma de gerenciar plugins e dependências em projetos Android
- `Material Design 3`: padrão de design recomendado pela google para criação de UI modernas
- `Hilt`: injeção de dependências
- `Navigating with Compose`: navegação entre composables e telas
- `Viewmodel, states e flow`: gerenciamento de estados da e controle dos eventos disparados pelas detecções do modelo da Google
- `ML Kit Object Detection`: biblioteca para detectar e extrair informações sobre objetos em tempo real usando a câmera do dispositivo
- `TensorFlow Lite Models`: conjunto de modelos pré-treinados e otimizados para executar em dispositivos móveis de forma eficiente.
- `Teachable Machine`: Plataforma que permite treinar modelos de aprendizado de máquina com facilidade, sem a necessidade de escrever código. Permite aos usuários criar modelos personalizados para reconhecimento de objetos, classificação de imagens e muito mais, com uma interface intuitiva e amigável.
- `CameraX`: biblioteca do Jetpack que facilita a integração de funcionalidades de câmera em aplicativos Android, abstraindo a complexidade da API de câmera do Android e oferecendo uma interface simples para captura de fotos e vídeo
- `CameraAnalyzer`: componente utilizado junto ao CameraX para analisar frames de vídeo em tempo real, permitindo a implementação de funcionalidades de detecção que requeiram processamento frame a frame.


## 📁 Acesso ao projeto

- Versão inicial: Veja o [código fonte][codigo-inicial] ou [baixe o projeto][download-inicial]
- Versão final: Veja o [código fonte][codigo-final] ou [baixe o projeto][download-final]

## 🛠️ Abrir e rodar o projeto
Após baixar o projeto, você pode abri-lo com o Android Studio. Para isso, na tela de launcher clique em:

“Open” (ou alguma opção similar), procure o local onde o projeto está e o selecione (caso o projeto seja baixado via zip, é necessário extraí-lo antes de procurá-lo). Por fim, clique em “OK” o Android Studio deve executar algumas tasks do Gradle para configurar o projeto, aguarde até finalizar. Ao finalizar as tasks, você pode executar o App 🏆


## 📚 Mais informações do curso

Gostou do projeto e quer conhecer mais? Você pode [acessar o curso](https://www.alura.com.br/curso-online-android-ia-usando-camera-detectar-objetos-machine-learning) que desenvolve o projeto desde o começo!

[codigo-inicial]: https://github.com/alura-cursos/3648-Android-MLKit-Object-Detection/commits/projeto-inicial/
[download-inicial]: https://github.com/alura-cursos/3648-Android-MLKit-Object-Detection/archive/refs/heads/projeto-inicial.zip

[codigo-final]: https://github.com/alura-cursos/3648-Android-MLKit-Object-Detection/commits/aula-5/
[download-final]: https://github.com/alura-cursos/3648-Android-MLKit-Object-Detection/archive/refs/heads/aula-5.zip
