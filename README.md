# PyCon Africa
The Divio Cloud project repository for the PyCon Africa website

## About the repository

The PyCon Africa website runs on [Divio Cloud](https://divio.com). The Divio Cloud Control Panel dashboard for the project
is available to members of the web team.


## How to use the repository

Commits landing on the ``master`` branch can be deployed to the project's *Test* server, and subsequently to the *Live*
server. Deployments are performed on the [website dashboard](https://control.divio.com/control/4037/edit/63735), or by
running ``divio project deploy test`` or ``divio project deploy live`` locally.


## How to work on the project

### Join the organisation on Divio Cloud

[Sign up](https://control.divio.com/auth/register/) (accounts are free).

Ask the web team to add you to the Python Africa organisation on Divio Cloud as a collaborator.

### Install the necessary components

These include:

* the [Divio desktop app](http://divio.com/app/) - installing this will install the other components automatically,
  so start here
* Docker
* the Divio CLI
* Git


### Develop locally

Set up the project locally, either using the Divio app or:

    divio project setup pycon-africa

Run the project locally, either using the Divio app or:

    docker-compose up

When you are happy with your changes, push them to a branch for review, and make a pull request.
