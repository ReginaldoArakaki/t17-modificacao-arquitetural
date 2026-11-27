# T17 · Modificação arquitetural: do método ad hoc ao ATAM/SEI

Turma T17 (2026.2B) · Prof. Reginaldo Arakaki · Escola Politécnica da USP

Nesta aula, cada grupo atua como consultoria sobre um sistema com problemas, em duas rodadas: primeiro pelo **método ad hoc**, com a experiência e a pressa da equipe; depois pelo **ATAM/SEI**, partindo dos objetivos de negócio. No fim, os grupos comparam o que mudou.

## Páginas das dinâmicas

| Dinâmica | Página |
|---|---|
| Dinâmica 1 · Método ad hoc | https://reginaldoarakaki.github.io/t17-modificacao-arquitetural/d1-metodo-ad-hoc/ |
| Dinâmica 2 · ATAM/SEI, etapas E1 e E2 | https://reginaldoarakaki.github.io/t17-modificacao-arquitetural/d2-metodo-atam-sei/ |

**Importante:**

- Usem **um único navegador** por grupo do início ao fim. O preenchimento fica salvo nele.
- Ao final da Dinâmica 1, copiem o **código** e colem na Dinâmica 2.
- Ao terminar cada bloco, **levem o resultado para o quadro do grupo no Miro**: botão **Copiar texto** para colar como nota, ou print da tela (**Win + Shift + S** no Windows, **Cmd + Shift + 4** no Mac; depois **Ctrl/Cmd + V** no quadro). Cada bloco tem uma etiqueta que identifica o print.

## Grupos e casos

| Grupos | Caso |
|---|---|
| G1 e G2 | Mega-Sena na virada do ano: procura cerca de 1000 vezes maior, com horário de fechamento fixo |
| G3 e G4 | Trânsito automatizado sob ataque: semáforos manipulados por invasores |
| G5 | Logística de última milha: destinatários trocados na separação dos pacotes |

Os casos são cenários didáticos inspirados em situações reais; nomes e números são ilustrativos.

## Roteiro da aula (90 min)

| Bloco | Tempo | O que acontece |
|---|---|---|
| Conceito | 20 min | Etapas do ATAM e casos reais (Telefônica, Bradesco, Bradesco Automóveis) |
| Dinâmica 1 · Ad hoc | 30 min | Seguir o fluxo da Fig. 1: Define as ADRs → Implementa → Testa → Entrega |
| Dinâmica 2 · ATAM/SEI | 30 min | E1 (papéis e regras), E2 (business drivers e fluxos críticos) e ações com método |
| Consolidação | 10 min | Comparação entre os grupos com o mesmo caso, com a Fig. 3 |

### Dinâmica 1 · Método ad hoc

Vocês são especialistas contratados com pressa executiva. Sigam o fluxo do desenho (Fig. 1), caixa por caixa:

| Tempo | Caixa | O que registrar |
|---|---|---|
| 0–3 min | Leitura | Caso e fluxo |
| 3–13 min | Define as ADRs | Componentes envolvidos; até 6 alternativas de mudança com o "por quê"; como comunicar a mudança |
| 13–21 min | Implementa | Ordem de execução e responsáveis |
| 21–27 min | Testa | Testes funcionais; o que fazer se falhar (loop de correções e ajustes) |
| 27–30 min | Entrega | Entrega rápida; levar tudo ao Miro e copiar o código para a D2 |

### Dinâmica 2 · ATAM/SEI, etapas E1 e E2

Mesmo caso, mesma equipe. Agora primeiro o negócio, depois as ações.

| Tempo | Folha | Referência | Produto |
|---|---|---|---|
| 0–5 min | E1 · Apresentação do ATAM | Fig. 0 | Papéis (cliente/patrocinador, arquiteto, avaliadores, relator) e regras |
| 5–17 min | E2 · Business drivers | Fig. 0 | Objetivo, fluxos críticos, stakeholders, restrições, top 3 de atributos de qualidade, riscos |
| 17–27 min | Ações com método | Fig. 2 | Alternativas da D1 classificadas e novas ações pedidas pelos drivers |
| 27–30 min | Resumo e Miro | — | Resumo completo no quadro do grupo |

Critérios para cada ação (Fig. 2):

1. Prioridade de negócio: parte de um driver ou fluxo crítico.
2. Foco na arquitetura × código.
3. Mensurável: toda ação tem uma medida.
4. Riscos → monitoração e controle.
5. Cenários de arquitetura × testes de funções.
6. Medições estáticas e dinâmicas.
7. Código necessário e suficiente, com medição.

## Figuras

| Figura | Conteúdo |
|---|---|
| [Fig. 0](figuras/fig0-atam-fluxo-e1-e2.pdf) | Método com ATAM/SEI: fluxo e etapas E1 a E9 |
| [Fig. 1](figuras/fig1-fluxo-ad-hoc-especialista.pdf) | Método ad hoc com especialista |
| [Fig. 2](figuras/fig2-atam-comentado.pdf) | ATAM comentado: critérios e três blocos |
| [Fig. 3](figuras/fig3-dois-fluxos-ad-hoc-atam.pdf) | Dois fluxos: especialista × ATAM |

## Estrutura do repositório

```
d1-metodo-ad-hoc/     página da Dinâmica 1 + Fig. 1
d2-metodo-atam-sei/   página da Dinâmica 2 + Fig. 0 e Fig. 2
figuras/              Fig. 0 a Fig. 3 (PDF) e Fig. 3 (PNG)
index.html            página inicial com os links das dinâmicas
```

As páginas são HTML autocontido e também abrem direto do arquivo, sem servidor.

---

ATAM: Architecture Tradeoff Analysis Method (SEI/Carnegie Mellon). As figuras são anotações do professor; imagens de terceiros são usadas para ilustração e pertencem aos respectivos autores.
