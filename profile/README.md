# SENAI-IA

Organização única das turmas de **Inteligência Artificial do SENAI** (projeto nacional).
Todas as turmas, equipes e projetos vivem aqui, seguindo uma convenção de nomes que mantém tudo organizado e fácil de encontrar.

---

## 📚 Cursos

| Sigla  | Curso                                              |
|--------|----------------------------------------------------|
| `IAPD` | IA Aplicada à Produtividade no Desenvolvimento     |

> Novos cursos entram nesta tabela com uma sigla de 3 a 5 letras.

---

## 🏷️ Código da turma

Cada turma tem um código único, usado em times e repositórios:

```
{CURSO}-{ANO}T{N}
```

| Parte   | Significado                          | Exemplo |
|---------|--------------------------------------|---------|
| `CURSO` | Sigla do curso                       | `IAPD`  |
| `ANO`   | Dois últimos dígitos do ano de início | `26`    |
| `T{N}`  | Número da turma do curso naquele ano | `T1`    |

**Exemplo:** `IAPD-26T1` → 1ª turma de *IA Aplicada à Produtividade no Desenvolvimento* em 2026.

---

## 👥 Times

Os times seguem uma hierarquia: **turma → equipes**.

```
PROFESSORES                       ← instrutores
IAPD-26T1                         ← turma inteira
 ├── IAPD-26T1-E01                ← equipe 1
 ├── IAPD-26T1-E02 - Byte Bandits ← equipe 2, com apelido
 └── IAPD-26T1-E03
```

### Regras

1. **O código vem sempre primeiro e não muda:** `{TURMA}-E{NN}`, com dois dígitos (`E01`, `E02`, …, `E10`).
2. **Apelido é opcional** e vai **depois** do código, separado por ` - `:
   `IAPD-26T1-E02 - Byte Bandits`
3. **Escolham o apelido no início da turma.** Renomear o time muda o link e as menções (`@SENAI-IA/...`).
4. **A própria equipe edita o nome e o avatar.** Todos os integrantes são *maintainers* do seu time: em *Teams → seu time → Settings*, dá para colocar o apelido e trocar a foto. **Nunca apague nem altere o código** (`IAPD-26T1-E02`); times fora do padrão são corrigidos pelo professor.
5. **Avatar com bom senso:** imagem própria ou livre de direitos, sem conteúdo ofensivo.
6. **Mexa apenas no seu time.** Como *maintainer*, você pode adicionar à equipe colegas que já são membros da organização, mas não remova ninguém nem mude a equipe de alguém sem combinar com o professor.

---

## 📁 Repositórios

Repositórios também começam pelo código da turma, sempre em minúsculas e com hífens:

| Tipo                | Padrão                              | Exemplo                          |
|---------------------|-------------------------------------|----------------------------------|
| Projeto da equipe   | `{turma}-e{nn}-{projeto}`           | `iapd-26t1-e03-techstorebot`     |
| Materiais da turma  | `{turma}-materiais`                 | `iapd-26t1-materiais`            |
| Apoio do professor  | `{turma}-{projeto}`                 | `iapd-26t1-pagamentos-api`       |

- O apelido da equipe pode aparecer na descrição ou no README do repositório, **não no nome**.
- Ao fim da turma, os repositórios são **arquivados** (somente leitura) e permanecem como portfólio.

### Regras para criar um repositório

1. **Nome no padrão:** `{turma}-e{nn}-{projeto}`, tudo em minúsculas, com hífens, sem acentos nem espaços.
   O `{projeto}` deve ser curto e descritivo: `iapd-26t1-e04-chatbot-rh`.
2. **Vincule sua equipe logo após criar:** em *Settings → Collaborators and teams → Add teams*, adicione o time da sua equipe (ex.: `IAPD-26T1-E04`) com permissão **Admin**.
   Sem isso, seus colegas só conseguem **ler** o repositório.
3. **Conteúdo mínimo:**
   - **Descrição** preenchida (aparece na lista da organização).
   - **README** com objetivo do projeto, integrantes da equipe e como executar.
4. **Não dê acesso a outras equipes nem a pessoas de fora.** As demais equipes já podem ler tudo; escrita é só da própria equipe.
5. **Repositórios fora do padrão** são apontados pelo professor e devem ser corrigidos pela equipe.

---

## 📖 Materiais de aula

Materiais são publicados **somente pelos professores**. Alunos têm acesso de leitura.

| Repositório          | Conteúdo                                                                  |
|----------------------|---------------------------------------------------------------------------|
| `{turma}-materiais`  | Material **da turma**: slides, atividades e entregáveis de cada aula      |
| `{turma}-{projeto}`  | Repositórios **de apoio** criados pelo professor e usados nas atividades (ex.: uma API para exercícios de code review) |

Cada turma tem **um** repositório de materiais, com uma pasta por aula na raiz:

```
iapd-26t1-materiais/
 ├── 2026-10-19-iapd-26t1-s01-aula-01-ensinando-maquinas/
 │    ├── IAPD-26T1 - S01 - Aula 01 - 2026-10-19 - Ensinando maquinas.pdf
 │    ├── README.md        ← agenda, atividades e entregáveis da aula
 │    └── atividades/      ← uma subpasta por atividade
 ├── prompts/              ← prompts compartilhados (aceita Pull Request)
 └── skills/               ← skills compartilhadas (aceita Pull Request)
```

- **Nome da pasta:** `AAAA-MM-DD-{turma}-sNN-aula-NN-tema` (data, turma, semana, aula e tema).
- **`prompts/` e `skills/`** são as únicas pastas abertas a contribuição dos alunos, sempre por **Pull Request** a partir de um *fork* (alunos têm só leitura no repositório de materiais). O professor revisa e faz o merge.
- Encontrou um erro ou tem uma sugestão? Abra uma **issue** no repositório de materiais.

> Exemplo real: [iapd-26t3-materiais](https://github.com/SENAI-IA/iapd-26t3-materiais) e [iapd-26t3-pagamentos-api](https://github.com/SENAI-IA/iapd-26t3-pagamentos-api).

---

## 🧑‍💻 Trabalhos individuais

Atividades individuais ficam **dentro do repositório da equipe**, em uma pasta com o seu usuário do GitHub:

```
iapd-26t1-e04-chatbot-rh/
 ├── (projeto da equipe)
 └── individual/
      ├── seu-usuario/
      │    └── atividade-01/
      └── usuario-do-colega/
```

1. **Cada aluno mexe apenas na própria pasta.** A pasta dos colegas é somente leitura, por combinação da equipe.
2. **Trabalhe em uma branch própria:** `seu-usuario/atividade-01`, e leve para a `main` por **Pull Request**.
3. **Entrega:** o professor avalia o conteúdo da sua pasta ou o PR correspondente.

> O histórico de commits registra quem alterou cada arquivo.

---

## ✅ Resumo rápido

- Código da turma: `IAPD-26T1`
- Equipe: `IAPD-26T1-E03` (ou `IAPD-26T1-E03 - Apelido`)
- Repositório: `iapd-26t1-e03-meu-projeto`, com a equipe vinculada como **Admin**

Dúvidas? Fale com o time **@SENAI-IA/professores**.
