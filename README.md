# Floorplan

## List Report Page

### Introdução
A página de List Report oferece aos usuários a capacidade de visualizar e interagir com um grande conjunto de itens. Esta é geralmente utilizada como ponto de entrada para navegar até os detalhes de um item específico.

### Quando Usar
- Quando os usuários precisam encontrar e agir em relação a itens relevantes dentro de um grande conjunto de itens.
- Quando deseja-se permitir que os usuários visualizem todo o conjunto de dados usando diferentes visualizações.
- Quando os usuários precisam trabalhar com múltiplas visualizações do mesmo item.
- Quando o detalhamento raramente é usado ou está disponível apenas através da navegação para outra página.
- Quando os usuários trabalham com diferentes tipos de itens.

### Quando Não Usar
- Quando os usuários precisam ver ou editar um item com todos os seus detalhes.
- Quando os usuários precisam encontrar um item específico e o item ou o dado de identificação é conhecido pelo usuário.
- Quando os usuários precisam trabalhar com um conjunto pequeno de itens, um por um.
- Quando os usuários precisam extrair conhecimento ou insight dos dados.
- Quando os gráficos não são usados apenas para visualização.
- Quando os usuários precisam ver o impacto de suas ações em um KPI.
- Quando os usuários precisam ver não apenas o resultado, mas também o impacto de suas configurações de filtro diretamente em uma representação gráfica.

### Gerenciamento de Variantes
- O gerenciamento de variantes é opcional.
- É recomendado usar um controle de gerenciamento de variante para toda a página.
- Os usuários podem escolher uma variante padrão, que é selecionada sempre que o aplicativo é iniciado.
- Se o gerenciamento de variantes não for necessário, mostre um título que descreva a visualização atual.

### Filtrar Informações
- Exiba as informações do filtro somente se o conteúdo do cabeçalho estiver recolhido.
- Mostre até 5 filtros.

### Barra de Ferramentas de Cabeçalho
- Use a barra de ferramentas do cabeçalho para ações não finalizadas, por exemplo: compartilhar.
- A barra de ferramentas do cabeçalho pode conter um campo de pesquisa.
- Os filtros são aplicados a todo o conteúdo, certifique-se de que os campos de filtros obrigatórios sempre tenham valores padrão.

### Layout Geral
- Existem três layouts básicos do List Report: conteúdo simples, visualizações múltiplas e conteúdo múltiplo.
- Conteúdo simples: na maioria dos casos, consiste apenas em uma barra de ferramentas de tabela e uma tabela.
- Visualizações múltiplas: fornece diversas visualizações do mesmo conteúdo, mostrando a mesma tabela, mas com colunas diferentes ou em diferentes estados pré-filtrados.
- Conteúdo múltiplo: pode conter diversas tabelas que exibem diferentes estados dos objetos.

### Navegação
- Existem três tipos de navegação: navegação do item de linha, navegação detalhada e navegação cruzada.

### Modos de Trabalho
- Modo Lista de Trabalho: reação direta do sistema às alterações dos usuários.
- Modo de Trabalho Contínuo: o usuário ainda precisa do item editado, mesmo que não corresponda mais aos critérios de filtro.

### Ações
- Ações globais afetam a página inteira e são colocadas na barra de ferramentas do cabeçalho.
- Ações de tabela/gráfico afetam o conteúdo de uma tabela ou gráfico e são colocadas na barra de ferramentas da tabela.
- Ações de item de linha afetam um único item e podem ser colocadas diretamente dentro do item de linha.
- Ações de finalização indicam o fim de um processo e afetam a página inteira, sendo colocadas na barra de ferramentas de rodapé.

### Capacidade de Resposta
- Em geral, o List Report é responsivo, mas há exceções se determinados controles forem usados.

## Analytical List Page

### Introdução
A página de Analytical List oferece aos usuários uma maneira exclusiva de analisar dados de diferentes perspectivas, investigar causas raízes e agir sobre conteúdo transacional.

### Quando Usar
- Quando os usuários precisam extrair informações importantes para compreender a situação atual ou identificar uma causa raiz.
- Quando os usuários precisam analisar os dados de diferentes perspectivas e agir sobre conteúdo transacional.
- Quando os usuários precisam alternar entre visualizações de gráfico e tabela.
- Quando os usuários precisam ver o impacto de suas ações em um indicador chave de desempenho.

### Quando Não Usar
- Quando o detalhamento raramente é usado ou só é necessário ao navegar para outra página.
- Quando os usuários precisam de visualizações diferentes para todo o conjunto de dados, mas não precisam de ambas as visualizações na mesma página.
- Quando os usuários precisam encontrar e agir sobre itens relevantes em um grande conjunto de itens sem usar detalhamento ou "dividir e fatiar".
- Quando os usuários precisam ver ou editar um único item com todos os seus detalhes.

### Estrutura
- Usa o layout de página dinâmica e tem duas áreas principais: Cabeçalho da página de lista analítica e Área de conteúdo da página de lista analítica.

### Variantes de Layout
- Os usuários podem escolher entre a barra de filtro visual e a barra de filtro no cabeçalho da página expandida.
- Na área de conteúdo, os usuários podem alternar entre visualização híbrida (gráfico e tabela), uma visualização somente de gráfico ou somente de tabela.

### Gerenciamento de Variantes
- Permite aos usuários uma variante de página sempre que houver alterações nas estruturas subjacentes da área de filtro/conteúdo.

### Tags e Cartões de KPIs Globais
- Use uma tag de KPI global para mostrar um KPI relacionado à tarefa em questão.
- Só pode exibir no máximo 3 KPIs globais.
- Clicar em uma tag de KPI abre um cartão KPI que exibe mais detalhes sobre esse KPI.

### Área de Filtro
- Permite ao usuário filtrar o conjunto de resultados, alimentando a área de conteúdo principal.
- A página vem com 2 filtros: filtros compactos e barra de filtros visuais.
- Recomendado definir a barra de filtros visuais com

 padrão.
- Ambos os filtros suportam 2 modos diferentes: atualização ao vivo e atualização manual.

### Tipos de Gráficos na Barra de Filtro Visual
- Gráfico de rosca interativo: usado para dados não relacionados ao tempo.
- Gráfico de linhas interativo: usado exclusivamente para dados de séries temporais.
- Gráfico de barras interativo: pode ser usado para dados não relacionados ao tempo.

### Usando Gráficos Interativos
- Mostre pelo menos 3 filtros visuais.
- Use uma convenção de nomenclatura para o título do filtro.
- Para contagem de itens, use "Número de [Dimensão]".

### Diretrizes
- Não mostre a mesma dimensão de filtro com duas ou mais medidas diferentes ao mesmo tempo.
- Considere usar uma overview page se o caso de uso exigir demonstrar uma dimensão com medidas diferentes.
