<h1 align="center">Guilherme Alves</h1>
<p align="center">
  <strong>Back-End Developer</strong> · Go · TypeScript · Node.js<br/>
  Sistemas de automação industrial de dia. APIs e arquitetura de software o resto do tempo.
</p>

<p align="center">
  <a href="https://linkedin.com/in/g7a"><img src="https://skillicons.dev/icons?i=linkedin" height="40" alt="LinkedIn"/></a>
  <a href="https://github.com/guialves50"><img src="https://skillicons.dev/icons?i=github" height="40" alt="GitHub"/></a>
  <a href="https://x.com/guialves50"><img src="https://skillicons.dev/icons?i=twitter" height="40" alt="X"/></a>
  <a href="https://discord.gg/ymKcdRMURF"><img src="https://skillicons.dev/icons?i=discord" height="40" alt="Discord"/></a>
</p>

---

## Sobre

Desenvolvedor back-end e estudante de Engenharia de Software, no Brasil.

No trabalho, escrevo Python que conversa com CLPs baseados em Raspberry Pi via **Modbus TCP** — leitura de temperatura de fornos e secadores, acionamento de equipamento por coils e holding registers, e persistência dos dados para análise. Sistema em produção, chão de fábrica, sem margem para "funciona na minha máquina".

Fora dele, estou reconstruindo minha base de engenharia de software do zero: fundamentos de rede, protocolos, bancos de dados, concorrência e arquitetura — na ordem certa, escrevendo o primeiro rascunho de cada solução sem IA antes de pedir revisão.

```go
type Dev struct {
    Nome      string
    Foco      []string
    Estudando string
    Regra     string
}

func main() {
    g := Dev{
        Nome:      "Guilherme",
        Foco:      []string{"APIs", "Arquitetura", "Sistemas distribuídos"},
        Estudando: "Go + fundamentos de back-end",
        Regra:     "entender antes de automatizar",
    }
    _ = g
}
```

---

## Stack

**Linguagens**

[![](https://skillicons.dev/icons?i=go,ts,js,python,java)](https://skillicons.dev)

**Back-end & Frameworks**

[![](https://skillicons.dev/icons?i=nodejs,nestjs,express,spring,prisma)](https://skillicons.dev)

**Dados**

[![](https://skillicons.dev/icons?i=postgres,mongodb,redis)](https://skillicons.dev)

**Infra & Ferramentas**

[![](https://skillicons.dev/icons?i=docker,linux,git,github,githubactions,postman,raspberrypi)](https://skillicons.dev)

**Também trabalho com:** Modbus TCP, `pymodbus`, integração com CLPs, REST, arquitetura limpa, testes automatizados.

---

## Projeto principal: PixelBank

Carteira digital com **ledger de partidas dobradas** — o projeto-âncora que evolui junto com meus estudos.

A ideia é simples de descrever e difícil de acertar: todo movimento de dinheiro é registrado como um par débito/crédito, o saldo nunca é um campo mutável e sim uma projeção do ledger, e o sistema precisa fechar sempre em zero. É onde eu exercito, em ordem crescente de dificuldade:

- Modelagem de domínio financeiro e invariantes contábeis
- Transações, isolamento e concorrência em PostgreSQL
- Idempotência e consistência em operações de saldo
- Autenticação, autorização e trilha de auditoria
- Observabilidade, testes de integração e deploy containerizado

> Em construção pública, uma fase de cada vez.

---

## Roadmap de estudos

Sigo um roadmap próprio de **11 fases**, baseado nas trilhas Backend e Go do roadmap.sh, com regras de disciplina fixas:

- Primeiro rascunho **sempre sem IA**
- Técnica de Feynman para fechar cada tópico
- Code review reverso: eu explico o código antes de aceitar sugestão

| Fase | Tema | Status |
|:----:|------|:------:|
| 0 | Lógica de programação e pseudocódigo | ✅ |
| 1 | Fundamentos da web (HTTP, DNS, hospedagem, browsers) | 🔄 |
| 2 | Linguagem: Go | ⏳ |
| 3 | Bancos de dados relacionais | ⏳ |
| 4 | APIs, autenticação e segurança | ⏳ |
| 5 | Testes e qualidade | ⏳ |
| 6 | Caching, filas e mensageria | ⏳ |
| 7 | Containers, CI/CD e deploy | ⏳ |
| 8 | Observabilidade | ⏳ |
| 9 | Escalabilidade e sistemas distribuídos | ⏳ |
| 10 | Arquitetura de software | ⏳ |

Cada sessão de estudo vira nota estruturada no meu Second Brain (Obsidian, estrutura PARA própria), com comandos automatizados de ingestão e consulta.

---

## Outros projetos

**Jarvis** — assistente de voz para escritório rodando em Raspberry Pi como orquestrador, com Claude API como camada de decisão: wake word, STT com Whisper, TTS com Piper, agentes para acesso a arquivos em rede e integração com Home Assistant + Broadlink para controle de IoT.

**Automação industrial** — refatoração de um sistema Modbus TCP em produção: migração de versão do `pymodbus`, suporte a context manager, padronização de tratamento de erro e logging estruturado.

---

## Estatísticas

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=guialves50&theme=dracula&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=guialves50&theme=dracula&hide_border=true&include_all_commits=true&count_private=true&layout=compact" />
</p>

<p align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=guialves50&theme=dracula&hide_border=true" />
</p>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/guialves50/guialves50/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/guialves50/guialves50/output/pacman-contribution-graph.svg">
  <img alt="Pac-Man contribution graph" src="https://raw.githubusercontent.com/guialves50/guialves50/output/pacman-contribution-graph.svg">
</picture>

---

<p align="center">
  <i>Aberto a conversas sobre back-end, Go, sistemas embarcados e arquitetura.</i>
</p>
