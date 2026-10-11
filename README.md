# Criando um Dashboard Gerencial para Tomada de Decisão com Power BI

Este repositório apresenta a resolução do segundo desafio de projeto do módulo de Power BI, cujo objetivo principal foi transformar um relatório estático em uma ferramenta gerencial altamente interativa, aplicando conceitos avançados de *Experiência do Usuário (UX)* e *Design de Interface (UI)*.

## 🎨 O Desafio de UX/UI

A partir de um modelo base fornecido pela instrutora, o projeto foi estendido para *3 páginas completas, focando na simetria, contraste em fundos escuros (*Dark Mode) e facilidade de navegação para o usuário final.

### Estrutura das Páginas:
1. *Home page (Capa):* Uma tela de boas-vindas limpa e intuitiva. O botão central "Explorar análise" foi configurado com uma ação de navegação direcionada para abrir imediatamente o relatório de vendas. Um ícone discreto de informação foi adicionado no canto inferior esquerdo para futuras instruções ou metadados.
2. *Dashboard de Vendas:* Tela focada na análise de faturamento bruto e unidades vendidas por período, segmento e país. Os gráficos foram redimensionados para garantir simetria em relação aos painéis roxos de fundo.
3. *Análise de Lucro (Nova Página Customizada):* Criada do zero através da duplicação e adaptação da segunda página. Todos os elementos visuais de receita foram substituídos pela métrica de Lucro Líquido (Profit), oferecendo aos gestores uma visão clara de rentabilidade por produto e segmento corporativo.

---

## 🛠️ Funcionalidades de Navegação e Interatividade Implementadas

Para tornar o relatório fluido e profissional, foram feitas as seguintes melhorias técnicas:

### 1. Menu de Navegação Dinâmico
Utilização do recurso nativo Page Navigator do Power BI posicionado na barra inferior branca de todas as telas. Ele indica de forma automática e visual (através de um traço verde) exatamente em qual página o usuário se encontra.

### 2. Fluxo de Avanço e Retorno (Setas de Navegação)
- Os botões de seta foram movidos estrategicamente para o *canto superior direito* das páginas, garantindo que os títulos longos ficassem limpos e o layout ficasse simétrico e sem poluição visual.
- A seta da terceira página foi rotacionada em *180 graus diretamente no menu de formato do ícone*, criando uma indicação visual clássica de "Voltar" que direciona o usuário perfeitamente de volta à página de vendas.

### 3. Botão Inteligente de Reset ("Limpar Filtros")
O fundo do relatório trazia a imagem estática de uma borracha azul que não executava nenhuma ação. Para dar vida a esse elemento:
- Foram criados indicadores (Bookmarks) exclusivos para cada página: *Clean Page* (para vendas) e *Clean Page Lucro* (para lucros).
- Foi sobreposto um *Botão em Branco (invisível)* exatamente em cima do desenho da borracha.
- Esse botão foi associado à ação do indicador correspondente. Agora, ao segurar Ctrl + Clique na borracha, o usuário limpa todas as seleções de países e datas de uma vez só, resetando o painel de forma independente sem mudar de página.

---

## 📐 Visualização do Projeto Finalizado

### 1. Home Page (Capa de Entrada)
![Capa do Relatório](insira_aqui_o_link_do_print_da_sua_capa.png)

### 2. Dashboard de Vendas (Visão Geral)
![Dashboard de Vendas](insira_aqui_o_link_do_print_de_vendas.png)

### 3. Análise de Lucro (Visão de Rentabilidade)
![Análise de Lucro](/imagens/analise_lucro.png)

---

## 📂 Arquivos Incluídos no Repositório
- .pbix: Arquivo original do Power BI contendo o modelo tratado, as 3 abas desenvolvidas e todas as regras de navegação por botões e indicadores prontas para uso.
- Imagens do Layout para documentação do portfólio.

## 👨‍💻 Autor
Desenvolvido por **Gabriela Pereira das Neves** no âmbito da jornada de transição e especialização em Dados e Tecnologia.
