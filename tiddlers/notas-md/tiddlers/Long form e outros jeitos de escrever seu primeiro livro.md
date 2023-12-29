# Long form e outros jeitos de escrever seu primeiro livro

## criado em: 
-  Ano, Mês e dia: 2023-07-08
- Hora: 21:11
- notas: [[Como organizar as notas esparsas]]
- tags: #criatividade #tecnologia #promptGPT #academia 
- Fontes & Links: 
---

O plugin Longform é uma ferramenta para o Obsidian que auxilia na escrita e edição de romances, roteiros e outros projetos longos. Ele permite que você organize uma série de notas, ou cenas, em um manuscrito ordenado. Também suporta projetos de nota única para trabalhos mais curtos. Aqui estão os principais recursos e como usá-los:

1. **Instalação**: O Longform está na seção Community Plugins das configurações do Obsidian. Você também pode instalá-lo manualmente copiando os arquivos main.js, manifest.json e styles.css de um release para uma pasta longform/ na pasta .obsidian/plugins do seu vault.

2. **Como funciona**: O Longform funciona procurando em seu vault qualquer nota que contenha uma entrada de frontmatter chamada longform. Você pode pensar nessas notas como as "espinhas dorsais" ou tabelas de conteúdo de seus projetos.

3. **Criando um romance**: Para começar, encontre ou crie uma pasta em seu vault onde gostaria de criar seu romance. Clique com o botão direito e selecione "Create Longform Project". Um modal "Create Project" aparecerá. Escolha entre os tipos de projeto Multi e Single-scene. No campo "Title", insira o título do seu romance. Clique em "Create". O Longform criará o arquivo prometido. Se você mudar para o painel Longform na barra lateral, o projeto já estará selecionado. Você verá três abas: Scenes, Project e Compile. A aba Scenes deve estar selecionada.

4. **Adicionando cenas**: O placeholder "New Scene" é um campo de texto - clique nele e insira algo que soe como a primeira cena de um romance, por exemplo, "The Sun Rises on Dublin", e pressione enter. Agora você deve estar editando uma nota com esse nome, e sua cena deve aparecer na aba Scenes.

5. **Criando uma história curta**: O Longform também suporta projetos de cena única que vivem como uma única nota em seu vault. Para criar um, clique com o botão direito na pasta que contém o projeto e selecione "Create Longform Project". No modal "Create Project", escolha "Single". Escreva sua história!

6. **Rascunhos e Projetos**: O Longform suporta a criação de vários rascunhos para um determinado projeto. Para criar um novo rascunho de um projeto, use o botão de novo rascunho (+) na aba Project.

7. **Compilando**: A aba Compile permite que você crie fluxos de trabalho personalizados que transformam seu projeto em um manuscrito.

8. **Estilização apenas para cena**: O Longform automaticamente anexará uma classe .longform-leaf aos painéis de contêiner de quaisquer notas que façam parte de um projeto Longform. Isso significa que você pode adicionar snippets CSS personalizados ao Obsidian que estilizam seu ambiente de escrita e apenas seu ambiente de escrita.

9. **Resolução de problemas**: O Longform é construído especificamente para nunca alterar o conteúdo de suas notas. A única nota que ele reescreve é o arquivo de índice de um projeto. Portanto, o Longform não pode excluir ou perder suas notas.

Espero que isso ajude a entender como usar o plugin Longform. Se você tiver mais perguntas, por favor, deixe-me saber!