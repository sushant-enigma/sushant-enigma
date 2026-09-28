### Sushant Nagil

Infrastructure engineer and team lead at Polaris Smart Metering in Jaipur, India. I build and run the cloud platform behind smart-metering rollouts for Indian state utilities. It carries data for 1.5 million meters on Kubernetes across AWS and OCI, with Kafka and MQTT handling the device traffic.

[Website](https://sushantnagil.com) · [LinkedIn](https://www.linkedin.com/in/sushant-nagil-3584881ba/) · [Resume (PDF)](https://sushantnagil.com/Sushant_Nagil_Resume.pdf) · nagilsushant@gmail.com

#### What I work on

- **Kubernetes:** four production EKS clusters with layered autoscaling: Karpenter for nodes, KEDA on Kafka lag, HPA for request services and Goldilocks-guided VPA. I also run the EKS version upgrades across five AWS accounts.
- **Messaging:** EMQX clusters for meter connections, and Kafka. I moved one production cluster from MSK to Strimzi on KRaft, and from ElastiCache to Valkey.
- **FinOps:** cost across a 24-account AWS estate, with about $45K a year in recurring savings.
- **Governance:** the landing zone, SCP guardrails, tag policies and SSO across the organisation.
- **On-call:** incident response and postmortems for the head-end and meter-data systems. A few of them are written up on [my site](https://sushantnagil.com/#incidents).

I lead a team of five: three DevOps engineers, a support engineer and a security engineer.

#### Certifications

- [AWS Certified Data Engineer – Associate](https://www.credly.com/badges/08d52b8c-f11f-43cf-b497-4d449ecc92f1), May 2026
- [Certified Kubernetes Administrator](https://www.credly.com/badges/fed0d324-7e61-4401-a86d-37cf9643d947), Dec 2025
- [HashiCorp Certified: Terraform Associate](https://www.credly.com/badges/ae7d1f4c-8d61-401d-884d-9f29099eb628), Sep 2025
- [AWS Certified Solutions Architect – Associate](https://www.credly.com/badges/f5bb537c-6ae9-4928-b4da-f7bbaf8d7316), Jul 2025

#### On GitHub

- [portfolio-site](https://github.com/sushant-enigma/portfolio-site): the source for sushantnagil.com. It's a static site on Cloudflare Workers with a strict Content Security Policy and Subresource Integrity. Its WebGL scene adapts to the visitor's GPU, and a daily workflow checks the live site from outside.
