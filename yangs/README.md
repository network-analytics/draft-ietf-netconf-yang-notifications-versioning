```shell
# ln -s dependencies/ietf-subscribed-notifications@2019-09-09.yang ietf-subscribed-notifications.yang
# ln -s dependencies/ietf-yang-revisions@2022-11-29.yang ietf-yang-revisions.yang
# ln -s dependencies/ietf-yang-semver@2023-01-17.yang ietf-yang-semver.yang
# ln -s ietf-yang-push-revision-03.yang ietf-yang-push-revision.yang
$ pyang ietf-yang-push-revision.yang -f tree -p . --tree-line-length=70
$ pyang -f tree ietf-yang-push-revision.yang ietf-yang-push@2019-09-09.yang ietf-subscribed-notifications@2019-09-09.yang --tree-line-length=70 -p dependencies
```