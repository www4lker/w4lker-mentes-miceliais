# LONGFORM OBSIDIAN

## criado em: 
-  Ano, Mês e dia: 2023-06-09
- Hora: 16:49

### Conteúdo Relacionado
- notas: [[obsidian]]
- [[do obsidian ao scrivener]]
- [[Scrivener 3]]
- [[do obsidian ao scrivener -  toque final]]
- [[workflow obsidian longform scrivener]]
- tags: #meta #promptGPT #criatividade #academia 
- Fontes & Links: 
---

> ideia central - juntar as notas no obsidian em um arquivo maior - dali converter para um formato rtf - e depois pós processar no scrivener

O Longform foi criado para ajudá-lo a escrever e editar projetos longos, como romances, roteiros e outros trabalhos extensos. Ele oferece recursos como organização de cenas em um manuscrito, rastreamento de contagem de palavras, metas de sessão de escrita, ferramentas de compilação, suporte para projetos de cena única e muito mais.

Para preparar seu documento para pós-processamento no Scrivener usando o plug-in Longform, você pode seguir estas etapas gerais:

1. Instale o plug-in Longform na Obsidian. Isso pode ser feito na seção Plugins da comunidade das configurações da Obsidian.
2. Depois de instalado, crie um novo projeto Longform para seu documento. Na Obsidian, clique com o botão direito do mouse na pasta em que deseja criar o projeto e selecione "Create Longform Project" (Criar projeto Longform).
3. Escolha o tipo de projeto apropriado (várias cenas ou uma única cena) com base na extensão e na estrutura do documento.
4. Digite o título do projeto e deixe que o Longform crie os arquivos necessários para o seu projeto.
5. Comece a adicionar cenas ao seu projeto. No painel do Longform, você pode clicar no campo "New Scene" (Nova cena) e digitar os nomes ou as descrições das cenas.
6. Use os recursos fornecidos pelo Longform para organizar e estruturar o documento. Você pode reordenar cenas, criar cenas pai para agrupar cenas relacionadas e utilizar os vários comandos e opções disponíveis.
7. Escreva seu documento editando as notas de cenas individuais criadas no projeto.
8. Quando estiver pronto para exportar o documento para pós-processamento no Scrivener, use a ferramenta de compilação fornecida pelo Longform. O recurso "Compile" (Compilar) permite gerar um único manuscrito a partir do seu projeto, que pode ser posteriormente refinado no Scrivener.

Observe que as etapas e as funcionalidades específicas podem variar de acordo com a versão do plug-in Longform que você está usando. É sempre uma boa ideia consultar a documentação oficial do plug-in para obter instruções detalhadas e quaisquer atualizações ou alterações que possam ter ocorrido desde o meu corte de conhecimento em setembro de 2021.

Espero que isso ajude você a entender como usar o plug-in Longform na Obsidian para preparar seu documento para pós-processamento no Scrivener.

---

A guia "Compilar" do Longform permite criar fluxos de trabalho que incluem etapas para transformar seu projeto em um documento final. Veja a seguir uma visão geral dos diferentes componentes e conceitos da guia Compilar:

1. **Etapas**: As etapas são os blocos de construção básicos da compilação no Longform. Elas recebem uma entrada (cenas ou um manuscrito combinado) e retornam uma saída (cenas transformadas ou um manuscrito alterado). Há três tipos de etapas:
   - Etapas de cena: Atuam em cada cena individualmente e recebem uma lista de cenas como entrada, retornando a lista modificada como saída. Por exemplo, a etapa "Prepend Title" (Anexar título) insere um cabeçalho com o título da cena na parte superior de cada cena.
   - Etapas de união: Pegam uma lista de cenas e as combinam em um único manuscrito.
   - Etapas do manuscrito: Atuam em um único documento do manuscrito.

   As etapas devem estar sempre na seguinte ordem: qualquer número de etapas de cena, seguido por uma etapa de união e, em seguida, qualquer número de etapas de manuscrito.

2. **Etapas incorporadas**: O Longform vem com um conjunto de etapas incorporadas que você pode adicionar ao seu fluxo de trabalho de compilação. Essas etapas incluem "Prepend Title" (Acrescentar título previamente), "Remove Comments" (Remover comentários), "Remove Links" (Remover links), "Remove Strikethroughs" (Remover tachados), "Strip Frontmatter" (Remover capa), "Concatenate Text" (Concatenar texto) e "Write to Note" (Escrever para nota). Cada etapa tem opções específicas que você pode personalizar.

3. **Etapas do script do usuário**: Além das etapas incorporadas, o Longform permite que você crie etapas personalizadas usando JavaScript. Você pode criar uma etapa de script de usuário exportando um objeto com propriedades específicas: `description` (que descreve a etapa e sua configuração) e `compile` (a função executada durante a compilação). As etapas de script do usuário oferecem flexibilidade para a criação de processos de compilação personalizados.

4. **Fluxos de trabalho**: As etapas são organizadas em fluxos de trabalho. O Longform inclui um fluxo de trabalho padrão que demonstra o processo de compilação e produz um manuscrito formatado simples. Você pode criar novos fluxos de trabalho para cada projeto e personalizá-los conforme necessário. Os fluxos de trabalho abrangem todo o cofre, portanto, a alteração de um fluxo de trabalho em um projeto afeta todos os projetos que usam esse fluxo de trabalho.

Para adicionar etapas ao seu fluxo de trabalho, clique no botão "Add Step" (Adicionar etapa) e escolha entre as etapas incorporadas disponíveis ou as etapas de script do usuário. Você pode arrastar e reorganizar as etapas em um fluxo de trabalho para controlar a ordem de execução.

Lembre-se de que o recurso "Compile" do Longform está em constante evolução, e mais etapas e recursos poderão ser adicionados no futuro. Se tiver sugestões ou encontrar problemas, você pode contribuir abrindo um problema no GitHub.

---

