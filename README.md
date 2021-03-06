# Unofficial Snap Packaging for Universal Update Utility
This is the unofficial snap packaging for Universal Update Utility, [Snaps are universal Linux packages](https://snapcraft.io).

Refer [snap/README.md](snap/README.md) for user-oriented information.

## Project obsoletion notice

The packaging work of this snap is now transferred to the upstream, please refer to [NXPmicro/mfgtools: Freescale/NXP I.MX Chip image deploy tools.](https://github.com/NXPmicro/mfgtools) for more info.

This project will be archived and serve for educational purposes.

## Remaining Tasks
Snapcrafters ([join us](https://forum.snapcraft.io/t/join-snapcrafters/1325)) are working to land snap install documentation and the [snapcraft.yaml](https://github.com/Lin-Buo-Ren/snapcrafters-template-plus/blob/master/snap/snapcraft.yaml) upstream so Universal Update Utility can authoritatively publish future releases.

- [x] Create _snap_name_-snap (or any valid name you prefer) repository via the [Use this template](https://github.com/Lin-Buo-Ren/snapcrafters-template-plus/generate) button above
  - It is recommended to *avoid forking the template repository* unless you're working on the template itself because you can only fork a repository once
- [x] Update the description of the repository
- [x] Update logos and references to `Universal Update Utility`, `universal-update-utility` and other placeholder names in `README.md`, `snap/README.md`, and `snap/snapcraft.yaml`
- [x] Add upstream contact information to this `README.md`
- [x] Create a snap that runs in `devmode`, [or in `classic` confinement if that's not possible](https://forum.snapcraft.io/t/subtle-differences-between-devmode-and-classic-confinement-snaps/7267)
    - [ ] If the snap must be packaged under `classic` confinement, file a [classic confinement request](https://forum.snapcraft.io/t/process-for-reviewing-classic-confinement-snaps/1460) topic in the Snapcraft Forum, under the `store` topic category - [template](https://github.com/Lin-Buo-Ren/snapcrafters-template-plus/wiki/Classic-Confinement-Request-Template) - [link]()
- [x] Add a screenshot to `snap/README.md`
- [x] Register the snap in the Snap Store, **using the preferred upstream name**(i.e. without custom postfix).  If the preferred upstream name is not available or reserved, [file a request to take over the preferred upstream name](https://dashboard.snapcraft.io/register-snap) and temporary use a name with personal postfix instead.  
      (3-letter snap name is not possible for this application, use alternative instead)
- [x] Setup [build.snapcraft.io](https://build.snapcraft.io) and publish the `devmode` snap in the Snap Store edge channel
- [x] Add the provided Snapcraft build badge to `snap/README.md`
- [x] Update snap's metadata, icons and screenshots on the [dashboard](https://dashboard.snapcraft.io)
- [x] Add install instructions to `snap/README.md`
- [x] File an Intent-To-Package issue/bug to the upstream's contact or issue/bug tracker to consolidate and let the upstream acknowledge the effort - [template](https://github.com/Lin-Buo-Ren/snapcrafters-template-plus/wiki/Intent-To-Package-Template) - [link](https://github.com/NXPmicro/mfgtools/issues/221)
- [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
- [x] Publish the confined snap in the Snap Store beta channel
- [x] Update the install instructions in `snap/README.md`
- [x] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io) - [template](https://github.com/Lin-Buo-Ren/snapcrafters-template-plus/wiki/Call-for-Testing-Template) - [link](https://forum.snapcraft.io/t/call-for-testing-universal-update-utility/19952)
- [x] (skipped, already upstreamed) Publish the snap in the Snap Store stable channel
- [ ] (skipped, already upstreamed) Update the install instructions in `snap/README.md`
- [ ] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io) - [template](https://github.com/Lin-Buo-Ren/snapcrafters-template-plus/wiki/Release-Announcement-Template) - [link]()
- [x] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers - [example](https://github.com/htacg/tidy-html5/pull/749) - [link](https://github.com/NXPmicro/mfgtools/pull/255)
- [ ] (skipped, already done by upstream) Submit a pull request or patch upstream that adds snap install documentation - [example](https://github.com/htacg/html-tidy.org/pull/11) - [link]()

If the upstream accepts the PRs **AND** willing to maintain the package on the Snap Store:
- [x] Request upstream create a Snap Store developer account
- [x] Create a topic [under the `store` category in the Snapcrafters Forum](https://forum.snapcraft.io/c/store) to request the snap be transferred to upstream - [template](https://github.com/Lin-Buo-Ren/snapcrafters-template-plus/wiki/Ownership-Transfer-Template#transfer-to-upstream) - [link]()

If the upstream rejects the offer:

- [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your/upstream's repo into github.com/snapcrafters, transfer the snap name from you to snapcrafters, and configure the repo for automatic publishing into edge on commit - [template](https://github.com/Lin-Buo-Ren/snapcrafters-template-plus/wiki/Ownership-Transfer-Template#transfer-to-the-snapcrafters-organization) - [link]()

Finally:

* [ ] Ask the Snap Advocacy team to celebrate the snap - [explanation](https://forum.snapcraft.io/t/what-is-ask-the-snap-advocacy-team-to-celebrate-the-snap/8808/7) -  [link]()

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

<!--
Refer the following page for setting a Gravatar:

    Gravatar - Globally Recognized Avatars
    https://en.gravatar.com/

Refer the following page for how to generate Gravatar image URL:

    Developer Resources - Gravatar - Globally Recognized Avatars
    https://en.gravatar.com/site/implement/

You may generate the unique hash by using the following command in terminal:

    printf username@example.com | tr '[:upper:]' '[:lower:]' | md5sum

-->

## Contacts
| Packager | Upstream |
| :-: | :-: |
| [![Packager's avatar](http://gravatar.com/avatar/66a5b84972e73e895d5d68d48b1e1e21/?s=128)<br>林博仁(Buo-ren, Lin)](mailto:Buo.Ren.Lin@gmail.com) | [Upstream's issue tracker](https://github.com/NXPmicro/mfgtools/issues) |
