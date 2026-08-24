<div align="center">
  <img src="assets/01-detection.svg" width="100%" alt="Enzo Frazão — Backend &amp; Applied AI Engineer, Full-Stack Developer. Stack: PHP, Laravel, Java, Spring Boot, n8n, Python, Docker.">
</div>

I build backend systems at the intersection of public services, automation, and applied AI.

At STC/MA, I develop digital workflows for public transparency. At SafeWork, I lead the development of a computer-vision platform for workplace safety. In both, I work across the full lifecycle, from requirements to deployment.

**Currently** — full-stack developer at the **Maranhão State Transparency Office (STC/MA)** · founder of **SafeWork**<br>
**Languages** — Portuguese (native) · English (C1) · French (A2)

<details>
<summary>Sobre mim (PT-BR)</summary>

<br>

Desenvolvo sistemas que unem backend, automação e IA aplicada.

Na STC/MA, desenvolvo fluxos digitais para transparência pública. Na SafeWork, lidero o desenvolvimento de uma plataforma de visão computacional para segurança do trabalho. Nos dois contextos, atuo em todo o ciclo, dos requisitos à implantação.

**Atualmente** — desenvolvedor full-stack na **Secretaria de Transparência e Controle do Maranhão (STC/MA)** · fundador da **SafeWork**<br>
**Idiomas** — português (nativo) · inglês (C1) · francês (A2)

</details>

## Selected work

**Agiliza Transparência** — *Maranhão State Transparency Office (STC/MA)* · `closed source`<br>
I designed and developed Agiliza Transparência end to end, replacing a manual, spreadsheet-and-paperwork transparency data collection process with a digital workflow. The Office opens a collection cycle from a semantic catalogue and distributes it to the state's managing units, each with its own deadline and extensions; submissions are checked structurally on upload, optionally reviewed by a focal point before they arrive, and every change lands in an append-only audit trail.

<details>
<summary>Ver em português</summary>

<br>

**Agiliza Transparência** — *Secretaria de Transparência e Controle do Maranhão (STC/MA)* · `código fechado`<br>
Projetei e desenvolvi o Agiliza Transparência de ponta a ponta, substituindo um processo manual, baseado em planilhas e documentos, por um fluxo digital. A Secretaria abre um ciclo de coleta a partir de um catálogo semântico e o distribui às unidades gestoras do Estado, cada uma com seu prazo e possíveis prorrogações; os envios são verificados estruturalmente, podem passar pela revisão de um ponto focal e toda alteração é registrada em uma trilha de auditoria na qual os registros não são sobrescritos.

</details>

<div align="center">
  <img src="assets/03-agiliza-stack.svg" width="100%" alt="Agiliza Transparência runs on-premise on state-owned hardware, open source, at zero licence cost, so the stack is drawn as a server rack: Traefik v3.6 as gateway, Keycloak 23 for SSO and IAM, Laravel 12 on PHP 8.2, PostgreSQL 17, a Next.js 16 client on React 19 and Tailwind 4, and Docker with Portainer and Playwright.">
</div>

**SafeWork** — *founder* · `closed source`<br>
As founder, I lead the team and built the functional MVP and backend that analyse CCTV footage exported from a client's recorder, detect missing PPE, and turn detections into a workplace-safety compliance report. Detection runs in batches on serverless GPU, and a missing helmet is a rule derived over the person, head and helmet classes rather than a class of its own — so nobody is flagged just because the model failed to see a hat. PPE detection is the first product; the platform is being built to expand into other workplace-safety products.

<details>
<summary>Ver em português</summary>

<br>

**SafeWork** — *fundador* · `código fechado`<br>
Como fundador, lidero a equipe e construí o MVP funcional e o backend que analisam imagens de CCTV exportadas do gravador do cliente, identificam EPIs ausentes e transformam as detecções em um relatório de conformidade em segurança do trabalho. A detecção roda em lotes com GPU serverless, e a ausência de capacete é uma regra derivada das classes pessoa, cabeça e capacete — não uma classe isolada. A detecção de EPIs é o primeiro produto; a plataforma está sendo construída para expandir para outras soluções de segurança do trabalho.

</details>

<div align="center">
  <img src="assets/02-safework-stack.svg" width="100%" alt="SafeWork detection pipeline: FFmpeg normalises the footage, Modal runs YOLO11 on serverless GPU, FastAPI receives the signed webhook, PostgreSQL stores the events and Resend delivers the report. n8n spans the stages from the GPU batch through to delivery; Cloudflare R2 holds the media on both sides of detection.">
</div>

**WhatsApp Ombudsman Chatbot** — *Public Prosecutor's Office (MP/MA)* · `closed source`<br>
I designed and built this end-to-end first-line intake for the ombudsman channel on the official WhatsApp Cloud API. A deterministic state machine walks the citizen through consent under Brazil's data protection law, one of three modes — identified, confidential or anonymous — field-by-field validated data collection, a free-text report with attachments, and a review-and-edit pass before anything is submitted. Redis holds session state with a three-hour expiry, message deduplication and a distributed lock, so concurrent messages cannot corrupt a conversation.

<details>
<summary>Ver em português</summary>

<br>

**Chatbot da Ouvidoria via WhatsApp** — *Ministério Público do Maranhão (MP/MA)* · `código fechado`<br>
Projetei e construí de ponta a ponta este primeiro atendimento da Ouvidoria sobre a API oficial do WhatsApp Cloud. Uma máquina de estados determinística conduz o cidadão pelo consentimento da LGPD, pela escolha entre atendimento identificado, sigiloso ou anônimo, pela coleta validada dos dados, pelo relato com anexos e por uma etapa de revisão e edição antes do envio. O Redis mantém o estado da sessão por três horas, faz a deduplicação das mensagens e aplica um lock distribuído para impedir que mensagens concorrentes corrompam a conversa.

</details>

<div align="center">
  <img src="assets/04-ouvidoria-stack.svg" width="100%" alt="MP/MA ombudsman workflow census, counted from the export: 88 functional nodes — 35 code, 21 httpRequest, 10 if, 9 switch, 7 redis, 2 webhook, plus 3 noOp and 1 respondToWebhook. All 35 code nodes are JavaScript and every one of the 21 httpRequest nodes calls the WhatsApp Cloud API on Graph v19.0. Stack: n8n, WhatsApp Cloud API, Redis, Docker and Chatwoot.">
</div>

## Let's talk

<div align="center">
  <a href="https://www.linkedin.com/in/enzofrazaovencio/">
    <img src="assets/05-contact-linkedin.svg" width="49%" alt="LinkedIn — /in/enzofrazaovencio">
  </a>
  <a href="mailto:enzofrazaoengsoft@gmail.com">
    <img src="assets/05-contact-email.svg" width="49%" alt="Email — enzofrazaoengsoft@gmail.com">
  </a>
</div>
