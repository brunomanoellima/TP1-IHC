# 🔎 2. Inspeção de Usabilidade – Pacific Northwest X-Ray Inc. (PNWX)

## 🧭 Introdução
A primeira avaliação do sistema **PNWX** foi realizada por meio da **Inspeção de Usabilidade**, utilizando como referência as **10 Heurísticas de Nielsen**.  
O objetivo foi identificar problemas de usabilidade nas principais páginas e fluxos do site, analisando-os individualmente e consolidando-os em uma lista única com recomendações de melhoria.

As etapas aplicadas foram:
1. **Detecção individual** – cada integrante navegou pelo site e registrou problemas encontrados.  
2. **Coleção consolidada** – unificação dos registros, removendo duplicatas.  
3. **Discriminação** – classificação dos problemas como *defeitos* ou *falsos-positivos*.  
4. **Lista limpa final** – conjunto de problemas confirmados, com recomendações de correção e benefícios esperados.  

📌 **Observação importante**:  
Todas as **evidências visuais (prints e links)** estão organizadas no **Notion da equipe** e podem ser acessadas através do link:  
👉 [Acessar tabelas de inspeção no Notion](https://www.notion.so)  

---

## 1️⃣ Detecção Individual

### 👤 Inspetor: Bruno
| ID   | Localização                   | Descrição do Problema                                                                                                                         | Inspetor |
|------|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|----------|
| D-01 | Página inicial                | Excesso de informações visuais, fundo prejudica legibilidade. Navegação pouco clara (menu não estruturado).                                   | Bruno    |
| D-02 | Página de produtos            | Fundo com textura intensa, baixo contraste de cores. Ausência de filtros e organização visual clara.                                           | Bruno    |
| D-03 | Diretório de acessórios       | Lista extensa de links sem hierarquia clara; cores fortes sobre fundo degradê; ausência de breadcrumbs.                                       | Bruno    |
| D-04 | Página de suprimentos         | Lista vertical simples, desalinhada, fundo degradê. Ausência de filtros ou categorias.                                                         | Bruno    |
| D-05 | Página de componentes         | Lista curta, desorganizada, mistura de cores e textos; sem distinção clara entre informações principais e secundárias.                         | Bruno    |
| D-06 | Página de equipamentos        | Lista mal estruturada; textos pequenos; ausência de filtros obriga rolagem extensa.                                                           | Bruno    |
| D-07 | Página de produto             | Textos longos, contraste fraco, informações sem hierarquia clara.                                                                              | Bruno    |
| D-08 | Página de produto             | Texto pouco escaneável; área de preços com baixo contraste; sem comparação de modelos.                                                         | Bruno    |

---

### 👤 Inspetor: Cíntia
| ID   | Localização                  | Descrição do Problema                                                                                                 | Inspetor |
|------|------------------------------|-----------------------------------------------------------------------------------------------------------------------|----------|
| D-09 | Campo de busca               | Sem auto-completar ou sugestões; exige que o usuário memorize nomes técnicos.                                          | Cíntia   |
| D-10 | Layout geral                 | Navegação pouco intuitiva; ausência de breadcrumbs claros.                                                            | Cíntia   |
| D-11 | Link de email                | Abre janela para escolher aplicativo, mas leva a aba vazia do navegador.                                              | Cíntia   |
| D-12 | Página inicial               | Navegação inicial pouco intuitiva; não há menu principal claro, apenas listas extensas de links.                      | Cíntia   |
| D-13 | Tela inicial / Tela produto  | Lista apenas itens "populares"; sem breadcrumbs ou links de retorno.                                                   | Cíntia   |
| D-14 | Toda a página                | Ausência de suporte a erros: não há mensagens para busca inválida ou links quebrados.                                  | Cíntia   |
| D-15 | Toda a página                | Em caso de falha, não há mensagens de diagnóstico ou sugestões de correção.                                            | Cíntia   |
| D-16 | Rodapé                       | Não há FAQ, tutoriais ou documentação; apenas nota sobre catálogo impresso.                                           | Cíntia   |

---

### 👤 Inspetor: Nelio Tobias
| ID   | Localização        | Descrição do Problema                                                                                               | Inspetor     |
|------|--------------------|---------------------------------------------------------------------------------------------------------------------|--------------|
| D-17 | Barra de busca     | Sem auto-completar ou sugestões ao digitar; exige conhecimento prévio de termos técnicos.                           | Nelio Tobias |
| D-18 | Layout de categorias | Categorias em blocos de texto longos e pouco visuais; exige esforço adicional do usuário.                           | Nelio Tobias |
| D-19 | Página de produtos | Não há carrinho para adicionar múltiplos itens; leva direto à compra de apenas um produto.                          | Nelio Tobias |
| D-20 | Página geral       | Site não possui suporte a erros; não há mensagens informativas quando ocorre falha.                                 | Nelio Tobias |

---

### 👤 Inspetor: Carlos
| ID   | Localização              | Descrição do Problema                                                                                                                                   | Inspetor |
|------|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|----------|
| D-21 | Menu Principal           | Visualmente poluído, plano de fundo com cor que não destaca informações. Categorias pouco claras e sem imagens dos produtos.                           | Carlos   |
| D-22 | Pesquisa                 | Ausência de mensagem quando a busca não retorna resultados (apenas página vazia).                                                                       | Carlos   |
| D-23 | Menu de Navegação e Logo | Letras poluídas e logotipo sem contraste adequado, prejudicando a visualização.                                                                         | Carlos   |
| D-24 | Lista de Pesquisa        | Itens pesquisados não apresentam botão interativo para visualizar ou comprar, dificultando experiência de uso.                                          | Carlos   |
| D-25 | Site completo            | Ausência de botão acessível de “voltar páginas”; usuário precisa repetir ações para retornar.                                                           | Carlos   |
| D-26 | Fluxo de compra          | Usuário não encontra facilidade para comprar; é necessário contato externo (email/telefone).                                                            | Carlos   |
| D-27 | Lista de Itens           | Ausência de avaliação de outros usuários sobre produtos; isso diminui a atratividade e confiança na decisão de compra.                                   | Carlos   |

---

## 2️⃣ Coleção Consolidada
| ID  | Localização         | Descrição resumida                                                                | Origem (IDs)                         | Único/Repetido |
|-----|---------------------|------------------------------------------------------------------------------------|--------------------------------------|----------------|
| C-01 | Campo de busca      | Sem auto-completar/sugestões; exige conhecimento técnico.                         | D-09, D-17, D-22                     | Repetido |
| C-02 | Layout geral        | Navegação pouco intuitiva; ausência de breadcrumbs; categorias pouco visuais.     | D-10, D-12, D-18, D-21, D-23         | Repetido |
| C-03 | Página de produtos  | Fundo degradê, baixo contraste, ausência de filtros/carrinho.                     | D-02, D-19                           | Repetido |
| C-04 | Estrutura de listas | Listas extensas/confusas sem hierarquia visual clara.                             | D-03, D-04, D-05, D-06, D-13, D-24   | Repetido |
| C-05 | Páginas de produto  | Textos longos, pouco escaneáveis, baixo contraste, ausência de comparação.         | D-07, D-08                           | Repetido |
| C-06 | Suporte a erros     | Ausência de mensagens preventivas/diagnósticos em caso de falha.                  | D-14, D-15, D-20, D-22               | Repetido |
| C-07 | Rodapé/documentação | Ausência de FAQ, tutoriais e documentação acessível.                              | D-16                                 | Único |
| C-08 | Links de email      | Link abre aba vazia, falha de funcionalidade.                                     | D-11                                 | Único |
| C-09 | Navegação geral     | Falta de botão de voltar; navegação pouco fluida.                                 | D-25                                 | Único |
| C-10 | Fluxo de compra     | Usuário não encontra facilidade de finalizar compra sem contato externo.           | D-26                                 | Único |
| C-11 | Lista de itens      | Ausência de avaliação de usuários para apoiar decisão de compra.                  | D-27                                 | Único |

---

## 3️⃣ Discriminação (Defeito ou Falso-positivo)
| ID   | Localização         | Descrição resumida                                              | Heurística principal        | Classificação |
|------|---------------------|------------------------------------------------------------------|-----------------------------|---------------|
| C-01 | Campo de busca      | Sem auto-completar/sugestões                                    | 6                           | Defeito |
| C-02 | Layout geral        | Navegação pouco intuitiva, ausência de breadcrumbs              | 1,6,8                       | Defeito |
| C-03 | Página de produtos  | Fundo degradê, baixo contraste, ausência de filtros/carrinho    | 1,3,4,7,8                   | Defeito |
| C-04 | Estrutura de listas | Listas confusas, sem hierarquia visual clara                    | 4,6,8                       | Defeito |
| C-05 | Páginas de produto  | Textos longos, pouco escaneáveis, sem comparação                | 6,7,8                       | Defeito |
| C-06 | Suporte a erros     | Ausência de mensagens ou diagnósticos de erro                   | 5,9,10                      | Defeito |
| C-07 | Rodapé/documentação | Ausência de FAQ e tutoriais                                     | 10                          | Defeito |
| C-08 | Links de email      | Links quebrados abrem abas vazias                               | 9                           | Defeito |
| C-09 | Navegação geral     | Falta de botão de voltar                                        | 3                           | Defeito |
| C-10 | Fluxo de compra     | Processo exige contato externo (email/telefone)                 | 7,10                        | Defeito |
| C-11 | Lista de itens      | Ausência de avaliação de usuários                               | 1,2                         | Defeito |

---

## 4️⃣ Lista Limpa Final
| ID   | Localização         | Problema resumido                                   | Heurística | Recomendação de Correção | Benefício Esperado |
|------|---------------------|-----------------------------------------------------|------------|--------------------------|--------------------|
| L-01 | Campo de busca      | Sem auto-completar/sugestões                        | 6          | Implementar autocomplete e sugestões. | Facilita navegação e reduz esforço de memória. |
| L-02 | Layout geral        | Ausência de breadcrumbs, categorias pouco visuais   | 1,6,8      | Incluir breadcrumbs e menus claros. | Melhora orientação e reduz frustração. |
| L-03 | Página de produtos  | Fundo degradê, baixo contraste, sem filtros/carrinho| 1,3,4,7,8  | Melhorar contraste, filtros e carrinho. | Melhora clareza e eficiência. |
| L-04 | Estrutura de listas | Listas confusas e mal organizadas                   | 4,6,8      | Reorganizar listas com hierarquia. | Facilita leitura e reduz erros. |
| L-05 | Páginas de produto  | Textos longos, pouco escaneáveis, sem comparação    | 6,7,8      | Melhorar escaneabilidade e comparação de produtos. | Apoia decisão de compra. |
| L-06 | Suporte a erros     | Ausência de mensagens e diagnósticos                | 5,9,10     | Incluir mensagens de erro claras e preventivas. | Reduz falhas e aumenta confiança. |
| L-07 | Rodapé/documentação | Ausência de FAQ e documentação                      | 10         | Adicionar seção de ajuda e FAQ. | Apoio ao usuário e redução de suporte. |
| L-08 | Links de email      | Links quebrados abrem abas vazias                   | 9          | Corrigir links e validar destino. | Evita frustração e perda de tempo. |
| L-09 | Navegação geral     | Ausência de botão de voltar                         | 3          | Adicionar botão de retorno acessível. | Facilita navegação e reduz retrabalho. |
| L-10 | Fluxo de compra     | Necessidade de contato externo para concluir compra | 7,10       | Implementar checkout funcional no site. | Reduz barreiras e melhora eficiência. |
| L-11 | Lista de itens      | Ausência de avaliações de usuários                  | 1,2        | Incluir sistema de reviews/avaliações. | Aumenta confiança e credibilidade. |

---

## ✅ Conclusão
A inspeção de usabilidade com quatro inspetores revelou **11 problemas consolidados** que impactam gravemente a experiência do usuário.  
As falhas mais recorrentes estão ligadas a:  
- **Navegação confusa** (ausência de breadcrumbs, excesso de listas mal organizadas).  
- **Falta de recursos básicos de e-commerce** (carrinho, checkout, comparações, avaliações de usuários).  
- **Deficiências visuais e estéticas** (baixo contraste, textos longos, fundo degradê).  
- **Ausência de suporte a erros e documentação** (mensagens de erro, FAQ, tutoriais).  

As recomendações propostas trazem soluções viáveis que, se implementadas, aproximariam o site PNWX de um padrão de usabilidade mais moderno, confiável e eficiente.  

📌 Evidências completas (prints e tabelas) estão disponíveis no **Notion da equipe**:  
👉 [Acessar tabelas e prints no Notion](https://www.notion.so)
