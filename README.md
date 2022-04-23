### Goals for this year

[//]: # (List your major goals here! Sharing your goals with your manager & coworkers is really nice because it helps them see how they can support you in accomplishing those goals!)

- 2020

      Migrate the Golf product from Heroku to GCP (Docker integration, Helm chart, Terraform, Vault)  
      Helped Golf developers to get used to the new eco-system.
      In the meanwhile, I improved the CD pipeline based on their needs (ephemeral environment, logs etc)

      Red finalization, adding multiple features (Zoom integration, Zendesk queue...) and making it production ready. 
      Also refactored the whole project since it has been developped by an intern.

- 2021

      Developing the K8s citizen-operator to initialize citizen inside a K8s cluster (init namespace, role creation etc)
      This helped us to remove the init-namespace Tekton job out of the Helm chart 

      Improving the CD pipeline (multi-region, etc)

- 2022

      Integrated Kumo citizen with Vault v2 using External-secrets operator and deprecated the in house secret-fetcher
    
      Implements K8s auth backend in Vault v2 and K8s authentication for Citizen through the gaia-google-gke module + citizen-operator
 
      Refactor citizen-operator to take care of connecting a citizen to it's outer world: https://miro.com/app/board/uXjVORX9y-I=/
      
      Making LSID products reliable (Monitoring, alert, Scalability)
      Sharing basic ops knowledge with the LSID devs (K8s resources management, ArgoCD, Vault)


### Goals for next year

[//]: # (If it’s getting towards the end of the year, maybe start writing down what you think your goals for next year might be.)

- 2023

      Continue on working on making one-lightspeed, by standarizing ops practices, tools etc

### Projects

[//]: # (For each one, go through:)
[//]: # (    What your contributions were &#40;did you come up with the design? Which components did you build? Was there some useful insight like “wait, we can cut scope and do what we want by doing way less work” that you came up with?&#41;)
[//]: # (    The impact of the project – who was it for? Are there numbers you can attach to it? &#40;saved X dollars? shipped new feature that has helped sell Y big deals? Improved performance by X%? Used by X internal users every day?&#41;. Did it support some important non-numeric company goal &#40;required to pass an audit? helped retain an important user?&#41;)
[//]: # (    Remember: don’t forget to explain what the results of you work actually were! It’s often important to go back a few months later and fill in what actually happened after you launched the project.)

- Red

      Red is a Slack bot that integrate different tools to make incident management smoother, by integrating different tools together (Slack, Pager Duty, Jira, Zoom, Zendesk).
      It'has been initialy design by an intern, who left before I arrived. I took care of remove bugs and adding last features.

- Leeroy

      TODO

- Kumo

      TODO

- LSID (Auth-gateway, Api-gateway, Identity-service, Lightspeed-ID)

      TODO

### Collaboration & mentorship

[//]: # (Examples of things in this category:)
[//]: # (    Helping others in an area you’re an expert in &#40;like “other engineers regularly ask me for one-off help solving weird bugs in their CSS” or “quoting from the C standard at just the right moment”&#41;)
[//]: # (    Mentoring interns / helping new team members get started)
[//]: # (    Writing really clear emails/meeting notes)
[//]: # (    Foundational code that other people built on top of)
[//]: # (    Improving monitoring / dashboards / on call)
[//]: # (    Any code review that you spent a particularly long time on / that you think was especially important)
[//]: # (    Important questions you answered &#40;“helped Risha from OTHER_TEAM with a lot of questions related to Y”&#41;)
[//]: # (    Mentoring someone on a project &#40;“gave Ben advice from time to time on leading his first big project”&#41;)
[//]: # (    Giving an internal talk or workshop)

- Help Golf developers to acquire knowledge on GCP/K8s
- Always willing to give support to dev and share knowledge
- Bring ideas to split the Support tasks vs Plan tasks
- Run Scrum/Retro meetings

### Design & documentation

[//]: # (List design docs & documentation that you worked on)

[//]: # (    Design docs: I usually just say “wrote design for X” or “reviewed design for X”)
[//]: # (    Documentation: maybe briefly explain the goal behind this documentation &#40;for example “we were getting a lot of questions about X, so I documented it and now we can answer the questions more quickly”&#41;)

- [Leeroy](https://miro.com/app/board/o9J_lF3rcL8=/)
- [Kumo components explanation](https://miro.com/app/board/uXjVORX9y-I=/)
- [LSID infra](https://miro.com/app/board/uXjVOB7sRPU=/)

### Company building

[//]: # (This is a category we have at work – it basically means “things you did to help the company overall, not just your project / team”. Some things that go in here:)
[//]: # (    Going above & beyond with interviewing or recruiting &#40;doing campus recruiting, etc&#41;)
[//]: # (    Improving important processes, like the interview process or writing better onboarding materials)

### What you learned

[//]: # (Try listing important things you learned or skills you’ve acquired recently! Some examples of skills you might be learning or improving:)
[//]: # (    how to do performance analysis & make code run faster)
[//]: # (    internals of an important piece of software &#40;like the JVM or Postgres or Linux&#41;)
[//]: # (    how to use a library &#40;like React&#41;)
[//]: # (    how to use an important tool &#40;like the command line or Firefox dev tools&#41;)
[//]: # (    about a specific area of programming &#40;like localization or timezones&#41;)
[//]: # (    an area like product management / UX design)
[//]: # (    how to write a clear design doc)
[//]: # (    a new programming language)

[//]: # (It’s really easy to lose track of what skills you’re learning, and usually when I reflect on this I realize I learned a lot more than I thought and also notice things that I’m not learning that I wish I was.)

### Outside of work

[//]: # (It’s also often useful to track accomplishments outside of work, like:)
[//]: # (    blog posts)
[//]: # (    talks/panels)
[//]: # (    open source work)
[//]: # (    Industry recognition)

[//]: # (I think this can be a nice way to highlight how you’re thinking about your career outside of strictly what you’re doing at work.)

[//]: # (This can also include other non-career-related things you’re proud of, if that feels good to you! Some people like to keep a combined personal + work brag document.)

### General prompts

[//]: # (If you’re feeling stuck for things to mention, try:)
[//]: # (    If you were trying to convince a friend to come join your company/team, what would you tell them about your work?)
[//]: # (    Did anybody tell you that you did something well recently?)
