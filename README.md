<div align="center">

<!-- ─────────────── HEADER / BANNER ─────────────── -->

<h1>
  <code>pj/</code> &nbsp;paulo julio
</h1>

<p>
  <sub><b>PLATFORM ENGINEER</b> &nbsp;·&nbsp; <code>terraform</code> &nbsp;·&nbsp; <code>azure</code> &nbsp;·&nbsp; <code>aws</code> &nbsp;·&nbsp; <code>kubernetes</code> &nbsp;·&nbsp; <code>docker</code> &nbsp;·&nbsp; <code>ansible</code> &nbsp;·&nbsp; <code>github actions</code> &nbsp;·&nbsp; <code>linux</code></sub>
</p>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1200&color=C6F24E&center=true&vCenter=true&width=620&lines=Platform+Engineer+%2F%2F+infra+as+code;6+projetos+de+infra+com+CI+verde+em+nuvem+real;terraform+%C2%B7+azure+%C2%B7+aws+%C2%B7+kubernetes;OIDC+sem+secret+est%C3%A1tico+%C2%B7+deploy+com+gate+manual;estudando+%3E+AZ-104;code.+automate.+ship.+evolve." alt="typing" />
</a>

<br>

<!-- linha divisória em brand -->
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" height="2" alt="" />

</div>

<br>

## `01 //` IDENTITY

```typescript
const engineer = {
  handle:    "pmacoy",
  role:      "Platform Engineer",
  focus:     "infraestrutura versionada, pipelines que provam o que entregam",
  stack:     ["Terraform", "Azure", "AWS", "Kubernetes",
              "Docker", "Ansible", "GitHub Actions", "Linux"],
  building:  "azure-platform-engineering — plataforma interna de ponta a ponta",
  studying:  "AZ-104 · Cloud Native · GitOps",
  principle: "nada conta como pronto até o CI ficar verde contra a nuvem real",
  status:    "online"
};
```

<br>

## `02 //` PROJECTS

<sub>Todos os projetos abaixo foram aplicados contra nuvem real e só foram considerados prontos com o pipeline verde — não com o `plan` "parecendo certo".</sub>

<br>

<table>
<tr>
<td width="50%" valign="top">

### `→` azure-platform-engineering

<sub>Plataforma interna (IDP) construída em milestones. Landing zone com rede segmentada, Key Vault e Log Analytics; AKS e ACR provisionados por pipeline. Autenticação no Azure por <b>OIDC federado — zero secret estático</b> — e <code>apply</code> travado atrás de aprovação manual.</sub>

<p>
<img src="https://img.shields.io/badge/terraform-0B0B0C?style=flat-square&logo=terraform&logoColor=C6F24E" />
<img src="https://img.shields.io/badge/azure-0B0B0C?style=flat-square&logo=microsoftazure&logoColor=C6F24E" />
<img src="https://img.shields.io/badge/aks-0B0B0C?style=flat-square&logo=kubernetes&logoColor=C6F24E" />
<img src="https://img.shields.io/badge/oidc-0B0B0C?style=flat-square&logo=github&logoColor=C6F24E" />
</p>

<a href="https://github.com/Pmacoy/azure-platform-engineering"><img src="https://img.shields.io/badge/ver_repositório_→-0B0B0C?style=for-the-badge&labelColor=C6F24E&color=0B0B0C" /></a>

</td>
<td width="50%" valign="top">

### `→` secure-cicd-pipeline

<sub>Pipeline de CI/CD com as portas de segurança que normalmente ficam de fora: varredura de dependências, análise estática e deploy atrás de aprovação. O pipeline reprova o build quando deve reprovar.</sub>

<p>
<img src="https://img.shields.io/badge/github_actions-0B0B0C?style=flat-square&logo=githubactions&logoColor=C6F24E" />
<img src="https://img.shields.io/badge/devsecops-0B0B0C?style=flat-square&logo=snyk&logoColor=C6F24E" />
</p>

<a href="https://github.com/Pmacoy/secure-cicd-pipeline"><img src="https://img.shields.io/badge/ver_repositório_→-0B0B0C?style=for-the-badge&labelColor=C6F24E&color=0B0B0C" /></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### `→` k8s-canary-pipeline

<sub>Deploy canário em Kubernetes: a versão nova recebe uma fatia do tráfego, é medida, e só então assume tudo — ou volta atrás sozinha.</sub>

<p>
<img src="https://img.shields.io/badge/kubernetes-0B0B0C?style=flat-square&logo=kubernetes&logoColor=C6F24E" />
<img src="https://img.shields.io/badge/progressive_delivery-0B0B0C?style=flat-square&logo=argo&logoColor=C6F24E" />
</p>

<a href="https://github.com/Pmacoy/k8s-canary-pipeline"><img src="https://img.shields.io/badge/ver_repositório_→-0B0B0C?style=for-the-badge&labelColor=C6F24E&color=0B0B0C" /></a>

</td>
<td width="50%" valign="top">

### `→` full-observability-stack

<sub>Stack de observabilidade completa — métricas, logs e alertas — subindo por código, para responder "o que quebrou e desde quando" sem depender de ninguém lembrar.</sub>

<p>
<img src="https://img.shields.io/badge/prometheus-0B0B0C?style=flat-square&logo=prometheus&logoColor=C6F24E" />
<img src="https://img.shields.io/badge/grafana-0B0B0C?style=flat-square&logo=grafana&logoColor=C6F24E" />
</p>

<a href="https://github.com/Pmacoy/full-observability-stack"><img src="https://img.shields.io/badge/ver_repositório_→-0B0B0C?style=for-the-badge&labelColor=C6F24E&color=0B0B0C" /></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### `→` iac-terraform-ansible

<sub>Terraform provisiona a infraestrutura, Ansible configura o que roda dentro dela — a divisão de responsabilidade entre as duas ferramentas feita de forma explícita, não improvisada.</sub>

<p>
<img src="https://img.shields.io/badge/terraform-0B0B0C?style=flat-square&logo=terraform&logoColor=C6F24E" />
<img src="https://img.shields.io/badge/ansible-0B0B0C?style=flat-square&logo=ansible&logoColor=C6F24E" />
<img src="https://img.shields.io/badge/aws-0B0B0C?style=flat-square&logo=amazonwebservices&logoColor=C6F24E" />
</p>

<a href="https://github.com/Pmacoy/iac-terraform-ansible"><img src="https://img.shields.io/badge/ver_repositório_→-0B0B0C?style=for-the-badge&labelColor=C6F24E&color=0B0B0C" /></a>

</td>
<td width="50%" valign="top">

### `→` mcp-devops-agent

<sub>Servidor MCP expondo operações de DevOps como ferramentas consumíveis por um agente de IA — automação de plataforma na fronteira entre infraestrutura e LLM.</sub>

<p>
<img src="https://img.shields.io/badge/python-0B0B0C?style=flat-square&logo=python&logoColor=C6F24E" />
<img src="https://img.shields.io/badge/mcp-0B0B0C?style=flat-square&logo=anthropic&logoColor=C6F24E" />
</p>

<a href="https://github.com/Pmacoy/mcp-devops-agent"><img src="https://img.shields.io/badge/ver_repositório_→-0B0B0C?style=for-the-badge&labelColor=C6F24E&color=0B0B0C" /></a>

</td>
</tr>
</table>

<br>

<sub><b>Study-hub</b> — trilhas, experimentos e anotações dos estudos que sustentam os projetos acima. &nbsp;<a href="https://github.com/Pmacoy/Study-hub">abrir →</a></sub>

<br><br>

## `03 //` TECH_STACK

<sub>**CLOUD**</sub>

![Azure](https://img.shields.io/badge/Azure-0B0B0C?style=for-the-badge&logo=microsoftazure&logoColor=C6F24E)
![AWS](https://img.shields.io/badge/AWS-0B0B0C?style=for-the-badge&logo=amazonwebservices&logoColor=C6F24E)
![GCP](https://img.shields.io/badge/GCP-0B0B0C?style=for-the-badge&logo=googlecloud&logoColor=C6F24E)

<sub>**INFRASTRUCTURE_AS_CODE**</sub>

![Terraform](https://img.shields.io/badge/Terraform-0B0B0C?style=for-the-badge&logo=terraform&logoColor=C6F24E)
![Ansible](https://img.shields.io/badge/Ansible-0B0B0C?style=for-the-badge&logo=ansible&logoColor=C6F24E)

<sub>**CONTAINERS_&_ORCHESTRATION**</sub>

![Docker](https://img.shields.io/badge/Docker-0B0B0C?style=for-the-badge&logo=docker&logoColor=C6F24E)
![Kubernetes](https://img.shields.io/badge/Kubernetes-0B0B0C?style=for-the-badge&logo=kubernetes&logoColor=C6F24E)

<sub>**CI/CD_&_TOOLING**</sub>

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0B0B0C?style=for-the-badge&logo=githubactions&logoColor=C6F24E)
![Git](https://img.shields.io/badge/Git-0B0B0C?style=for-the-badge&logo=git&logoColor=C6F24E)

<sub>**OS_&_NETWORKING**</sub>

![Linux](https://img.shields.io/badge/Linux-0B0B0C?style=for-the-badge&logo=linux&logoColor=C6F24E)
![Networking](https://img.shields.io/badge/Networking-0B0B0C?style=for-the-badge&logo=cisco&logoColor=C6F24E)
![Nginx](https://img.shields.io/badge/Nginx-0B0B0C?style=for-the-badge&logo=nginx&logoColor=C6F24E)

<br>

## `04 //` CURRENTLY

```bash
> status report

[ ATIVO    ]  azure-platform-engineering
              M1 landing zone .................. entregue · CI verde
              M2 AKS + ACR ..................... entregue · CI verde
              M3 GitOps com Argo CD ............ em andamento
              M4 golden path (Backstage) ....... planejado
              M5 guardrails (policy) ........... planejado
              M6 observabilidade ............... planejado

[ ESTUDANDO ]  AZ-104 · Azure Administrator
[ PRÓXIMO   ]  CKA · Certified Kubernetes Administrator

> awaiting next challenge... █
```

<br>

## `05 //` SYSTEM_METRICS

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Pmacoy&show_icons=true&hide_border=false&bg_color=0B0B0C&title_color=C6F24E&text_color=F4F1EA&icon_color=C6F24E&border_color=2A2A2E&count_private=true" alt="stats" />
<img height="165" src="https://streak-stats.demolab.com?user=Pmacoy&theme=dark&background=0B0B0C&stroke=2A2A2E&ring=C6F24E&fire=C6F24E&currStreakLabel=C6F24E&sideLabels=F4F1EA&currStreakNum=F4F1EA&sideNums=F4F1EA&dates=8A8A90&border=2A2A2E" alt="streak" />

<br><br>

<img width="52%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pmacoy&layout=compact&hide_border=false&bg_color=0B0B0C&title_color=C6F24E&text_color=F4F1EA&border_color=2A2A2E&langs_count=8" alt="top langs" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Pmacoy&bg_color=0B0B0C&color=F4F1EA&line=C6F24E&point=C6F24E&area=true&area_color=C6F24E&hide_border=false&custom_title=commit%20activity%20//%20last%2031%20days" alt="activity graph" />

</div>

<br>

## `06 //` CONNECT

<p>
  <a href="https://www.linkedin.com/in/pauloajulio/">
    <img src="https://img.shields.io/badge/LinkedIn-0B0B0C?style=for-the-badge&logo=linkedin&logoColor=C6F24E" alt="linkedin" />
  </a>
  &nbsp;
  <a href="https://github.com/Pmacoy?tab=repositories">
    <img src="https://img.shields.io/badge/todos_os_repositórios-0B0B0C?style=for-the-badge&logo=github&logoColor=C6F24E" alt="all repos" />
  </a>
</p>

<br>

<div align="center">
  <sub><code>pj/</code> &nbsp;·&nbsp; <i>code. automate. ship. evolve.</i> &nbsp;·&nbsp; <img src="https://komarev.com/ghpvc/?username=Pmacoy&label=visitors&color=C6F24E&style=flat" alt="visitors" /></sub>
</div>
