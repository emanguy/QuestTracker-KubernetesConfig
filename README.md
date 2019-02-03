# Quest Tracker Kubernetes Config

This repository contains the kubernetes resources necessary to deploy the full quest tracker webapp. Note that secrets containing passwords have been scrubbed from the repository.

Once the resources are deployed, you just need to `kubectl port-forward` the mongo container and use the instructions for getting mongo set up from the [Frontend API](https://github.com/emanguy/QuestTracker-FrontendApi/blob/master/README.md)
so you can actually log into the webpage as an admin.
