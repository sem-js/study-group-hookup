# webhooks-project

[![Join the chat at https://gitter.im/sem-js/hookup](https://badges.gitter.im/sem-js/hookup.svg)](https://gitter.im/sem-js/hookup?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
SEMjs study group project with CI, webhooks and IoT.

(see bottom of the file for current install instructions)

Project Objectives:
- Let people collaborate on a project that has all the basic components of a production web application
- Build a working web application
- learn github authentication
- learn how CI (continuous integration) works
- learn how to make a PR (pull request)
- learn to write and run unit tests
- practice a code review process

Requirements:
- This will be a basic scaffolding for a web system
- Repo/project name is negotiable!
- Core application should be very simple, we have decided to create a webhook system to trigger events from mobile devices and dispatch actions to IoT devices
- basic user flow (for the service):
    + mobile device triggers an event
    + this event sends a notification to the server
    + the server sees the event, and sends notifications to all registered devices
- basic user flow (for the frontend registration management):
    + authenticate with github
    + add/edit/delete device registrations
    + [need more details for this]

Project Components (need to decide on technologies to use):
- CI
- webhooks
- IoT
- UI/frontend
- build system

Simple UI will have:
- a button for authentication with github
- a simple management system to keep track of event registrations
- [need more details for this]

Questions [have we answered any of these?]:
- Where to host?
- Current Contributors:
   - miguelcastillo
   - heymark
   - matthewmorgan
   - mgmatola
   - daniellecloss
   - ravenwilde (twitter: @ravenwilde)
   - ![remy_ico](https://cloud.githubusercontent.com/assets/16939008/17646598/049ffe38-619f-11e6-9e20-c8905d8daffc.jpg) [asyalushnikova](https://github.com/asyalushnikova)
- What technology would we want to use? (see components above)
- where to get the hardware and what hardware to get?
   - briangenisio

proof of concept
- [Heroku Server Code](./heroku-server-example.js)
- [Example Client Code](./node-client-example.js)
- Webhook connects to https://young-fjord-53100.herokuapp.com/ece926d8c0356205276a45266d361161 and client receives event

------------------
Current install instructions for base client app:
- clone repo
- make sure you are in the base repo directory
- type `npm install`
- cd to the webhooks-app directory
- type `npm start`

This should get you to the basic create-react-app demo (currently, until we update it!)
