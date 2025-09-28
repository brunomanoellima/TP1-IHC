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
Todas as **evidências visuais (prints e links)** estão organizadas no **Notion da equipe** e podem ser acessadas pelo professor através do link:  
👉 [Acessar tabelas de inspeção no Notion](https://www.notion.so)  

---

## 1️⃣ Detecção Individual

### 👤 Inspetor: Bruno
| ID   | Localização                   | Descrição do Problema                                                                                                                         | Inspetor | Heurística Violada                                                                 |
|------|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|----------|------------------------------------------------------------------------------------|
| D-01 | Página inicial                | Excesso de informações visuais, fundo prejudica legibilidade. Navegação pouco clara (menu não estruturado).                                   | Bruno    | 2. Compatibilidade com o Mundo Real; 4. Consistência e Padrões; 8. Design Estético e Minimalista |
| D-02 | Página de produtos            | Fundo com textura intensa, baixo contraste de cores. Ausência de filtros e organização visual clara.                                           | Bruno    | 1. Visibilidade do Status; 7. Flexibilidade e Eficiência de Uso; 8. Design Estético e Minimalista |
| D-03 | Diretório de acessórios       | Lista extensa de links sem hierarquia clara; cores fortes sobre fundo degradê; ausência de breadcrumbs.                                       | Bruno    | 1. Visibilidade do Status; 6. Reconhecimento em vez de Lembrança; 8. Design Estético e Minimalista |
| D-04 | Página de suprimentos         | Lista vertical simples, desalinhada, fundo degradê. Ausência de filtros ou categorias.                                                         | Bruno    | 6. Reconhecimento em vez de Lembrança; 7. Flexibilidade e Eficiência de Uso; 8. Design Estético e Minimalista |
| D-05 | Página de componentes         | Lista curta, desorganizada, mistura de cores e textos; sem distinção clara entre informações principais e secundárias.                         | Bruno    | 4. Consistência e Padrões; 6. Reconhecimento em vez de Lembrança; 8. Design Estético e Minimalista |
| D-06 | Página de equipamentos        | Lista mal estruturada; textos pequenos; ausência de filtros obriga rolagem extensa.                                                           | Bruno    | 6. Reconhecimento em vez de Lembrança; 7. Flexibilidade e Eficiência de Uso; 8. Design Estético e Minimalista |
| D-07 | Página de produto             | Textos longos, contraste fraco, informações sem hierarquia clara.                                                                              | Bruno    | 6. Reconhecimento em vez de Lembrança; 7. Flexibilidade e Eficiência de Uso; 8. Design Estético e Minimalista |
| D-08 | Página de produto             | Texto pouco escaneável; área de preços com baixo contraste; sem comparação de modelos.                                                         | Bruno    | 6. Reconhecimento em vez de Lembrança; 7. Flexibilidade e Eficiência de Uso; 8. Design Estético e Minimalista |

---

### 👤 Inspetor: Cíntia
| ID   | Localização                  | Descrição do Problema                                                                                                 | Inspetor | Heurística Violada |
|------|------------------------------|-----------------------------------------------------------------------------------------------------------------------|----------|---------------------|
| D-09 | Campo de busca               | Sem auto-completar ou sugestões; exige que o usuário memorize nomes técnicos.                                          | Cíntia   | 6. Reconhecimento em vez de Lembrança |
| D-10 | Layout geral                 | Navegação pouco intuitiva; ausência de breadcrumbs claros.                                                            | Cíntia   | 1. Visibilidade do Status; 6. Reconhecimento em vez de Lembrança |
| D-11 | Link de email                | Abre janela para escolher aplicativo, mas leva a aba vazia do navegador.                                              | Cíntia   | 9. Prevenção de Erros; 10. Ajuda e Documentação |
| D-12 | Página inicial               | Navegação inicial pouco intuitiva; não há menu principal claro, apenas listas extensas de links.                      | Cíntia   | 2. Compatibilidade com o Mundo Real; 8. Design Estético e Minimalista |
| D-13 | Tela inicial / Tela produto  | Lista apenas itens "populares"; sem breadcrumbs ou links de retorno.                                                   | Cíntia   | 6. Reconhecimento em vez de Lembrança |
| D-14 | Toda a página                | Ausência de suporte a erros: não há mensagens para busca inválida ou links quebrados.                                  | Cíntia   | 9. Prevenção de Erros |
| D-15 | Toda a página                | Em caso de falha, não há mensagens de diagnóstico ou sugestões de correção.                                            | Cíntia   | 9. Prevenção de Erros; 10. Ajuda e Documentação |
| D-16 | Rodapé                       | Não há FAQ, tutoriais ou documentação; apenas nota sobre catálogo impresso.                                           | Cíntia   | 10. Ajuda e Documentação |

---

### 👤 Inspetor: Nelio Tobias
| ID   | Localização        | Descrição do Problema                                                                                               | Inspetor     | Heurística Violada |
|------|--------------------|---------------------------------------------------------------------------------------------------------------------|--------------|---------------------|
| D-17 | Barra de busca     | Sem auto-completar ou sugestões ao digitar; exige conhecimento prévio de termos técnicos.                           | Nelio Tobias | 6. Reconhecimento em vez de Lembrança |
| D-18 | Layout de categorias | Categorias em blocos de texto longos e pouco visuais; exige esforço adicional do usuário.                           | Nelio Tobias | 8. Design Estético e Minimalista |
| D-19 | Página de produtos | Não há carrinho para adicionar múltiplos itens; leva direto à compra de apenas um produto.                          | Nelio Tobias | 3. Controle e Liberdade do Usuário; 4. Consistência e Padrões; 7. Flexibilidade e Eficiência de Uso |
| D-20 | Página geral       | Site não possui suporte a erros; não há mensagens informativas quando ocorre falha.                                 | Nelio Tobias | 5. Prevenção de Erros |

---

## 2️⃣ Coleção Consolidada
| ID | Localização         | Descrição resumida                                                     | Origem (IDs)             | Único/Repetido |
|----|---------------------|-------------------------------------------------------------------------|--------------------------|----------------|
| C-01 | Campo de busca      | Sem auto-completar/sugestões; exige conhecimento técnico.              | D-09, D-17               | Repetido |
| C-02 | Layout geral        | Navegação pouco intuitiva; ausência de breadcrumbs.                    | D-10, D-12, D-18         | Repetido |
| C-03 | Página de produtos  | Fundo degradê, baixo contraste; ausência de filtros/carrinho.          | D-02, D-19               | Repetido |
| C-04 | Estrutura de listas | Páginas de acessórios/suprimentos/componentes pouco estruturadas.      | D-03, D-04, D-05, D-06   | Repetido |
| C-05 | Páginas de produto  | Textos longos, baixo contraste, ausência de comparação entre modelos.  | D-07, D-08, D-13         | Repetido |
| C-06 | Suporte a erros     | Não há mensagens preventivas/diagnósticos em caso de falha.            | D-14, D-15, D-20         | Repetido |
| C-07 | Rodapé/documentação | Ausência de FAQ, tutoriais e documentação acessível.                   | D-16                     | Único |
| C-08 | Links de email      | Link abre aba vazia, falha de funcionalidade.                          | D-11                     | Único |

---

## 3️⃣ Discriminação (Defeito ou Falso-positivo)
| ID | Localização         | Descrição resumida                                       | Heurística | Classificação |
|----|---------------------|-----------------------------------------------------------|------------|---------------|
| C-01 | Campo de busca      | Sem auto-completar/sugestões.                            | 6          | Defeito |
| C-02 | Layout geral        | Navegação pouco intuitiva, ausência de breadcrumbs.      | 1,6,8      | Defeito |
| C-03 | Página de produtos  | Fundo degradê, baixo contraste, ausência de filtros.     | 1,3,4,7,8  | Defeito |
| C-04 | Estrutura de listas | Páginas mal estruturadas e confusas.                     | 4,6,8      | Defeito |
| C-05 | Páginas de produto  | Textos longos, pouco escaneáveis, sem comparação.        | 6,7,8      | Defeito |
| C-06 | Suporte a erros     | Ausência de mensagens de erro ou prevenção.              | 5,9,10     | Defeito |
| C-07 | Rodapé/documentação | Sem FAQ ou tutoriais.                                    | 10         | Defeito |
| C-08 | Links de email      | Links quebrados abrem abas vazias.                       | 9          | Defeito |

---

## 4️⃣ Lista Limpa Final
| ID | Localização         | Problema resumido                                   | Heurística | Recomendação | Benefício Esperado |
|----|---------------------|-----------------------------------------------------|------------|--------------|--------------------|
| L-01 | Campo de busca      | Sem auto-completar/sugestões                        | 6          | Implementar autocomplete e sugestões. | Facilita navegação e reduz esforço de memória. |
| L-02 | Layout geral        | Ausência de breadcrumbs, navegação pouco clara      | 1,6,8      | Incluir breadcrumbs e menus claros. | Melhora orientação e reduz frustração. |
| L-03 | Página de produtos  | Fundo degradê, baixo contraste, sem filtros/carrinho| 1,3,4,7,8  | Melhorar contraste, filtros e carrinho. | Melhora clareza e eficiência. |
| L-04 | Estrutura de listas | Páginas confusas e mal organizadas                  | 4,6,8      | Reorganizar listas com hierarquia. | Facilita leitura e reduz erros. |
| L-05 | Páginas de produto  | Textos longos, pouco escaneáveis, sem comparação    | 6,7,8      | Melhorar escaneabilidade e comparação de produtos. | Apoia decisão de compra. |
| L-06 | Suporte a erros     | Ausência de mensagens e diagnósticos                | 5,9,10     | Incluir mensagens de erro claras e preventivas. | Reduz falhas e aumenta confiança. |
| L-07 | Rodapé/documentação | Ausência de FAQ e documentação                      | 10         | Adicionar seção de ajuda e FAQ. | Apoio ao usuário e redução de suporte. |
| L-08 | Links de email      | Links quebrados abrem abas vazias                   | 9          | Corrigir links e validar destino. | Evita frustração e perda de tempo. |

---

## ✅ Conclusão
A inspeção de usabilidade revelou **falhas críticas de navegação, organização da informação, ausência de recursos básicos (carrinho, filtros, comparação) e suporte a erros**.  
Essas questões afetam diretamente a eficiência, prevenção de erros e satisfação do usuário.  

As recomendações propostas oferecem caminhos para modernizar o site, tornando-o mais **intuitivo, confiável e alinhado a padrões modernos de usabilidade**.  

📌 Evidências completas estão disponíveis no **Notion do grupo**:  
👉 [Acessar tabelas e prints no Notion]([https://www.notion.so](https://spiky-fact-32a.notion.site/Inspe-o-de-Usabilidade-26ea7e3beb4381e4a5ace94a783b9d44?pvs=74))
