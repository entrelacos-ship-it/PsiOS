# PsiOS

> O sistema operacional do seu consultório dentro do Claude Code.

Você acaba de instalar o PsiOS. Em alguns minutos, seu consultório vai
ter uma memória própria, uma identidade visual aplicada em tudo que
o sistema gerar, e 15 skills prontas pra fazer conteúdo, divulgação
ética, SEO e operação do dia a dia rodarem com você dirigindo.

Criado pela [Entrelaços Psicologia](https://entrelacospsicologia.com.br)
como base de mentoria pra psicólogas e psicólogos montarem sua própria
estrutura de IA — você clona, roda o `/instalar` e o sistema já sai
sabendo quem você é.

Bora voar.

---

## Ligando o sistema

Dois caminhos. Escolhe o que combina contigo.

### Pelo Claude (mais rápido)

Abre o Claude Code em qualquer pasta e cola:

```
Clona o https://github.com/entrelacos-ship-it/PsiOS.git na pasta atual,
entra nela e roda o /instalar.
```

Ele clona, entra na pasta nova e dispara a entrevista de setup. Você
só responde.

### Pelo terminal (mais previsível)

```
git clone https://github.com/entrelacos-ship-it/PsiOS.git
cd PsiOS
code .
```

Na janela do VS Code que abrir: terminal integrado → `claude` → `/instalar`.

---

Quando o `/instalar` terminar, renomeia a pasta `PsiOS/` pro nome do teu
consultório ou marca (fecha o VS Code, renomeia no Explorer/Finder, abre
de novo). A pasta não fica como "PsiOS" — ela é o teu consultório agora.

O `/instalar` roda uma vez só. Te entrevista sobre teu trabalho como
psicóloga(o), monta a memória e configura o sistema. Depois disso, é
só usar.

---

## O sistema

**Núcleo** — o jeito de operar o dia a dia
`/abrir` carrega o contexto antes de cada sessão de trabalho · `/salvar`
faz commit + push no GitHub · `/atualizar` varre o projeto e atualiza
a memória · `/novo-projeto` cria pasta isolada pra cada grupo, curso ou
iniciativa nova · `/mapear-rotinas` descobre o que você repete e transforma
em skill personalizada.

**Conteúdo e SEO** — vitrine pública do consultório
`/carrossel` cria carrosséis 1080×1350 com identidade da marca (com ou
sem foto IA) · `/publicar-tema` pega um tema e entrega artigo de blog +
carrossel + 3 legendas amarradas · `/seo` roda fluxo completo de 8 passos
(demanda, concorrência, GMB, on-page, conteúdo, ads, monitoramento, GEO)
· `/responder-avaliacoes` escreve respostas humanas pras avaliações do
Google · `/aprovar-post` publica blog + Instagram + Facebook num comando.

**Divulgação paga** — sempre dentro do Código de Ética do psicólogo (sem
promessa de resultado clínico, sem depoimento de paciente, sem
sensacionalismo)
`/anuncio-google` monta a campanha inteira em CSV pronto pra importar
no Google Ads Editor · `/relatorio-ads` lê os exports de Google + Meta
e devolve relatório semanal com alertas e recomendações.

**Produção** — ferramentas do dia a dia
`/analisar-dados` lê CSV/XLSX/PDF e gera resumo executivo (uso
administrativo — nunca dado clínico de paciente) ·
`/email-profissional` rascunha email a partir de contexto livre.

---

## A tese

IA não é uma ferramenta que seu consultório usa. É o sistema operacional em
que ele roda.

A diferença não é velocidade. É capacidade nova — uma psicóloga com IA
constrói o que antes exigia equipe inteira de marketing e gestão. Cada
processo que hoje roda em open loop (decide → executa → não mede → repete
cego) vira closed loop dentro do PsiOS (decide → executa → captura →
realimenta → ajusta sozinho).

O sistema não substitui você nem sua escuta clínica. Vira parte da
operação do seu consultório — a parte administrativa e de divulgação,
nunca a parte clínica.

---

## Como o PsiOS pensa

`_memoria/` é o cérebro. Tudo que importa do seu consultório mora aqui —
quem você é, como você fala, o que tá em foco essa semana. O Claude
lê isso antes de cada resposta. Quanto melhor a memória, melhor o sistema.

`identidade/` é o rosto. Cores, fontes, logo, padrão visual. Todo
carrossel, slide, peça que o sistema gera respeita isso.

`marketing/`, `saidas/` e `scripts/` são o resultado. O sistema produz,
versiona no GitHub, fica tudo seu.

**Importante:** o PsiOS é pra operação, divulgação e conteúdo do
consultório. Prontuário, dado de sessão e qualquer informação sigilosa
de paciente NUNCA entram nesse sistema — seguem o sigilo profissional e
o CFP fora daqui.

---

## Quando precisar

[entrelacospsicologia.com.br](https://entrelacospsicologia.com.br)
