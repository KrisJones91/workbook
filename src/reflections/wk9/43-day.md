# Day 43
__2/9/20__

## What is a Github action and how do they work?
Github actions are individual tasks that you can put together to customize your workflow. You create text files, known as workflows, in your repositories to create actions and those actions allow for continous development, integration, etc.

## What benefits do Github actions provide?
Github actions are beneficial in supporting projects and teams that are continuously developing and deploying projects regularly. It makes automating workflows and branch management easy.

## What types of trigger actions can a workflow use? What do they do?
You can trigger an action "on: push" so that when someone pushes to any branch of a project, the event will trigger your workflow. You can go more in depth with this action by "on: push: branches: -main:" so that you can specify when someone pushes to only the main branch your workflow will trigger.