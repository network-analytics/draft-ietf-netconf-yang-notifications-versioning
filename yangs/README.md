```shell
# ln -s dependencies/ietf-system-capabilities@2022-02-17.yang ietf-system-capabilities.yang
# ln -s dependencies/ietf-notification-capabilities@2022-02-17.yang ietf-notification-capabilities.yang
# ln -s dependencies/ietf-subscribed-notifications@2019-09-09.yang ietf-subscribed-notifications.yang
# ln -s dependencies/ietf-yang-revisions@2022-11-29.yang ietf-yang-revisions.yang
# ln -s dependencies/ietf-yang-semver@2023-01-17.yang ietf-yang-semver.yang
# ln -s dependencies/ietf-yang-library@2019-01-04.yang ietf-yang-library.yang
# ln -s ietf-yang-push-revision-09.yang ietf-yang-push-revision.yang
$ pyang -f tree ietf-yang-push-revision.yang ietf-system-capabilities.yang ietf-notification-capabilities.yang --tree-line-length=70 -p dependencies
$ pyang ietf-yang-push-revision.yang -f tree -p dependencies --tree-line-length=70
$ pyang -f tree ietf-yang-push-revision.yang ietf-yang-push@2019-09-09.yang ietf-subscribed-notifications@2019-09-09.yang --tree-line-length=70 -p dependencies
```