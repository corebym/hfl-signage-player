React Digital Signage Player
============================

Digital signage player written by Henrik Franciscus Leppä

Main technologies:
- [Express.js 4](https://expressjs.com/)
- [Material-UI v1](https://material-ui-next.com/)
- [Node.js](https://nodejs.org/)
- [PouchDB](https://pouchdb.com/)
- [React.js](https://reactjs.org/)
- [React Router 4](https://github.com/ReactTraining/react-router)
- [Redux](https://redux.js.org/)

This project is made up of 3 subprojects:
- [Back-end](./back-end/)
- [Front-end](./front-end/)
- [Management UI](./management-ui/)


Getting Started / Installation
------------------------------

1. Setup the environment.

   This project has only been tested to work on the following environment:
   - Operating system: Ubuntu 16.04.3 LTS Desktop AMD64
   - Run-time environment: Node.js 8.9.4
     - I found the ["Installing Node.js via package manager"][Node.js
       installation] instructions to be the easiest way to install it.
       - To use this method however, you first need to install `curl` with:
         ```
         sudo apt-get install curl
         ```
   - Web browser: Mozilla Firefox (latest)
2. Start [Back-end](./back-end/).
3. Start [Management UI](./management-ui/), and create some signs, playlists and
   (optionally) upload some files.
4. Start [Front-end](./front-end/) and open a playlist.


Workflow
--------

This project uses [git-flow] with default settings.


Copyright
---------

Copyright © 2018 Henrik Franciscus Leppä

All rights reserved.


[git-flow]: https://github.com/nvie/gitflow
[Node.js installation]: https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions
