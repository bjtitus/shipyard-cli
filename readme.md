# Shipyard CLI
CLI client for [Shipyard](http://shipyard-project.com)

Note: This is under active development and is currently very limited in functionality.

# Building

* `make`

# Usage

When you first run (and any time you want to change endpoints) you will need to
log in to shipyard as follows:

`./shipyard login`
Enter:
URL
Username
Password
API Version

Once you run as above, Shipyard will cache the credentials in `$HOME/.shipyard.cfg`.
You can then run the Shipyard CLI without passing creds each time.

## Show Help

`./shipyard -h`

## Show Applications
`./shipyard show-applications`

## Show Application Details
`./shipyard show-applications --name <app-name>`

## Show Containers
`./shipyard show-containers`

## Show Container Details
`./shipyard show-applications --id <container-id>`

## Show Hosts
`./shipyard show-hosts`

## Show Host Details
`./shipyard show-hosts --name <short-name-of-host>`
