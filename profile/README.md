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
4. **Peça o apelido ao professor.** É ele quem aplica a mudança, para garantir que o código continue intacto.

---

## 📁 Repositórios

Repositórios também começam pelo código da turma, sempre em minúsculas e com hífens:

| Tipo                | Padrão                              | Exemplo                          |
|---------------------|-------------------------------------|----------------------------------|
| Projeto da equipe   | `{turma}-e{nn}-{projeto}`           | `iapd-26t1-e03-techstorebot`     |
| Material de aula    | `{turma}-aula-{AAAA-MM-DD}`         | `iapd-26t1-aula-2026-04-23`      |

- O apelido da equipe pode aparecer na descrição ou no README do repositório, **não no nome**.
- Ao fim da turma, os repositórios são **arquivados** (somente leitura) e permanecem como portfólio.

---

## ✅ Resumo rápido

- Código da turma: `IAPD-26T1`
- Equipe: `IAPD-26T1-E03` (ou `IAPD-26T1-E03 - Apelido`)
- Repositório: `iapd-26t1-e03-meu-projeto`

Dúvidas? Fale com o time **@SENAI-IA/professores**.
