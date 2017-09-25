# queue

Stuff that's not on GitHub: 

* check with IT on WR laptop hosting
* AWS account setup for MR -> blocked on IT, nagging daily

PRs in-flight: 

- linux slave swapfile https://github.com/servo/saltfs/pull/715
- utf8 locale https://github.com/servo/saltfs/pull/714
- log rotation https://github.com/servo/saltfs/pull/710
- .taskcluster.yml https://github.com/servo/servo/pull/17580
- servo-gecko-try minion https://github.com/servo/saltfs/pull/700
- user accounts https://github.com/servo/saltfs/pull/628
- doc locations https://github.com/rust-lang/rust-buildbot/pull/155
- python version https://github.com/servo/saltfs/pull/542
- unattended-upgrades https://github.com/servo/saltfs/pull/276 (https://github.com/servo/saltfs/issues/275)
- tidy stuff (tracking: https://github.com/servo/servo/issues/10636)
  - https://github.com/servo/rust-azure/pull/222
  - https://github.com/servo/rust-layers/pull/233
  - https://github.com/servo/gaol/pull/26
  - https://github.com/servo/ipc-channel/pull/67
- iptables https://github.com/servo/saltfs/pull/108
- highfive tests https://github.com/nrc/highfive/pull/58

Blocked last time I checked: 

- update servo builders https://github.com/servo/saltfs/issues/462


Issues:

- :bangbang: WR benchmark machine https://github.com/servo/saltfs/issues/614
- ~~upgrade linux cross builders https://github.com/servo/saltfs/issues/711~~ -> https://github.com/servo/saltfs/pull/715
- homu unboundlocalerror https://github.com/servo/homu/issues/67
- :bangbang: servo-gecko-try deploy https://github.com/servo/saltfs/issues/619 (requires https://github.com/servo/saltfs/pull/700)
- Servo observatory score https://github.com/servo/saltfs/issues/473
- locking master branch https://github.com/servo/servo/issues/12771
- salt log policy https://github.com/servo/saltfs/issues/437
- nightly failure notifications https://github.com/servo/saltfs/issues/413
- 2fa for build infra access https://github.com/servo/saltfs/issues/399
- rust-www headers https://github.com/rust-lang/rust-www/issues/165
  - also signatures https://github.com/rust-lang/rust-www/issues/112
- rust repos without licenses https://github.com/rust-lang/rust/issues/25664

- crates.io SSL https://github.com/rust-lang/crates.io/issues/621
- put build results on perfherder https://github.com/servo/servo/issues/13430
- :bangbang: salt the letsencrypt renewal https://github.com/servo/saltfs/issues/423
- mac6 breakage https://github.com/servo/servo/issues/18374
- Buildbot git breakage https://github.com/servo/servo/issues/18338
- mac7 git errors https://github.com/servo/servo/issues/18228
- enhancement: server admin log https://github.com/servo/saltfs/issues/709
- mac9 & mac5 slow https://github.com/servo/servo/issues/17873
- enhancement: sccache https://github.com/servo/servo/issues/17106
- Travis secret refresh https://github.com/servo/saltfs/issues/664
- enhancement: rootless Salt https://github.com/servo/saltfs/issues/657
- enhancement: homu block till landing https://github.com/servo/homu/issues/111
- enhancement: more homu hooks https://github.com/servo/homu/issues/105
- homu command syntax change https://github.com/servo/saltfs/issues/624
- enhancement: better homu concurrency https://github.com/servo/homu/issues/102
- more tests on Windows https://github.com/servo/saltfs/issues/556
- salt file removal issue https://github.com/servo/saltfs/issues/552
- enhancement: salt migration checklists https://github.com/servo/saltfs/issues/488
- page load perf testing https://github.com/servo/servo/issues/12988
- osmesa libs https://github.com/servo/saltfs/issues/468
- servo binary signing https://github.com/servo/servo/issues/12532
- SRI hash test https://github.com/servo/download.servo.org/issues/7
- enhancement: reproducible builds https://github.com/servo/servo/issues/11980
- publish servo-perf logs https://github.com/servo/servo/issues/11167
- enhancement: CORS for buildbot logs https://github.com/servo/saltfs/issues/354
- CI setup for repos: 
  -  mozjs linux https://github.com/servo/rust-mozjs/issues/254
  - ipc-channel android, mac, windows https://github.com/servo/ipc-channel/issues/23
  - rust-layers android, mac, windows https://github.com/servo/rust-layers/issues/222
- broken servo css test https://github.com/servo/servo/issues/7625
- TUF https://github.com/rust-lang/crates.io/issues/75
- add gecko to perf https://github.com/servo/saltfs/issues/712
- add gecko to WR https://github.com/servo/webrender/issues/1589
- enhancement: per-directory reviewers https://github.com/servo/highfive/issues/147
