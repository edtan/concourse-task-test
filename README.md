# concourse-task-test

Illustrates [issue #2182](https://github.com/concourse/concourse/issues/2182) in Concourse where parameters can't be passed into task files.

`fly -t local sp -p test -v repo=alpine -c pipeline.yml`

The various branches show different ways of trying to populate the REPO/repo parameter in task.yml.
