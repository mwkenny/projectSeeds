# README
###  For use on Codenvy

create a workspace on codenvy
In Workspaces click Add Workspace

Add Name

Team personal

Select Stack Rails

Add or Import Project

select Git

https://github.com/2davecollins/golf.git

click ADD

click create

In worspace after it starts

in Terminal cd golf

type bundle install

wait for gems to be installed

type rake db:migrate

Run the project navigate to the url
navigate to route /items

Catalog should be empty
in terminal run the following command

cp app/assets/backup/development.sqlite3 db/

refresh browser and catalog should have items.

Click on Git menu on navbar and select Delete Repository.