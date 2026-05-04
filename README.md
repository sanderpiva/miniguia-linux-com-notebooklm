# Miniguia Linux com NotebookLM

## 📌 Contexto e Objetivos
Este projeto tem como objetivo criar um **segundo cérebro digital** para organizar e explorar conteúdos sobre o sistema operacional **Linux**, utilizando a inteligência artificial do **NotebookLM** como ferramenta de apoio.  
A proposta é reunir materiais relevantes, estruturar resumos e insights, e documentar o processo de aprendizado de forma clara e acessível.  

Os principais objetivos são:
- Consolidar conhecimentos sobre Linux, suas características e utilizações.  
- Explorar como a IA pode apoiar o estudo e a curadoria de informações.  
- Criar um guia prático que sirva como referência futura para revisões e aprofundamentos.  

---

## 📚 Curadoria de Fontes
A seguir estão as fontes selecionadas e utilizadas como base para o estudo no NotebookLM:

1. **CALADO, Aprígio de Lima.**  
   *Uma análise comparativa de distribuições do sistema operacional Linux.* 2018.  
   [PDF disponível aqui](https://releia.ifsertaope.edu.br/jspui/bitstream/123456789/450/1/TCC%20-%20UMA%20AN%c3%81LISE%20COMPARATIVA%20DE%20DISTRIBUI%c3%87%c3%95ES%20DO%20SISTEMA%20OPERACIONAL%20LINUX.pdf)

2. **CAMPOS, Augusto.**  
   *O que é Linux.* BR-Linux. Florianópolis, 2006.  
   [PDF disponível aqui](https://www.jvasconcellos.com.br/ti/wp-content/uploads/2012/01/linux.pdf)

3. **LIMA, Welton Dias.**  
   *Android e a influência do Sistema Operacional Linux.* Tecnologias em Projeção, v. 8, n. 1, p. 100-111, 2017.  
   [Artigo disponível aqui](https://www.projecaociencia.com.br/index.php/Projecao4/article/view/829)

4. **RESGATES, Revista.**  
   *Sistemas operacionais livres baseados em Linux.* Colégio Stockler, 2017.  
   [PDF disponível aqui](https://static1.squarespace.com/static/637bb31bc82d6a0e64a33d3d/t/6470f6db2d5c8b1814aba6c2/1722006373009/stockler-2017-revista-resgates.pdf#page=38)

5. **ZORZO, Avelino Francisco et al.**  
   *Uso de Linux como Sistema Embarcado.* In: III Workshop sobre Software Livre, 2002, Brasil.  
   [PDF disponível aqui](https://repositorio.pucrs.br/dspace/bitstream/10923/22219/2/Uso_de_Linux_como_Sistema_Embarcado.pdf)

---

## 🧩 Engenharia de Prompts e Cicatrizes
Durante a exploração com o NotebookLM, foram elaboradas perguntas estratégicas para extrair informações relevantes das fontes. Alguns exemplos de prompts utilizados:

- **Prompt 1:** "Quais as principais diferenças entre o kernel Linux e as distribuições?"  
- **Prompt 2:** "Qual é a polêmica sobre o nome GNU/Linux?"  
- **Prompt 3:** "Cite e explique alguns comandos em Linux"  
- **Prompt 4:** "Quais vantagens do Linux como sistema embarcado?"  

### Cicatrizes (aprendizados e dificuldades)
- Não houve dificuldades técnicas, mas aprendi que prompts mais específicos geram respostas mais contextualizadas.  
- As respostas foram consistentes com as fontes, sem necessidade de correções.
- Ao incluir a fonte **Resgates, Revista**, e pedir para fazer um **resumo em áudio (Studio)** ele não considerou apenas as páginas sobre o Linux (45-54), incluindo outro conteúdo.
Portanto, ao fazer os resumos 'exclui' essa fonte para evitar inconsistencias, apesar do prompt ter funcionado corretamente. 

---

## 🖼️ Evidências Visuais (NotebookLM)
Para comprovar as interações realizadas com o NotebookLM, foram registradas capturas de tela que mostram os prompts e respostas obtidas.  
Essas imagens estão disponíveis na pasta `img_src` deste repositório.

Exemplos de prints incluídos:
-1 Diferenças entre **Kernel Linux** e **Distribuições**.  
print1
print2
print3
---
-2 Debate sobre o nome **GNU/Linux**.  
print1
print2
print3
---
-3 Comandos básicos como `ls`, `cp`, `sudo`, `apt-get`.  
print1
print2
print3
---
-4 Linux como sistema embarcado.  
print1
print2
---
#

## 📖 Miniguia de Estudo (Entrega Final)

### 📑 Resumos Estruturados
**Kernel vs Distribuições**  
- O kernel é o núcleo do sistema, criado por Linus Torvalds em 1991.  
- Atua como intermediário entre hardware e software, gerenciando recursos como memória e processador.  
- As distribuições são sistemas completos, que incluem o kernel + utilitários + aplicativos, prontos para uso (ex.: Ubuntu, Debian, Fedora).  

**Android e Linux**  
- O Android utiliza o kernel Linux como base para seu funcionamento.  
- Essa integração garante estabilidade, segurança e compatibilidade com diversos dispositivos móveis.  

**Linux como Sistema Embarcado**  
- Segundo Zorzo (2002), o Linux é amplamente usado em sistemas embarcados devido à sua flexibilidade e código aberto.  
- Permite customização para dispositivos específicos, como roteadores, smart TVs e equipamentos industriais.  

**Comandos Essenciais**  
- `ls`: lista arquivos e diretórios.  
- `cp`: copia arquivos.  
- `sudo`: executa comandos com privilégios de administrador.  
- `apt-get`: gerencia pacotes em distribuições Debian/Ubuntu.  
- `time`: mede tempo de execução de processos.  

---

### 📘 Glossário de Conceitos
- **Kernel**: núcleo do sistema operacional, responsável por gerenciar recursos.  
- **Shell**: interpretador de comandos que conecta usuário e sistema.  
- **Distribuição (Distro)**: versão completa do Linux com kernel + utilitários + aplicativos.  
- **GNU/Linux**: denominação que reconhece a união do kernel Linux com ferramentas do projeto GNU.  
- **Sistema Embarcado**: dispositivos que utilizam Linux adaptado para funções específicas.  
- **/proc**: diretório virtual que fornece informações sobre processos e estado do sistema.  
- **sudo**: comando para executar ações com privilégios de administrador.  

---

### 💡 Prompts Reutilizáveis
- "Explique as diferenças entre kernel Linux e distribuições."  
- "Como o Android utiliza o kernel Linux?"  
- "Quais são os principais comandos básicos do Linux e suas funções?"  
- "Quais vantagens do Linux como sistema embarcado?"  
- "Qual é a polêmica sobre o nome GNU/Linux?"  
- "Liste exemplos de distribuições Linux e suas características principais."  

---

## 🚧 Próximos Passos
- Expandir os resumos com mais detalhes das fontes.  
- Adicionar exemplos práticos de uso dos comandos.  
- Inserir prints da pasta `img_src` para ilustrar cada resumo.  
- Refinar e documentar novos prompts para enriquecer o aprendizado.  

