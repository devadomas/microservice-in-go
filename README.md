# Microservice in Golang

Personal project to assemble microservice boilerplate in Golang based on my beliefs in code structure, architectural patterns, features that microservice should have, etc.

## Objectives
- [ ] Set the desired code structure
- [ ] Define logging
- [ ] Define monitoring (HTTP stats, APM)
- [ ] Define testing approach

### Note
> Everything is based on my beliefs and should be taken with good grain of salt. Every individual or team has their own "perfect" recipe of what works, and what doesn't. Project is dedicated to learn and share knowledge.

# Beliefs
- Little 3rd party dependencies
    - Standard library likely has 90% of needed features
    - Framework integration shouldn't dictate main domain of service
- Fitting Code structure for Golang(Clean code VS Domain Driven Design)
    - Domain shouldn't be impacted by 3rd parties
    - DTOs should be property whitelisted and used in it's only scope

# Sources
- Layout inspired by [go-lang-starndarts](https://github.com/golang-standards/project-layout) community
- ADR inspired by [Joel Parker Henderson](https://github.com/joelparkerhenderson/architecture-decision-record/tree/main)

# History

I started this project due my interest in Golang and passion for lean approach to ... basically life in general. Golang was on my radar for past 6 years. Due to my focus on tech management and primary expertise being in NodeJS, PHP and platform engineering, I never had a chance to try it out myself. I treat this project as a canvas for exploring the Golang and expression of my beliefs on what the "production-worthy" service should have.