# Backlog de Versões — skill-github-orquestracao

---

## v1.0 — 2026-06-01

**Tipo de alteração:** Criação
**Autorizado por:** victorarimatea
**Impacto:** non-breaking (nova skill, sem dependências existentes)
**Skills afetadas:** todas — esta skill orquestra operações que afetam
qualquer repositório do ecossistema

**Exposição de motivos:** Criação da skill de orquestração do ecossistema
DTD/SETIS. A necessidade surgiu da constatação, ao longo de múltiplas
sessões de trabalho, de que operações no ecossistema dependiam da memória
da sessão para garantir que nenhum arquivo fosse esquecido. Dois erros
concretos foram identificados e motivaram a criação:

1. README.md do dtd-setis não atualizado ao criar o tipo P e o P01
   (identificado em 2026-06-01)
2. Drift de versões entre sumario.md e backlog-versoes.md do M01
   (identificado retrospectivamente, ocorreu em múltiplas sessões)

A skill resolve isso com: leitura obrigatória do estado real antes de
agir; plano completo apresentado antes de qualquer execução; aprovação
explícita antes de solicitar token; verificação de consistência pós-
execução; e registro permanente de erros aprendidos que viram
verificações adicionais.

### Arquivos criados nesta versão
- `README.md` — apresentação pública do repositório
- `SKILL.md` — instruções completas v1.0 (380 linhas)
- `backlog-versoes.md` — este arquivo
