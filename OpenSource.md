# Open-Source Software at Flow

Flow fundamentally believes in open source software. We have benefited
incredibly from the contributions of others in building Flow. We
strongly encourage everybody at Flow to develop w/ open source in
mind; contributing to existing projects and sharing the software we
write publicly.

## Mechanics

1. Use the license approved by Flow
   - [MIT](https://github.com/flowcommerce/standards/LICENSE)

2. Make the project public in GitHub

We've really tried to make it as simple as possible to open source the
software you write. As the author, you decide whether or not to make
your project public. As Flow, we prefer that all projects be made
public.


## Helpful tips

  - Discuss your project with 1-2 team members - it's helpful to talk to both people familiar with your work and also people from other teams.
  - Update your documentation - and specifically your README - to be as clear as possible. Keep in mind that people will be learning about your project with no background. We recommend taking a look at the documentation for other open source projects you love as a template.
  - Clean up your config - specifically want to confirm there are no specifics of Flow's environment
  - Review the project to make sure there are no usernames, passwords, credentials, etc. If necessary, create a new repo.
  - Squash SCM commit history to eliminate risk of sensitive data.
  - Ask a friend or two to install / use your project just by reading the documentation.
  - If you'd like broader review of your project - send a note to tech-rfc or ask in chat.

## Promote Your Project

Open source projects require active promotion to gain traction with the community.

  - Post about your project to [tech.flow.io](https://tech.flow.io) (ask evangelist for help)
  - Tweet about your project
  - Create a talk that explores your project and deliver it at meetups, conferences, etc.
  - Create and comment on issues
  - Actively review / accept pull requests

## Examples of docs

  - [react project](https://facebook.github.io/react/)
  - [Promoting Storm](http://nathanmarz.com/blog/history-of-apache-storm-and-lessons-learned.html)
  - [apidoc](http://apidoc.me/doc/)

## FAQ

  - I want to use a different license. What do I do?

    Two options:

      1. You can just release your project in your personal git hub
         account and use the license you'd like.

      2. If you'd like Flow to officially adopt another license - open
         a pull request.

  - The MIT license doesn't address the fact that someone could fork
    our projects and completely change them. Should we make
    contributors submit a patch to feed their changes back to the
    original projects?

    No - users are free to fork code as they like - this is an
    integral part of open source! We will still own the canonical repo
    and the name. The code is free to run. Apple took KHTML as a
    starting point and built up WebKit--that helped everyone. Google
    and Oracle force you to hand over your copyright for any patch
    through a contributor agreement which we think stifles community
    involvement.


  - Who should be responsible for project maintenance?

    Each project should have at least one maintainer. A number of
    projects at Flow have adopted a [standard contribution process](https://github.com/flowcommerce/standards/Contributing.md)

  - Do we want to fork our projects and have public and private versions?

    Ideally no - we should just use our own open source projects just
    like we use any other open source project. Generally speaking, we
    suggest using environment variables or configuration files stored
    outside the repository as needed.
