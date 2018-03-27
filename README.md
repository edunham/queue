# queue

Email/IRC: 

* Servo Infra accts for password manager
  - [x] Lars
  - [ ] Aneesh -- guest acct requested by email from servicedesk
  - [x] Manish
  - [x] Josh
  - [ ] Nox
  - [x] Jack

* Gathering input in "Naming preferences for MixedReality properties?" thread


Bugzilla: 

* https://bugzilla.mozilla.org/show_bug.cgi?id=1449017 blog.mr.m.o
* Netlify saga https://bugzilla.mozilla.org/show_bug.cgi?id=1410453
* Games repo tasks outlined in https://bugzilla.mozilla.org/show_bug.cgi?id=1438488#c11
* Travis/Rust RRA https://bugzilla.mozilla.org/show_bug.cgi?id=1389648
* Daala TC https://bugzilla.mozilla.org/show_bug.cgi?id=1261110

* MR password manager -- transfer notes from Google Docs



### From awhile back:

Stuff that's not publicly on GitHub: 

* AFrame cloudfront
* AFrame infra issue tracker-or-something
* Netlify: Bugzilla https://bugzilla.mozilla.org/show_bug.cgi?id=1410453, remember to update admin docs @ link in ticket when done
* http://trac.buildbot.net/wiki/RunningBuildbotOnWindows for unbreaking windows builders

blocked on external: 
* ~~bug filed for WR laptop hosting RITM0057316 in servicenow (:bangbang: WR benchmark machine https://github.com/servo/saltfs/issues/614) https://bugzilla.mozilla.org/show_bug.cgi?id=1409205~~ well we're now in ServiceNow REQ0052233, James is setting up remote access which I'll then provide to GW
- https://github.com/servo/saltfs/issues/734 may have hit a salt bug for newer OSXs, Salt folks confirm it's a Salt bug w/ labels on https://github.com/saltstack/salt/issues/44130

PRs in flight: 
- utf8 locale https://github.com/servo/saltfs/pull/714 -- fixed conflicts, has an intermittent
- linux slave swapfile https://github.com/servo/saltfs/pull/715
- user accounts https://github.com/servo/saltfs/pull/628
- .taskcluster.yml https://github.com/servo/servo/pull/17580
- servo-gecko-try minion https://github.com/servo/saltfs/pull/700 :bangbang: servo-gecko-try deploy https://github.com/servo/saltfs/issues/619 (requires https://github.com/servo/saltfs/pull/700)
- doc locations https://github.com/rust-lang/rust-buildbot/pull/155
- python version https://github.com/servo/saltfs/pull/542
- unattended-upgrades https://github.com/servo/saltfs/pull/276 (https://github.com/servo/saltfs/issues/275)
- tidy stuff (tracking: https://github.com/servo/servo/issues/10636)
  - https://github.com/servo/rust-azure/pull/222
  - https://github.com/servo/rust-layers/pull/233
  - https://github.com/servo/gaol/pull/26
  - https://github.com/servo/ipc-channel/pull/67
- iptables https://github.com/servo/saltfs/pull/108


Issues:

- update servo builders https://github.com/servo/saltfs/issues/462
- ~~upgrade linux cross builders https://github.com/servo/saltfs/issues/711~~ -> https://github.com/servo/saltfs/pull/715
- homu unboundlocalerror https://github.com/servo/homu/issues/67
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
- Buildbot git breakage https://github.com/servo/servo/issues/18338
- mac7 git errors https://github.com/servo/servo/issues/18228
- Travis secret refresh https://github.com/servo/saltfs/issues/664
- homu command syntax change https://github.com/servo/saltfs/issues/624
- more tests on Windows https://github.com/servo/saltfs/issues/556
- salt file removal issue https://github.com/servo/saltfs/issues/552
- page load perf testing https://github.com/servo/servo/issues/12988
- osmesa libs https://github.com/servo/saltfs/issues/468
- servo binary signing https://github.com/servo/servo/issues/12532
- SRI hash test https://github.com/servo/download.servo.org/issues/7
- publish servo-perf logs https://github.com/servo/servo/issues/11167
- CI setup for repos: 
  -  mozjs linux https://github.com/servo/rust-mozjs/issues/254
  - ipc-channel android, mac, windows https://github.com/servo/ipc-channel/issues/23
  - rust-layers android, mac, windows https://github.com/servo/rust-layers/issues/222
- broken servo css test https://github.com/servo/servo/issues/7625
- TUF https://github.com/rust-lang/crates.io/issues/75
- add gecko to perf https://github.com/servo/saltfs/issues/712
- add gecko to WR https://github.com/servo/webrender/issues/1589

"enhance!"
- enhancement: salt migration checklists https://github.com/servo/saltfs/issues/488
- enhancement: reproducible builds https://github.com/servo/servo/issues/11980
- enhancement: rootless Salt https://github.com/servo/saltfs/issues/657
- enhancement: homu block till landing https://github.com/servo/homu/issues/111
- enhancement: more homu hooks https://github.com/servo/homu/issues/105
- enhancement: better homu concurrency https://github.com/servo/homu/issues/102
- enhancement: server admin log https://github.com/servo/saltfs/issues/709
- enhancement: sccache https://github.com/servo/servo/issues/17106
- enhancement: per-directory reviewers https://github.com/servo/highfive/issues/147
- enhancement: CORS for buildbot logs https://github.com/servo/saltfs/issues/354
