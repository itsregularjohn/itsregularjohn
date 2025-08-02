# Hi, I'm JP

I'm a software architect who still writes code. I specialize in building infrastructure that scales when it has to, stays cheap when it can, and holds up under pressure. I've been doing this for 5+ years.

Here I'm documenting and sharing real-world architecture, tools I believe in, and projects I've built.

## Featured Work

### Enterprise AWS + EKS Architecture with Terraform
[Production-ready EKS setup](https://github.com/itsregularjohn/terraform-aws-enterprise-eks) based on AWS best practices with my own battle-tested decisions.

This started as a personal reference — I've used this structure to handle large-scale events in production and kept improving it. It's designed to be modular and practical for real teams.

- Multi-account layout based on AWS Prescriptive Guidance
- Least-privilege IAM, encrypted storage, all features I could add
- tfsec/trivy checks for compliance
- Avoids common pain points I've identified: few EKS managed addons, secrets are loaded from Secrets Manager instead of tfvars, and others

---

### Nano – Micro SaaS Starter
[Lean SaaS framework](https://github.com/itsregularjohn/nano) built to keep costs low until revenue comes, built to test new ideas quickly based on learnings from Lean Startup by Eric Ries.

- Uses libraries and patterns that requires low maintanence, fits nicely with Lambda and can scale well when needed: Hono, Zod, Stripe without Webhooks, Google OAuth. 
- Relies on Hono JSX and HTMX to dynamic content. No React. (Use Alpine.js if you really need something more)
- Simple auth, routes structure, billing setup that relies on Stripe Customer Portal.

---

### Notes  
[notes.mrjp.xyz](https://notes.mrjp.xyz) – Technical writing and architecture notes.

I publish short, opinionated explanations on tools and decisions that matter to me. Inspired by the idea that [concise explanations accelerate progress](https://stephango.com/concise). You'll find my takes on Zod, Vite, k6, Terraform, GraphQL, and more.

Structured with Obsidian, deployed with Gatsby + Netlify. Symlinked vault let me push external notes directly to the blog.

---

## About Me

I live in São Paulo, Brazil. I'm available for contract, freelance, or part-time work — open to negotiation depending on the scope.

If you're building something serious and need help, I'm interested.

- Technical writing: [notes.mrjp.xyz](https://notes.mrjp.xyz)
- LinkedIn: [itsregularjohn](https://www.linkedin.com/in/itsregularjohn/)
- Support my work: [Buy me a coffee](https://coff.ee/itsregularjohn)
