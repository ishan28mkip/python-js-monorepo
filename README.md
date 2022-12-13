# python-js-monorepo
A repository to instantly start and deploy side projects or startup mvp.

Reasoning for creation,
This is made for projects that don't wish to deploy and manage things on AWS or some cloud provider. Creating things on cloud is overkill for a small
project / initial stage of startup, someone should be able to just rent out an ec2 / digital ocean droplet and be able to deploy in minutes and get started.

An initial project / startup should focus on just writing business logic and not spend time on deploying or setting up dx. This is just one opiniated way.

1. Should have some way to easily get ssl certificate which renews automatically.
2. Should be a monorepo but everyone should not be required to setup everything, but should be able to run nonetheless without having expertise.
3. Monorepo should be easily managed.
4. Should be integrated with github and updates on main should auto deploy, it would be better is staging and prod track main and release branches.
5. Should be dockerized and env and network should be effortless.
6. Package dependency should be handled using poetry for python and pnpm for js.
7. Ideally local and prod should both run on docker containers so that dev and prod env is as similar as possible.
8. A reverse proxy should exist that efforlessly handles proxying requests.
9. Data science should be a breeze. With all libraries setup and easy setup. Some way to deploy model training and deployment somewhere.
10. Easy way to access thrid party AI endpoints.
11. Basic things like auth ready to go.
12. Data engineering should be easy and visual.
